# DApps Data Dashboard

Second Milestone project for code institute full stack developer course interactive frontend development.
It is a single page responsive application visualizing data of decentralised applications statistics.

### The Project Brief:

#### CREATE A DATA DASHBOARD

* Build a data dashboard that visualizes a dataset of your choice
* Your data can be stored locally (e.g., in a js file) or sourced from an API
* Visualise your data using D3.js and dc.js


## UX

This App was developed for users looking for statistics on decentralised applications(DApps) that run on blockchain platforms.
The platforms I picked were Ethereum(ETH), EOSIO(EOS) and Tron(TRX), I selected the top 15 DApps on each platform
and built a dataset of the platforms, names, category, amount of users over 24hr period and the amount daily and weekly transactions(txs) of each DApp.

### Style:
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
    [Glo-Board-1](https://camo.githubusercontent.com/f492ce38de7bfa60d50ff496ed3dafc9705b4ebf/68747470733a2f2f6170702e6769746b72616b656e2e636f6d2f6170692f676c6f2f626f617264732f3563333330653838666566333839303030666534333033342f6174746163686d656e74732f356334396331383739323638326630303066323263626437)


## Features

In this section, you should go over the different parts of your project, and describe each in a sentence or so.
 
### Existing Features
- Feature 1 - allows users X to achieve Y, by having them fill out Z
- ...

For some/all of your features, you may choose to reference the specific project files that implement them, although this is entirely optional.

In addition, you may also use this section to discuss plans for additional features to be implemented in the future:

### Features Left to Implement
- Another feature idea

## Technologies Used

In this section, you should mention all of the languages, frameworks, libraries, and any other tools that you have used to construct this project. For each, provide its name, a link to its official site and a short sentence of why it was used.

- [JQuery](https://jquery.com)
    - The project uses **JQuery** to simplify DOM manipulation.


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