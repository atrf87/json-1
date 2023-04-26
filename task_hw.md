#### 1. Create an external repository called "json"
```
GitHub ➡️ New repository ➡️ Create repository 
```
#### 2. Clone the JSON repository to a local machine
```
git clone <SSH key>
```
#### 3. Inside the local JSON create a “new.json” file
```
cd json/
cat > new.json
```
#### 4. Add changes to indexed files section
```
git add .
```
#### 5. Commit the file
```
git commit -m "commit message"
```
#### 6. Push the file to the external GitHub repository
```
git push
```
#### 7. Edit the content of the file “new.json” - write information about yourself (name, age, number of pets, future desired salary). Everything is written in json format
```
{
    "name": "Anna",
    "surname": "Gvozdeva",
    "age": 31,
    "pets": 0,
    "desired_salary": 100000
}
```
#### 8. Push changes the an external repository
```
git add .
git commit -m "commit message"
git push
```
#### 9. Create a file "preferences.json"
```
cat > preferences.json
```
#### 10. In the file "preferences.json", add information about your preferences (favorite movie, favorite TVshow, favorite food, favorite season, country you would like to visit). In json format
```
{
    "favorite_movie": "Midnight in Paris",
    "favorite_TVshow": "The Sopranos",
    "favorite_food": "Italian cuisine",
    "favorite_season": "Spring",
    "country_to_visit": "China"
}
```
#### 11. Create a file "skills.json" and add information about the skills that will be studied in the course. In json format
```
{
    "skill_1": "QA_Theory",
    "skill_2": "HTTP",
    "skill_3": "GIT",
    "skill_4": "Postman",
    "skill_5": "Charles",
    "skill_6": "DevTools",
    "skill_7": "VPN",
    "skill_8": "Android_Studio",
    "skill_9": "Xcode",
    "skill_10": "Terminal",
    "skill_11": "SQL"
}
```
#### 12. Send two files at once to the external repository 
```
git add .
git commit -m "commit message"
git push
```
#### 13. On the web interface, create a file "bug_report.txt"
```
➡️ Add file ➡️ Create new file
```
#### 14. Press "Commit changes", save changes on the web interface
```
➡️ Commit new file
```
#### 15. On the web interface, modify the file "bug_report.json" and add a bug report. In json format
```
{
    "ID": "01",
    "Title": "No notification, in the authorization form, about the successful registration of a new user",
    "STR": 
    {
        "1. Go to the main page of the site (link)",
        "2. Enter data in the  \"Login\" field",
        "3. Enter data in the \"Password\" field",
        "4. Press \"Register\""
    },
    "Environment":
    {
        "OS": "iOS 16.2 iPhone 12 Pro",
        "Browser": "Safari 16.2"
    },
    "Actual result": "A message appears, about successful registration",
    "Expected result": "A user has no understanding of the registration result",
    "Severity": "Minor",
    "Priority": "Low",
    "Attachments": "Link to the image or video with the bug"
}
```
#### 16. Press "Commit changes" and save changes on the web interface
```
➡️ Commit changes 
```
#### 17. Synchronize the external and the local JSON repository
```
git pull
```