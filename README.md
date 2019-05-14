# The Perfect Lineup

## Instructions

In the initial commit to this project, you have been provided with files that contain a JavaScript module and some associated tests. Currently the `calculateTotalSalary` function is not implemented causing some tests to fail. Use what we have learned about reducing to write a solution to the problem of calculating the total salary of a lineup.

## Provided Files

**.babelrc** - this file allows mocha to read the code files written in ES6 syntax

**.eslintrc.js** - this file tells ESLint what our style rules are for our code so we will be prompted if we violate that style

**.gitignore** - this file sets the project up to ignore the node_modules folder when committing to git

**package.json** - this file sets up the Node project including all the dev dependencies

**lineup.js** - this file contains the functions for validating a fantasy baseball lineup

**tests.js** - this file contains tests for the functions in the `lineup` module

## Lineup Rules
1) The total salary of all players in a lineup may not exceed $45,000
2) Lineups may not contain more than 2 players from a single team
3) Lineups may not contain more than 3 players from a single game
4) Lineups must contain exactly 3 players with the position of 'OF' and must also contain exactly 1 player from each of the following positions: 'P', 'C', '1B', '2B', '3B', 'SS'

## Exercise Submission

You should fork this repository and submit your working changes in a pull request to your forked repo.

## Extra Credit

Currently the `getPositionCounts` function is not implemented and thus we are not checking that lineups follow the position rules. Begin by removing the 8 `.skip`s from the `tests.js` file. Then uncomment the position related code on lines 44 and 48 of the `lineup.js` file. This will cause the position related tests to fail. You can then write a solution to the `getPositionCounts` function that causes the tests to pass. Review the section on reduce in module 3 for further guidance, specifically the part about using reduce to build new objects.
