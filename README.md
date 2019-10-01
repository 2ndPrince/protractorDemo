# Protractor Frontend E2E testing

### End-to-End testing
Testing the flow of an application as per the design from start to finish

### Protractor
An end-to-end test framework for Angular and AngularJS applications
Runs on real browser and it is built on top of WebDriverJS

### Advantage of Protractor
It supports Angular-specific locator strategies, which allows testing Angular-specific elements without any setup effort.

It waits and sleeps do not need to be added to a test.

It can automatically execute the next step in the test, the moment the webpage finishes pending tasks. No waiting for your test and webpage to sync!

### How to run a test with protractor
Protractor needs two files to run, a spec file and a configuration file.
'''
protractor conf.js
'''
Output: The browser window opens, navigates to the todo list in the AngularJS page and closes on its own.

## Quizlet flashcard
https://quizlet.com/434573852/angularjs-packaging-and-testing-flash-cards/

## Install protractor globally
Install protractor if not installed (protractor --version)
```
npm install -g protractor
```
## Update webdriver-manager
```
webdriver-manager update
```
## Make sure webdriver-manager is up and running
```
webdriver-manager start
```
This will start up a Selenium Server and will output a bunch of info logs.
The Protractor test will send requests to this server to control a local browser.
You can see information about the status of the server at http://localhost:4444/wd/hub.

## Launch the protractor and browser will pop up
```
protractor conf.js
```
