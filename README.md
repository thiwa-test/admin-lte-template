# AdminLteTemplate

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 8.3.29.
This project was used Admin LTE V3.1

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## Code scaffolding
1. Create new project
	1. ng new admin-lte-template
2. Install admin lte 3 module
	1. npm install admin-lte@^3.1 --save
3. Verify admin lte integration
	1. check weather moudle is added under /node_modules/admin-lte
	2. check on package.json, under dependencies that admin-lte included
4. Include scripts and style links needed for page
	1. Open angular.json file
	2. Under projects>architect>build>styles add style link needed for page
	3. Under projects>architect>build>scripts add javascript link needed for page
5. Now update /src/app/app.component.html with page you selected
	1. Note that static links need to added in header section (specific only to page)
6. Test run!

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory. Use the `--prod` flag for a production build.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via [Protractor](http://www.protractortest.org/).

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI README](https://github.com/angular/angular-cli/blob/master/README.md).
