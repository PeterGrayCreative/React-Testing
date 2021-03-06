# React Testing

This module builds upon the topic of client-side testing by extending it into the realm of React. 

## Project Description

The objectives of this module are the following: 
- To get you guys writing tests for a React application using Jest and Enzyme, two libraries which are commonly used in production for testing React components and applications. 
- To give you guys some practice reading over and understanding code that you didn't write but that you need to test.

For this exercise, you're given a complete React application. Your job is to go through and inspect all of the different pieces of the code, and write tests for all of the components in the `./src/components` directory in the correspondingly-named files in the `./src/tests` directory.

You'll be using [Jest](https://facebook.github.io/jest/docs/en/expect.html) and [Enzyme](http://airbnb.io/enzyme/) in order to test React components. 

## Initialization and Setup

You can run the complete application by `yarn install`ing and then running `yarn start`. 

Run `yarn test` in order to run the test suite. Of course, this isn't going to actually test anything yet, since you haven't written the tests!

## Stretch Goals

Add additional test files `logic.test.js` and `operate.test.js` in the `tests` directory to test the files in the `./src/logic` folder. The files in this directory aren't React components, so for testing them you'll actually just be using Jest without Enzyme.  