# INFO6150 Final Project

You work for the marketing department of a small, technology-focused university called Seattle Technological University.

Your team has been tasked with designing, building and testing a new website for the university. The marketing department is especially interested in getting students to enroll in one of the many degree programs available in one of the six different schools. At the very least, they would like students to sign up for the email newsletter. 

I have already implemented some pieces of the website that relate to routing, iterating over data, text content, etc.

Your role is to coordinate with your team to build the UI pieces and CSS stylesheets that display the data in a usable, accessible and attractive way.

You are encouraged to do research and look at other college websites to get ideas about how to present the Seattle Technological University website.

===

## Rubric

This project is worth 30% of your final grade.

### Final website

15% of your final grade will be the total score of the website produced based on the rubric below. The same score will be awarded identically amongst all team members.

Projects will be evaluated on a 0-100 scale for each of 5 sections. Each section score will be multiplied by .20 and the 5 sections will be added together to calculate the final 0-100 score.

<table>
  <thead>
    <tr>
      <th></th>
      <th>Meets expectations (100-75)</th>
      <th>Mostly meets expectations (75-50)</th>
      <th>Does not meet expectations (50-25)</th>
      <th>Incomplete (25-0)</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>1. HTML</td>
      <td>Site validation has no errors and few warnings, HTML is semantic and well-formed</td>
      <td>Site validation has one or two errors and/or several warnings, HTML is mostly semantic and well-formed.</td>
      <td>Site validation has several errors and/or warnings, HTML is not very semantic.</td>
      <td>Site validation has many errors and/or warnings, HTML is not semantic or unfinished.</td>
    </tr>
    <tr>
      <td>2. CSS</td>
      <td>CSS shows mastery, is clearly organized using CSS modules, fully responsive and has at least 2 adaptive breakpoints</td>
      <td>CSS shows nearing mastery and/or is included globally in index.css, is mostly responsive and has at least 1 adaptive breakpoint</td>
      <td>CSS does not show mastery, is sparse and/or is included globally in index.html, is only somewhat responsive and/or has no adaptive breakpoints</td>
      <td>CSS is very crude, near non-existent and/or unfinished, is not responsive</td>
    </tr>
    <tr>
      <td>3. Usability/accessibility</td>
      <td>Project shows good principles of usability and accessibility. It is clear and easy to use/navigate.</td>
      <td>Project shows ok principles of usability and accessibility.</td>
      <td>Project shows some principles of usability and accessibility but could use much improvement.</td>
      <td>Project is difficult to use and shows little or no principles of usability/accessibility.</td>
    </tr>
    <tr>
      <td>4. Requirements</td>
      <td>Project requirements are fully or almost fully implemented</td>
      <td>Project requirements are mostly implemented</td>
      <td>Project requirements are somewhat implemented</td>
      <td>Project requirements are mostly not implemented (project is unfinished)</td>
    </tr>
    <tr>
      <td>5. Overall result/presentation</td>
      <td>Project presented in class shows good effort and refinement</td>
      <td>Project presented in class shows OK effort and refinement</td>
      <td>Project presented in class shows low effort</td>
      <td>Project was not presented in class and/or shows barely any effort</td>
    </tr>
  </tbody>
  <tfoot>
    <td colspan="5">Total: </td>
  </tfoot>
</table>

### Journal/writeup

15% of your final grade will be your individual score as determined by the level of effort/participation detailed in your project journal/writeup. You should keep this journal while your team is working on the project as a record of your individual participation.

In this writeup, you should include a **detailed description of your contributions to the project**, especially detailing any challenges you encountered during the project and how you resolved them, extra effort you put in, etc. Feel free to include things like links to your shared team repo, screenshots, google docs histories, etc. to support your description. 

This should not be simply a summary of the work done by the team but a record of what you personally contributed/worked on.

<table>
  <thead>
    <tr>
      <th></th>
      <th>100-75</th>
      <th>75-50</th>
      <th>50-25</th>
      <th>25-0</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Participation</td>
      <td>Writeup provides detailed description and is well supported by checkins to repo, screenshots, etc.</td>
      <td>Writeup provides mostly thorough description and has some supporting details.</td>
      <td>Writeup is brief and provides few details.</td>
      <td>Writeup is very brief, incomplete or unfinished/missing.</td>
    </tr>
  </tbody>
  <tfoot>
    <td colspan="5">Total: </td>
  </tfoot>
</table>

### HTML

The HTML for your website must be semantically correct and valid to the best of your ability. I will be validating the site with the W3 HTML Validator (http://validator.w3.org).

**You are encouraged to make any changes you wish to the HTML and components here. Do not assume that any HTML already included is valid and/or final.**

===

## Schedule

### Week 10, July 10

We will finalize teams and review project. With your team (if possible), you will work on look and feel, wireframes and sitemap for the website.

The following pieces should be emailed to me for feedback **by 2pm EDT, July 17** (ie, the beginning of Week 11 class). You can send a Word document, PDF, etc. 

#### Look and feel

Your team should give me 3 look and feel words (eg, "bold", "calm") that you want your website to convey and an explanation of how your website will convey that using concepts discussed in class.

#### Wireframes

You must have wireframes for

- Homepage
- About
- Contact
- Calendar
- 404
- Schools page (all schools, with links to each of the degree detail pages for the school)
- Degrees page (all degrees)
- Degree (single degree detail page)
- Enrollment flow (1. form, 2. summary / thank you screen)

#### Site map

You must create a sitemap showing all the pages of the site

### Week 11, July 17

With your team, you will work on project implementation

### Week 12, July 24

In class, we will conduct usability testing on each others' websites and provide feedback that teams can use to finalize their projects.

### Week 13, July 31

Each team will demonstrate their final website to the rest of the class. Personal journals/writeups should be emailed to a.bingham@northeastern.edu **by midnight EDT, July 31**.

===

## Project Requirements

Seattle Technological University has many degrees offered by the six different schools. Current degree offerings can be viewed in `src/data/degrees.json`. The schools can be viewed in `src/data/schools.json`.

There are already some components built for you to use in your project. I encourage you to explore the components in the `src` directory. 


### Layout

The website should be both **responsive and adaptive**; you **must** implement at **least 2 breakpoints** where the layout updates in an obvious fashion.

Each page should use good principles of usability and accessibility discussed in class!


### Images

In /public/images, there are a number of images that are relevant to college life. Your website must use **at least 5** of these images, and **at least one** of those images must be used as a background image on some element. Your images should be responsive along with the rest of the website. 


### Navigation

The website must display a main navigation menu on every page.

- Home
- Schools
- Degrees
- Calendar
- About
- Directions and Contact

Where you choose to place this navigation menu is up to you, but it should reflect good principles of usability.

### `HomePage` page
Your website must feature a homepage for Seattle Technological University. The name "Seattle Technological University" must appear on the homepage and in the title of every page of the website.


### `SchoolsPage` page

This page should display a list of each of the schools in the university. Each school must display the school name, summary text and the list of all degrees for that school, each of which must link to the individual `DegreePage`.

This page **must** use grid or flex to display the schools. 


### `DegreesPage` page

This page should display a list of all degrees available at the university. It should also display the `DegreesSorterFilterer` component so that the degrees can be filtered or sorted by various parameters.  

This page **must** use grid or flex to display the degrees. Each degree must display at least the degree image and the degree title, plus the link to the individual degree page. 


### `DegreePage` page

This page should display the information about the individual degree.

You must display the following pieces of data from `src/data/degrees.json` on the `DegreePage`.

- degree image -- this is already implemented but needs styling and should be responsive
- level: levels should be printed in different colors
  - Beginner: green
  - Intermediate: blue
  - Advanced: red
  - Mastery: purple
- list of schools offering this degree. Each school should be in the format "School of [school name]"  
- short summary
- list of syllabus PDF urls. Each URL should be linked properly to the syllabus. If there are no PDFs to link, then this list should not appear on the page
- title

This page sends the user into the first step of the enroll flow via an enroll link.


### `EnrollPage` page

This page collects information about a student for enrollment. It has two parts:

#### The enroll form
The enroll form collects the following information: 
- Student full name
- Student email address * (format: foo@bar.com)
- Student address 
  - street address
  - city
  - state
  - zip code * (format: XXXXX)
- Student phone number * (format: XXX-XXX-XXXX)
- Student date of birth * (format: YYYY-MM-DD)
- Student gender (male, female, other, prefer not to say)
- Student preferred pronouns (he/him, she/her, they/them, other, prefer not to say)
- Student degree of interest (could choose multiple degrees of interest)

All fields are **required**. If a user does not fill in one of the required fields, the UI should alert them to that fact when attempting to move on in the order flow.

Fields with stars after them should be validated to make sure they follow the given format.

#### The enroll confirmation/thank you
Upon submitting the enroll form, the confirmation page should display back the values that the student entered in a user-friendly, readable format. 


### `CalendarPage` page

This page should display a list of current calendar events from `src/data/calendar.json` for the university. 


### `AboutPage` page

This page should display content about the university. 


### `ContactPage` page

This page should display contact information, directions, etc about the university. 

#### The newsletter form
This page also contains a form where a student can sign up for the newsletter. 

The newsletter form collects the following information: 
- Student email address * (format: foo@bar.com)

Fields with stars after them should be validated to make sure they follow the given format.


### `ErrorPage` page

The website should display an attractive, usable and accessible 404 page when visiting an unmatched route.

===

### Routes

All of the pages of the site are available via components controlled by a router. This simplifies the process of linking the pages together and gives a straightforward mapping of which component is associated with which URL of the website.

There is already a router implemented with the following routes in place.

#### `/`

corresponds to `http://localhost:3000/` and the `HomePage` component; the homepage of the website.

#### `/schools`

corresponds to `http://localhost:3000/schools` and the `SchoolsPage` component; the list of all schools.

#### `/degrees`

corresponds to a route like `http://localhost:3000/degrees` and the `DegreesPage` component; the list of all degrees offered by the university.

#### `/calendar`

corresponds to a route like `http://localhost:3000/calendar` and the `CalendarPage` component; the list of all calendar events offered by the university.

#### `/degree/:slug`

corresponds to a route like `http://localhost:3000/degree/ai-product-manager-nanodegree--nd088` and the `DegreePage` component; the listing for a specific degree. _The degree slug must be supplied in the URL or the route will not be matched._

#### `/enroll/:slug`

corresponds to a route like `http://localhost:3000/enroll/ai-product-manager-nanodegree--nd088` and the `EnrollPage` component; the enroll flow for a specific degree. _The degree slug must be supplied in the URL or the route will not be matched._

#### `/about`

corresponds to `http://localhost:3000/about` and the `AboutPage` component; the about page of the university.

#### `/contact`

corresponds to `http://localhost:3000/contact` and the `ContactPage` component; the contact page of the university.

#### `/404`

corresponds to `http://localhost:3000/404` and the `ErrorPage` component; the 404 page of the university.
