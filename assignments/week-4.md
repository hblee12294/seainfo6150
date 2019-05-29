# INFO6150 Week 4 Assignments
Due by the beginning of class, week 5 (June 5).
You may revise up to 2 times by the beginning of class, week 6 (June 12).

This week you will be practicing working in the web app, creating a tracking branch, creating a React component and passing props. 

## fetch branches and create a week-4 branch that tracks the upstream/week-4 branch
This means that a local branch is created from the `week-4` branch from upstream
```
cd seainfo6150-webapp
git fetch upstream
git checkout --track upstream/week-4
```

## create a component
Create a functional component that displays the news article being passed to `src/App.js`.

You **must** name this component `src/Article.js`.

Article.js accepts 1 prop:
* article: the news article being passed to `src/App.js`

You should create valid, semantically-appropriate HTML to display the article attributes shown in the proptypes in `src/App.js`. Consider block level and inline HTML elements, what kind of text this is and how you should properly cite the author, properly display the date, email address etc. Make sure to validate your text with an HTML validator like http://validator.w3.org!

Note: as in week 3, because you are writing this in the React app, HTML attributes work slightly differently. Most relevant for this assignment, you will use the following attribute for one of your tags: 
`dateTime={article.pubYear}` (note the camelCase syntax)

## import the component
In `src/App.js`, import and render the functional component so that it is displayed on the main app page (http://localhost:3000). Don't forget to pass the article prop to it!

## start the webapp
Start the webapp and verify that it is displayed as shown in <a href="./week-4-component.png">this screenshot</a>.
```
npm start
```

## save it 
save and commit your work to the week-4 branch and push to your fork
```
git add . 
git commit -m "[your commit message]"
git push origin week-4
```

## send an email 
Email Anitha at lakshmanan.t@husky.neu.edu with a link to your seainfo6150-webapp fork. 


<table>
  <caption>Rubric</caption>
  <tbody>
    <tr>
      <td>Created and saved assignment to week-4 branch</td>
      <td>2</td>
    </tr>
    <tr>
      <td>Semantic, properly marked-up article attributes</td>
      <td>2</td>
    </tr>
    <tr>
      <td>Created and imported functional component `src/Article.js`</td>
      <td>4</td>
    </tr>
    <tr>
      <td>Valid HTML</td>
      <td>1</td>
    </tr>
    <tr>
      <td>App runs and displays article properly</td>
      <td>1</td>
    </tr>
  </tbody>
  <tfoot>
    <td>Total:</td>
    <td>10</td>
  </tfoot>
</table>
