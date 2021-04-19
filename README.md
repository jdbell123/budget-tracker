# Budget Tracker
![GitHub code size in bytes](https://img.shields.io/github/languages/code-size/jdbell123/budget-tracker)
 [![GitHub issues](https://img.shields.io/github/issues/jdbell123/budget-tracker)](https://github.com/jdbell123/budget-tracker/issues)
 [![GitHub stars](https://img.shields.io/github/stars/jdbell123/budget-tracker)](https://github.com/jdbell123/budget-tracker/stargazers)
## Table of Contents

* [Reason](#reason)
* [Learnt](#learnt)
* [Take-Aways](#Take-Aways)
* [Installation](#installation)
* [Usage](#usage)
* [Credits](#credits)
* [License](#license)
* [Links](#links)

***

## Reason

The reason for this assignment this week was to learn about deploying an app that could work offline and sync to the database when it comes back online. We were given the following User Story and Acceptance Criteria:

```
AS AN avid traveller
I WANT to be able to track my withdrawals and deposits with or without a data/internet connection
SO THAT my account balance is accurate when I am traveling
```

```
GIVEN a user is on Budget App without an internet connection
WHEN the user inputs a withdrawal or deposit
THEN that will be shown on the page, and added to their transaction history when their connection is back online.
```

---

## Learnt

Working on this project I have learnt about the following things:

    1 - Expanded knowledge on MongoDB
    2 - Expanded knowledge on doing routing (offline)
    3 - Gained knowledge on using indexedDB
    5 - Gained knowledge on using manifests & service workers
    6 - Expanded knowledge on JavaScript
    7 - Learnt how to deploy Apps to Heroku that use MongoDB

---

## Take-Aways

Think through the changes you are making and always test straight away before moving onto the next part of the code. Commit more often is something I need to work on.

---

## Installation

To install the required libraires for this application use the following command to install the application locally:

```
npm i
```

There is a deployed version of this application. Just navigate to the URL to see the application.

* [Links](#links)

---

## Usage 

To use this application type the following command into your terminal/command prompt (after installing it):

```
npm start
```

Once the local server is running navigate to http://localhost:3000/ to see the app in action.

This is a demo of the finished application:

![App Demo](./assets/images/App_Demo.gif "App Demo")

---

## Credits

As always thanks to my BFF Google for being there in my hours of need. Also, to my fellow class mates for the study groups and hints/tips I received on this project. Last but not least a thank you to the tutor and TAs for the guidance and support they gave on this project. 

---

## License


Licensed under the [MIT](./LICENSE) license.


---

## Links

[GitHub Repo](https://github.com/jdbell123/budget-tracker)

[Deployed App](https://vast-lowlands-73957.herokuapp.com/)