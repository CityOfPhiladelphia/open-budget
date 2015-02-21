# Open Budget
A fork of [tpreusse/open-budget](https://github.com/tpreusse/open-budget)

## Setup
First, clone the repository, and then install dependencies via:
```
$ npm install
```
Make your changes and view the application in its development at `/src`.

## Build
Optimize the application by running:
```
$ npm run build
```
This will update the files in the `/dist` directory. To push that directory to the `gh-pages` branch of the repo, use:
```
$ git subtree push --prefix dist origin gh-pages
```

## Data Format
* See the [open-budget-data-transformer](https://github.com/CityOfPhiladelphia/open-budget-data-transformer) repo
* See the parent repo's [Data Format](https://github.com/tpreusse/open-budget/wiki/Data-Format) documentation