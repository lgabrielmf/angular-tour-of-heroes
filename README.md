# AngularTourOfHeroes

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 14.1.3.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The application will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via a platform of your choice. To use this command, you need to first add a package that implements end-to-end testing capabilities.

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI Overview and Command Reference](https://angular.io/cli) page.

## To initiate a new Angular Project:
Create the project:
ng new name-of-the-project

## Add navigation and create routes:
ng generate module app-routing --flat --module=app

## Adding Angular Material:
ng add @angular/material

## Generate components:
ng generate component component-name-to-be-generated

## To receive properties configured on html tag of a custom component:
import { Component, OnInit, Input } from '@angular/core';

@Input() hero?: Hero; # hero é a propriedade

## Use component in another component:
<name-of-the-component [hero]="selectedHero"></name-of-the-component>

## Generate service:
ng generate service hero

## Inject service:
Use DI in component class constructor

## To use only Bootstrap grid system with Angular material:
If you just need to use the bootstrap grid, you can add in your package.json dependencies: "bootstrap": "4.3.1" and npm i then in your styles.scss add @import 'bootstrap/dist/css/bootstrap-grid.min.css'; upside the angular material theme import and there you go, you imported only the grid style without all other stuffs and material theme is still the same.
