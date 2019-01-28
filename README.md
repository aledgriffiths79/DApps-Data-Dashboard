# DApps Data Dashboard

Second Milestone project for code institute full stack developer course interactive frontend development.
It is a single page responsive application visualizing data of decentralised applications statistics.

#### The Project Brief:
##### CREATE A DATA DASHBOARD

* Build a data dashboard that visualizes a dataset of your choice
* Your data can be stored locally (e.g., in a js file) or sourced from an API
* Visualise your data using D3.js and dc.js


## UX

This App was developed for users looking for statistics on decentralised applications(DApps) that run on blockchain platforms.
The platforms I picked were Ethereum(ETH), EOSIO(EOS) and Tron(TRX), I selected the top 15 DApps on each platform
and built a dataset of the platforms, names, category, amount of users over 24hr period and the amount daily and weekly transactions(txs) of each DApp.

### Style

For this app i picked a darker theme from [bootswatch](https://bootswatch.com/sandstone/) called sandstone which included fonts, colors and theming.
DC css file was also used for styling charts, I used some custom css in styles.css to override some of the styles in the bootswatch theme and edited
dc.min.css to change values of the chart styles.
I used a dark color for the body background and a lighter shade for the cards that hold the charts.

### User Stories

- As a new or experienced user to blockchain and DApps i want to find information on:
    * Amount of users per platform
    * DApps categories statistics
    * Amount of weekly transactions per platform
    * Amount of daily users per DApp
    * Amount of daily users and the daily transactions per DApp
    * Amount of daily/weekly transactions per DApp

#### Home Section Contains:

1. Dashboard introduction paragraph
2. Links in paragraph to read more about the blockchain platforms
3. Selectors for filtering the dataset

#### User/Category Section Contains:

* 3 Charts in a row
    1. Platform Users Breakdown pieChart
    2. Categories Stats barChart
    3. Weekly Transactions pieChart

#### DApps Users Section Contains:

* Daily DApps Users rowChart

#### Daily User Transactions Section Contains:

* Daily User Transactions scatterplotChart

#### DApps Daily and Weekly Transactions Section Contains:

* DApps Daily and Weekly Transactions stackedbarChart

### Mock-Ups

1. [Desktop](https://camo.githubusercontent.com/fd8931475416b2fc463dd1b15323ad8bdef33643/68747470733a2f2f6170702e6769746b72616b656e2e636f6d2f6170692f676c6f2f626f617264732f3563333330653838666566333839303030666534333033342f6174746163686d656e74732f356334646365613039323638326630303066323336663865)
2. [Tablet](https://camo.githubusercontent.com/fcb297dc9f86630d6f1a2966ef585af4655ed237/68747470733a2f2f6170702e6769746b72616b656e2e636f6d2f6170692f676c6f2f626f617264732f3563333330653838666566333839303030666534333033342f6174746163686d656e74732f356334646365613039323638326630303066323336663862)
3. [Mobile](https://camo.githubusercontent.com/58fd5cf3d9d14f65a45feb366f1d8d02b8dd911c/68747470733a2f2f6170702e6769746b72616b656e2e636f6d2f6170692f676c6f2f626f617264732f3563333330653838666566333839303030666534333033342f6174746163686d656e74732f356334646365613039323638326630303066323336663931)

### Project Management

For this project [Git Kraken/GloBoards](https://www.gitkraken.com/) was used as a task/issue tracker board which is synced
to the project repo on github.
Sections included - issues, to Do, in Progress, to be reviewed, completed, bugs.

#### Usage

* When starting the project:
    1. Create cards
    2. Add descriptions
    3. Add assignee
    4. Add labels
    5. Add tasks
    6. Add files and comments where needed

* During the Project:
    1. Move card from ToDo to in Progress
    2. Check card for required tasks
    3. Complete task and tick off list
    4. Once all tasks completed move card to be reviewed section
    5. once reviewed move to complete and close issue

##### See screenshots for reference:

1. [Glo-Board-1](https://camo.githubusercontent.com/f492ce38de7bfa60d50ff496ed3dafc9705b4ebf/68747470733a2f2f6170702e6769746b72616b656e2e636f6d2f6170692f676c6f2f626f617264732f3563333330653838666566333839303030666534333033342f6174746163686d656e74732f356334396331383739323638326630303066323263626437)
2. [Glo-Board-2](https://camo.githubusercontent.com/fd6a1d8690c757d16da890a7a3e87e0901b53036/68747470733a2f2f6170702e6769746b72616b656e2e636f6d2f6170692f676c6f2f626f617264732f3563333330653838666566333839303030666534333033342f6174746163686d656e74732f356334396331383739323638326630303066323263626461)
3. [Glo-Board-3](https://camo.githubusercontent.com/ecd591dbc4fcf0f0474875351d47781d5d3bd265/68747470733a2f2f6170702e6769746b72616b656e2e636f6d2f6170692f676c6f2f626f617264732f3563333330653838666566333839303030666534333033342f6174746163686d656e74732f356334396331383739323638326630303066323263626464)
4. [Glo-Board-4](https://camo.githubusercontent.com/73cd00bf1eea1877c75d94f150382b2f609aeba0/68747470733a2f2f6170702e6769746b72616b656e2e636f6d2f6170692f676c6f2f626f617264732f3563333330653838666566333839303030666534333033342f6174746163686d656e74732f356334396331383739323638326630303066323263626434)

## Features

### Desktop/Tablet View

#### Home
- The home section features a transparent navbar with heading title to the left and section nav links to right.
- It also features an intoduction paragraph with links to different blockchain platforms.
- Selectors are located below the paragraph and allow you to filter the different data points.
- Once a selection is made it filters the charts as per selection.
- You can reset the filters by clicking the reset all button.

#### User/Category
- This sections has a row of 3 charts
    1. piechart with platfrom legend to filter the different platforms data.
    2. barchart showing the different categories data.
    3. piechart with legend to filter the platform data.

#### DApps Users
- This section has a rowchart showing the different dapps and allows you to filter the different data points.

#### Daily User Transactions
- This section features a scatterplot chart showing the amount of user tranactions per dapp and is filtered when selecting a
a filter from the selectors in the home section.

#### DApps Tranactions
- This section features a stacked barchart showing the daily and weekly transactions by dapp name and is filter by the selectors
in the home section or by clicking the bar sections on the chart.

#### Footer
- The footer section features a reset all button for the filters and nav items to navigate the sections.

### Mobile View
- When viewing on mobile the charts are positioned on top of each other to help the responsive behavior of the site.
- It also features a hamburger dropdown menu in the navbar, once clicked a dropdown menu appears containing the nav list items.

- All views feature a back to top button for ease of navigation.
- The button fades in and out as you scroll the page once clicked it returns you to home section using jquery script for smooth scrolling effect.


### Features Left to Implement
- Add a loader to the dashboard to display while page loads.
- Add more unit tests to get better code coverage.

## Technologies Used

For this project the following Technologies were used:
- [HTML5](https://en.wikipedia.org/wiki/HTML5)
    - The project uses **HTML5** to structure the content in line with modern semantic html5.

- [CSS3](https://en.wikipedia.org/wiki/Cascading_Style_Sheets#CSS_3)
    - The project uses **CSS3** to style the html content.

- [FontAwesome](https://fontawesome.com/)
    - The project uses **FontAwesome** to add icons for chart symbols.

- [Javascript](https://www.javascript.com/)
    - The project uses **Javascript** to add interactive content to dashboard.

- [Bootstrap 4](https://getbootstrap.com/)
    - The project uses **Bootstrap** to layout the html content and make it responsive.

- [Bootswatch](https://bootswatch.com/sandstone/)
    - The project uses **Bootswatch Theme** to add fonts and color the theme chosen was sandstone.

- [D3.js](https://d3js.org/)
    - The project uses **D3.js** for manipulating documents and rendering charts.

- [Crossfilter](https://github.com/crossfilter/crossfilter)
    - The project uses **Crossfilter** for manipulating and filtering the data.

- [Dc.js](https://dc-js.github.io/dc.js/)
    - The project uses **Dc.js** as a charting library with native crossfilter support and usesd3 to render charts.

- [Queue](https://github.com/d3/d3-queue)
    - The project uses **Queue** as a little helper for asynchronous JavaScript.

- [Jasmine](https://jasmine.github.io/index.html)
    - The project uses **Jasmine.js** for unit testing.

- [Vs Code](https://code.visualstudio.com/)
    - The project used **Vs Code** as the IDE of choice.

- [Mockflow](https://mockflow.com/)
    - The project used **Mockflow** for creating the mock-ups.

- [Git Github](https://github.com/)
    - The project used **Git Github** for source control management.

- [Git Kraken/Glo Boards](https://www.gitkraken.com/)
    - The project used **Git Kraken/Glo Boards** for project and task management.

- [JQuery](https://jquery.com)
    - The project uses **JQuery** to control scrolling and toggle features.

## Testing

In this section, you need to convince the assessor that you have conducted enough testing to legitimately believe that the site works well. Essentially, in this part you will want to go over all of your user stories from the UX section and ensure that they all work as intended, with the project providing an easy and straightforward way for the users to achieve their goals.

Whenever it is feasible, prefer to automate your tests, and if you've done so, provide a brief explanation of your approach, link to the test file(s) and explain how to run them.

For any scenarios that have not been automated, test the user stories manually and provide as much detail as is relevant. A particularly useful form for describing your testing process is via scenarios, such as:

1. Contact form:
    1. Go to the "Contact Us" page
    2. Try to submit the empty form and verify that an error message about the required fields appears
    3. Try to submit the form with an invalid email address and verify that a relevant error message appears
    4. Try to submit the form with all inputs valid and verify that a success message appears.

In addition, you should mention in this section how your project looks and works on different browsers and screen sizes.

You should also mention in this section any interesting bugs or problems you discovered during your testing, even if you haven't addressed them yet.

If this section grows too long, you may want to split it off into a separate file and link to it from here.

## Deployment

This section should describe the process you went through to deploy the project to a hosting platform (e.g. GitHub Pages or Heroku).

In particular, you should provide all details of the differences between the deployed version and the development version, if any, including:
- Different values for environment variables (Heroku Config Vars)?
- Different configuration files?
- Separate git branch?

In addition, if it is not obvious, you should also describe how to run your code locally.


## Credits

### Content
- The text for section Y was copied from the [Wikipedia article Z](https://en.wikipedia.org/wiki/Z)

### Media
- The photos used in this site were obtained from ...

### Acknowledgements

- I received inspiration for this project from X