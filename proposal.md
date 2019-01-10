## Overview

ExTrac is a convenient expense tracking app that provides users an user-friendly interface to record and track their daily expenses at any moment of the day. In order to complete a single expense record, user will be asked to enter an amount in dollar, expense description, date and category. Once submitted, the expense list on the side bar will display the most-recent ten expenses along with detailed information for each expense item. 

The app will also show dynamic data chart/graph that summarizes a user's expenses over a customized period of time (daily, monthly or all). The app will also automatically update the chart/graph whenever the user inputs a new expense or make any new changes to their previous expense items. The interface will also provide user a daily weather inforamtion and a stock market info with 3 main stock indices.

This app is inspired by a mobile app, Pocket Expense, (http://www.appxy.com/pocket-expense/). I am envisioning a design with black and blue as theme colors and simpilicity and user-friendliness as  missions.

### Functionality

* Users can enter dollar amount, write description and select date and category.
* Users can add and delete customized category type(s)
* Users can add, edit and delete expense items 
* If a user prefer daily/monthly expense summary, there are two to three option buttons for them to display preferable data on the chart/graph.
* Users can set a daily/monthly budget. The web will display a warning message when a user excesses that budget.

### Wireframes

![Wireframe](./screenshots/wireframe.png)

The app will consist of a single page with 2 input box, 2 dropdown menus, 1 Add Expense button, 1 expense sidebar, 1 expense data chart/graph, 1 board for weather info and stock market info and the links to the Github repository and developer LinkedIn.

Upon pressing Add Expense the expense sidebar starts adding the new expense item and the data chart will also start re-calculating and displaying new data.

Clicking the stock market info icon will redirect the user to Yahoo Finance page; whereas clicking the weather icon will redirect the user to a general weather website.

##### Technologies employed

* Vanilla JavaScript for calculation logic.
* HTML5 Canvas for rendering.
* Webpack to bundle various scripts into a single source.
* React.js for basic page structure and functionality.

##### Main files
* `extrac.js` main structure of the canvas and center of calculation logic.
* `expense.js` responsible for rendering the input boxes and dropdown menus.
* `user.js` receives input and outputs.
* `expense_sidebar.jsx` fetches expenses and displays them in a `<ul></ul>`.

### MVPs
- [x] Basic visuals and an interactive interface.
- [x] User can enter, edit and delete an expense item
- [x] Render dynamic expense sidebar
- [x] Render dynanmic data chart/graph
- [x] API for live-time weather info
- [x] API for live-time stock market info

### Development timeline

##### Jan 9, Wed, day 1:
- [x] Finish brainstorming, concept, and proposal.

##### Jan 10, Thur, day 2:
- [x] Finish basic project skeleton and essentials.

##### Jan 11, Fri, day 3:
- [x] Briefly review web app using canvas from the instructional curriculum.
- [x] Complete basic page skeleton and functionality.
- [x] Know how to manipulate localStorage
- [x] Review data visulization 

##### Jan 12, Sat, day 4:
- [x] Complete user input design and rendering.
- [x] Ideally move onto date chart

##### Jan 13, Sun, day 5:
- [x] Complete data chart rendering and add styles to it
- [x] Complete expense sidebar rendering and functionality.


##### Jan 14, Mon, day 6:
- [x] Review API and start working to fetch weather info
- [x] Review API and start working to fetch stock market info


##### Jan 15, Tue, day 7:
- [x] Finish styling page.
- [x] Complete MVPs and iron out project.
- [x] Implement bonus features.

##### Jan 16, Wed, day 8:


### Bonus features
