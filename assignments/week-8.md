# INFO6150 Week 8 Assignments

Due by the beginning of class, week 9 (July 3).
You may revise up to 2 times by the beginning of class, week 10 (July 10).

This week you will be practicing adding a responsive layout to your components from last week.

**You should finish all your week 6 revisions before starting the week 8 assignment**


## create a week-8 branch from your week-6 branch
You will be using the components you created last week for this week's assignment.

```
cd seainfo6150-webapp
git checkout week-6
git pull upstream master
git checkout --b week-8
```

## create a new layout for the articles list
Create as many new components as you think appropriate to create a layout framework for the news articles as shown in <a href="./week-8-list.png">this screenshot</a>. Your components should have semantically-valid, accessible HTML.


## style the components
Create styles for your new components (and update the styles for the ArticleList/ArticleListItem/ArticleImage components from week 6) to match <a href="./week-8-list.png">this screenshot</a> as closely as possible.

The red header where `The INFO6150 News` is displayed **must** use flexbox styling in some way.

The grey section where the articles are displayed **must** use grid styling in some way.


## start the webapp

Start the webapp and verify that it is displayed as shown in <a href="./week-6-list.png">this screenshot</a>.

```
npm start
```

## save it

save and commit your work to the week-8 branch and push to your fork

```
git add .
git commit -m "[your commit message]"
git push origin week-8
```

## send an email

Email Anitha at lakshmanan.t@husky.neu.edu with a link to your seainfo6150-webapp fork.

<table>
  <caption>Rubric</caption>
  <tbody>
    <tr>
      <td>Created and saved assignment to week-8 branch</td>
      <td>1</td>
    </tr>
    <tr>
      <td>Styled the header with flexbox</td>
      <td>2</td>
    </tr>
    <tr>
      <td>Styled the articles with grid</td>
      <td>5</td>
    </tr>
    <tr>
      <td>Valid HTML</td>
      <td>1</td>
    </tr>
    <tr>
      <td>App runs and displays article list properly</td>
      <td>1</td>
    </tr>
  </tbody>
  <tfoot>
    <td>Total:</td>
    <td>10</td>
  </tfoot>
</table>
