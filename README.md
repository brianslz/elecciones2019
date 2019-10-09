# Angular5

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 1.7.3.

#Installation steps
1.Clone both repository

2.in Frontend run below command

npm install and yarn install

3.In backend run below command

composer install

php artisan key:generate

php artisan migrate --seed

php artisan passport:install

4.After you run passprt:install command you get 2 keys

take second key and set it in frontend/enviroments/environment.ts and frontend/enviroments/environment.prod.ts and set backend url ex: http://localhost:8000

5.in fronetend run ng serve and in backend run php artisan serve



## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory. Use the `-prod` flag for a production build.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via [Protractor](http://www.protractortest.org/).

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI README](https://github.com/angular/angular-cli/blob/master/README.md).
