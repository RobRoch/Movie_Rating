
# TODO 

27.04.2017
https://movie-ranking.herokuapp.com/

- changed my learning technique, trying to comment everything i do, so i can be able to visualize data placement. (or at least try)

- modal (DEAD)
I guess i'm not able to do this // I made it with ng2-bootstrap using ViewChild, ModalDirective and ModalModule. Sadly my modal didn't have bootstrap style.
It's something with ng2-bootstrap working with bootstrap 3 and is not used to bootstrap4? Maybe gonna come back later with more knownledge. Removing modal -> doing input instead.

- rating :id
Big issue! Downloading all rating 5 times and then filtering to get values.
After input again! Gonna try BehaviorSubject.

- input vote- 
Poor styling with number type.
Maybe change it later.

- searchbar
It's working fine, choose to use search button with it.

- asceding/descending
It's working. Works like this (normal -> asc -> desc -> asc -> desc -> etc.)

- http instead of hardcoded db
After few days it's working. Observables made this hard for me ;)

- error input vote
Only when null i get error. When other numbers than 1-5, it's doing nothing.


# MovieRating

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 1.0.0.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive/pipe/service/class/module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory. Use the `-prod` flag for a production build.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via [Protractor](http://www.protractortest.org/).
Before running the tests make sure you are serving the app via `ng serve`.

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI README](https://github.com/angular/angular-cli/blob/master/README.md).
