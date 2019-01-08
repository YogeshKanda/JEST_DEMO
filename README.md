## Getting Started:

This guide is regarding setting up for API automation framework using jest-supertest:
```
Jest is the framework which provide test runner, configurations, assertions etc
supertest is the tool which make the request to API and fetch the response. 
```
## Install all required modules
```
npm install or npm i //This will install all required modules as specified in "package.json" file
```
## Environments to run the test against:
```
Mock env : npm run test-mock
```
```
Test env : npm run test-dev
```

## Run a specific file or pattern
```
npm run test-dev file_name/file_name_pattern
```

## Run specific test or tests of a particular pattern
```
npm run test-dev -- -t test_name/pattern
```

## Run tests in docker
```
docker-compose up
```