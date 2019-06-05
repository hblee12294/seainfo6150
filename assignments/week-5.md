# INFO6150 Week 5 Assignments
Due by the beginning of class, week 6 (June 12).
You may revise up to 2 times by the beginning of class, week 7 (June 19).

This week you will be practicing working in the web app, creating a branch from an existing branch, creating a couple of React component and adding styling. 

## fetch branches and create a week-5 branch that tracks the upstream/week-5 branch
This means that a local branch is created from the `week-5` branch from upstream
```
cd seainfo6150-webapp
git fetch upstream
git checkout --track upstream/week-5
```

## create an ArticleList directory
```
mkdir ArticleList
```

## create a list item component
Create a new functional component in `ArticleList` named `ArticleListItem.jsx` that displays data about each of the news articles in `seainfo6150-webapp/src/data/articles.json` as a list item that will be displayed as part of an *unordered list*. **You should not modify `articles.json` in any way.**

The article data should be marked up in the list item with valid, semantically-appropriate HTML. Consider how you should properly mark up a list item, cite the author, the date, etc.

**You should be able to use week-4's Article.js component as the basis for this component.**

`ArticleListItem` must accept these 5 props:
* title: a string
* date: a date string
* year: a year string
* author: a string
* shortText: a string

## create a list component
Create a new functional component in `ArticleList` named `ArticleList.jsx`, with the appropriate valid, semantically-correct containing HTML to create an unordered list.

`ArticleList` must accept this 1 prop:
* articles: all the news articls being passed from `src/App.js`


Copy and paste the following block of code between your unordered list tags to output each of the articles as an `ArticleListItem` component. **You must add the required props from `article` to pass into `ArticleListItem`!**

```
{
  // this iterates through the articles JSON and
  // calls your ArticleListItem component for each article object
  Object.values(articles).map(article => {
    return <ArticleListItem />
  })
}
```

The list should be marked up with valid, semantically-appropriate HTML. 

## style the components
Create styles for the two new components in css module files named `ArticleList.module.css` and `ArticleListItem.module.css`. Make sure to import the css into `ArticleList/ArticleList.jsx` and `ArticleList/ArticleListItem.jsx` as demonstrated in class using CSS modules. Please style your components to match <a href="./week-5-list.png">this screenshot</a> as closely as possible.

## import the component
In `src/App.js`, import and render the `ArticleList/ArticleList.jsx` so that it is displayed on the main app page (http://localhost:3000). Don't forget to pass the `articles` prop to it!

## start the webapp
Start the webapp and verify that it is displayed as shown in <a href="./week-5-list.png">this screenshot</a>.
```
npm start
```

## save it 
save and commit your work to the week-4 branch and push to your fork
```
git add . 
git commit -m "[your commit message]"
git push origin week-5
```

## send an email 
Email Anitha at lakshmanan.t@husky.neu.edu with a link to your seainfo6150-webapp fork. 


<table>
  <caption>Rubric</caption>
  <tbody>
    <tr>
      <td>Created and saved assignment to week-5 branch</td>
      <td>1</td>
    </tr>
    <tr>
      <td>Semantic, properly marked-up article list and article list item</td>
      <td>1</td>
    </tr>
    <tr>
      <td>Created functional components `ArticleList` and `ArticleListItem`</td>
      <td>2</td>
    </tr>
    <tr>
      <td>Styled functional components `ArticleList` and `ArticleListItem` as closely to screenshot as possible</td>
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
