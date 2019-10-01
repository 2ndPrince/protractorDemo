# Protractor Frontend E2E testing
Protractor needs two files to run, a spec file and a configuration file.

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

## Create config and spec file
conf.js
todo-spec.js

## Launch the protractor and browser will pop up
```
protractor conf.js
```
