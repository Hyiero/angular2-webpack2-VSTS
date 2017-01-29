# Angular 2 - Webpack 2 - Visual Studio Team Service Seed

## This repository contains a seed project for a Angular 2 and webpack 2 stack project. Can get up and running in minutes. And is setup to successfully build to Visual Studio Team Services

## Commands:
1. **npm start** - This is for local development. It will bundle the app and turn on the webpack-dev-server and also enable hot module replacement
   to allow for continuous development without having to worry to refresh the browser
2. **npm run test:dev** - This is for local testing. It will compile the app and run the unit test as well as watch any changes that might take place to the unit test
   if changes are made it will recompile and re-run the test
3. **npm run test-coverage** - This is for prod and single test running to produce front end unit testing coverage.
4. **npm run build** - This is for prod builds. It will bundle the app and vendors js files and run all the goods on them and then pump them out to the dist
   folder
5. **npm run docs** - This will sweep project and parse out the .ts files in order to generate the documentation. Afterwards we will serve that documentation to the
   browser at localhost:8080.