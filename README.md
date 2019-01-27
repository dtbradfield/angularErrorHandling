I took the files for this app from the tutorial I am following

The purpose of this project was to debug using Augury.

I was able to fix everything on my own:

Initial problems: Add server button did not work. Also, the method that removed the last item of the array of newly added servers
was unable to remove the final item.

## Fixes: 

Fixed the server button. 'servers' was not forced to be an empty array, so I did it manually: servers = [];

Fixed the remove server function with an if else in the app component file. Easy peasy.

# MyFirstApp

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 6.0.0.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory. Use the `--prod` flag for a production build.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via [Protractor](http://www.protractortest.org/).

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI README](https://github.com/angular/angular-cli/blob/master/README.md).
"# angularErrorHandling"  git init git add README.md git commit -m "first commit" git remote add origin https://github.com/dtbradfield/angularErrorHandling.git git push -u origin master
"# angularErrorHandling" 
