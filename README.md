# api-testing

# Automation Test API with SuperTest

This is the repository for automation of API, developed to work with SuperTest.

## Table of Contents

1. [Goal](#goal)
2. [Project Structure](#project-structure)
3. [Tests](#tests)
4. [Initial Setup](#initial-setup)
5. [Run Tests](#run-tests)

## Goal

The goal of this repository is to be easy to understand focused on developing automated tests for API, using [SuperTest](https://www.npmjs.com/package/supertest), a tool developed to provide a high-level abstraction for testing HTTP, while still allowing you to drop down to the lower-level API provided by superagent.

## Project Structure

```
|--- test
|--- utils
|--- .env
|--- .env.sample
|--- jest_html_reporters.html
|--- jest.config.json
|--- jsconfig.json
|--- package-lock.json
|--- package.json
```

## Tests

The tests were written using the JavaScript language.

## Run tests

### Initial Setup

1. Requires node. To install, execute `npm install node` or download [Node](https://nodejs.org/en/download/)
2. Run the command `npm install` to install dependencies
3. Requires the EBAC Demo Store Admin to execute. Git clone the [EBAC Demo Store Admin](https://github.com/EBAC-QE/ebac-demo-store-admin.git) for your local machine, then start following the steps in the README.
4. Requires the EBAC Demo Store Server to execute. Git clone the [EBAC Demo Store Server](https://github.com/EBAC-QE/ebac-demo-store-server.git) for your local machine, then start following the steps in the README.

### Run Tests

- Run one of the commands below to run the tests.
  Examples:
- To run all tests, execute `npm run test`
- To run only the Health Check tests, execute `npm run test:healthCheck`
- To run only the E2E tests, execute `npm run test:e2e`
<p>