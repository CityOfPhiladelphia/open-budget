# Open Budget

This tool is an open source project built by the [City of Philadelphia’s Office of Innovation and Technology](http://www.phila.gov/data/), based on a project by [OpenData.ch](https://github.com/tpreusse/open-budget), the Swiss division of the [Open Knowledge Foundation](http://okfn.org/).

## Setup
First, clone the repository and from within project directory install dependencies via:
```
$ npm install
```
Make your changes and view the application in its development at `/src`.

_Note: to preview data visualization, browser preview requires running a local webserver_

## Build
Optimize the application by running:
```
$ npm run build
```
This will update the files in the `/dist` directory. To push that directory to the `gh-pages` branch of the repo, use:
```
$ git subtree push --prefix dist origin gh-pages
```

## Dependencies
- Underscore.js
- d3.js
- Foundation 5
- Bootstrap 3
- jQuery

## Data Format
<!--* See the [open-budget-data-transformer](https://github.com/CityOfPhiladelphia/open-budget-data-transformer) repo -->
* See the parent repo's [Data Format](https://github.com/tpreusse/open-budget/wiki/Data-Format) documentation
