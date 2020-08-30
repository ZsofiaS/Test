# Vulnerability scan tech test

## Technologies and design

The app has been built with React.
The scan results page consists of the following main components:
* summary: contains general information about the scan
* user: contains user information & notifications
* scan details: list of vulnerabilities and details

## To run locally

* In your terminal, type
```
git clone https://github.com/ZsofiaS/Vulnerability-Scan.git
```
* navigate to the project directory 'Vulnerability-Scan', then type
```
npm install
```
to install all required node modules.
* Then type
```
npm start
```
* Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

## To run the tests

* In your terminal, type
```
npm test
```
This launches the test runner in the interactive watch mode.

## Specification

With a .json payload provided, which contains user & scan information, mock up an interface that consumes this data and displays it in the browser.
