# Angular2RxJs

The purpose of the project is to create an RXJS data source using the library Faker.js.

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 1.2.0.

## Faker.js

Generates 'massive amounts of fake data in the browser' and can be found here https://github.com/marak/Faker.js

To install...

npm install faker --save-dev

npm install @types/faker --save-dev

Then in the files that are required.


import * as faker from 'faker';
and type 'faker.' to see all the juicy options.


## Server scaffolding

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.


## Where does the data come from?

The data can come from the API or you can configure the application to fake the data, FAKE DATA IS DEFAULT!

#To get the data from the API  
Go to the directory 'server' 
run NPM INSTALL
run NODE INDEX

In the app.component file, change '.initialiseUsers(true, 50)' to read '.initialiseUsers()'
