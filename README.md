# Getting Started with Create React App

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## What to do the first time

The first time you retrieve this code, you will need to install the react scripts to work properly. To do this, type:

`npm install react-scripts --save`

This is a one-time action for this project, which downloads and retrieves the necessary artifacts.

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

## Code Coverage

```
To generate the code coverage, launch `npm test -- --coverage` which produces a file that contains a breakdown of 

 PASS  src/App.test.js
  √ No moves when model created (3 ms)
  √ Properly renders 0 moves (55 ms)
  √ Access GUI (22 ms)
  √ First valid moves (3 ms)
  Separately define a new suite
    √ Test puzzle

---------------------|---------|----------|---------|---------|--------------------------------------
File                 | % Stmts | % Branch | % Funcs | % Lines | Uncovered Line #s
---------------------|---------|----------|---------|---------|--------------------------------------
All files            |   83.55 |    56.97 |      82 |   85.85 |
 src                 |   51.72 |    16.66 |      50 |   51.72 |
  App.js             |   82.35 |       50 |    62.5 |   82.35 | 57,59-60
  Layout.js          |     100 |      100 |     100 |     100 |
  index.js           |       0 |      100 |     100 |       0 | 7-17
  reportWebVitals.js |       0 |        0 |       0 |       0 | 1-8
 src/boundary        |      96 |    83.33 |     100 |     100 |
  Boundary.js        |      96 |    83.33 |     100 |     100 | 57-62
 src/controller      |      75 |       50 |      75 |   83.33 |
  Controller.js      |      75 |       50 |      75 |   83.33 | 28-30
 src/model           |   88.74 |    56.66 |      90 |   91.04 |
  Model.js           |   88.51 |    56.66 |      90 |   90.83 | 9-13,102,132-133,167,182,242-246,263
  Puzzle.js          |     100 |      100 |     100 |     100 |
  TestPuzzle.js      |     100 |      100 |     100 |     100 |
---------------------|---------|----------|---------|---------|--------------------------------------
Test Suites: 1 passed, 1 total
Tests:       5 passed, 5 total
Snapshots:   0 total
Time:        2.769 s, estimated 3 s
Ran all test suites.
```

If you don't see the above input, then set the environment variable "CI" to be true, something like `set CI=true`, then rerun the example.

