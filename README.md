# 0109_lsw14c_react_testing

This module builds upon the topic of client-side testing by extending it into the realm of React.

## Project Description

The objectives of this module are the following:

- To write tests for a React application using Jest and Enzyme. These two libraries are commonly used in production for testing React components and applications.
- To practice reading over and understanding code which you did not write, but that you do need to test.

For this exercise, you're given a complete React application. Your job is to:

1. Go through and inspect **_all_** of the different pieces of the code.
2. Write tests for **_all_** of the components in the `./src/components` directory.
3. Write these tests in the correspondingly-named files in the `./src/__tests__` directory.
4. Modify the test files to avoid duplication of the enzyme configuration code.

You'll be using [Jest](https://facebook.github.io/jest/docs/en/expect.html) and [Enzyme](http://airbnb.io/enzyme/) in order to test React components.

## Initialization and Setup

You can run the complete application by installing Node modules with the `yarn` command, and then running `yarn start`.

Run `yarn test` in order to run the test suite. Of course, this isn't going to actually test anything yet, since you haven't written the tests!

## Stretch Goals

Add additional test files `calculate.test.js` and `operate.test.js` in the `tests` directory to test the files in the `./src/logic` folder. The files in this directory aren't React components, so for testing them you'll actually just be using Jest without Enzyme.
