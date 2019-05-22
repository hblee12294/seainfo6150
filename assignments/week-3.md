# INFO6150 Week 3 Assignments

This week you will be practicing working in the web app, creating a branch and marking up text with HTML!

1. create a week-3 branch
```
cd seainfo6150-webapp
git checkout master
git pull upstream master
git checkout -b week-3
```

2. Copy and paste text into App.js
Copy and paste the news article from <a href="./week-3-article.md">assignments/week-3-article.md</a> into App.js as shown in <a href="./week-3-paste-text.png">this screenshot</a>. 

3. Start the webapp
```
npm install (only the first time you ever run the app)
npm start
```

4. Add HTML
Mark up the news article with valid, semantically-appropriate HTML. Consider block level and inline HTML elements, what kind of text this is and how you should properly cite the author, properly display the date, email address etc. Make sure to validate your text with an HTML validator like http://validator.w3.org!

5. Save and commit your work to the week-3 branch and push to your fork
```
git add . 
git commit -m "[your commit message]"
git push origin week-3
```

6. Send an email to Anitha at lakshmanan.t@husky.neu.edu with a link to your seainfo6150-webapp fork. 
