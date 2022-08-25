# angular-tour-of-heroes
Angular example of a simple application using core concepts: components, service, routes.

Some info about how to use Angular:

Create the project:
ng new name-of-the-project


Generate components:
ng generate component component-name-to-be-generated

Para receber propriedades configuradas na tag html do componente:
  import { Component, OnInit, Input } from '@angular/core';

@Input() hero?: Hero; # hero é a propriedade


Use component in another component:
<name-of-the-component [hero]="selectedHero"></name-of-the-component>


Generate service:
ng generate service hero


Add navigation and create routes:
ng generate module app-routing --flat --module=app


Inject service:
Usar a DI no construtor
