# cypress-cucumber-docker

Integrated with:

- [x] https://github.com/badeball/cypress-cucumber-preprocessor
- [x] https://github.com/bahmutov/cypress-esbuild-preprocessor
- [x] https://www.npmjs.com/package/multiple-cucumber-html-reporter
- [x] https://github.com/cucumber/json-formatter
- [x] https://github.com/Shelex/cypress-allure-plugin

(+ bundlers: https://github.com/badeball/cypress-cucumber-preprocessor/tree/master/examples)

- ## 💻 Pre-requisites

1. Node JS
2. Optional: Java 8 for Allure Reporter
3. Optional: Json-formatter for Native Reporter option(depends on your OS: https://github.com/cucumber/json-formatter)

## 🚀 Install the project

Install project dependencies with: npm install or npm i

## Run the demo:

1. Standard Execution: npm run cypress:execution

2. Allure Report: 
   1. npm run cypress:execution-allure
   2. npm run allure:report
   3. allure open

## Run jenkins test on mac
Install the latest LTS version: brew install jenkins-lts
Start the Jenkins service: brew services start jenkins-lts and open http://localhost:8080
Restart the Jenkins service: brew services restart jenkins-lts
Update the Jenkins version: brew upgrade jenkins-lts