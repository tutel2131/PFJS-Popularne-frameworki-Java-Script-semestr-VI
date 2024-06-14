# Filmix

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 16.1.4.

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


----------------------------------------------------------
## Opis projektu

Projekt to (niedokończona) aplikacja internetowa z bazą filmów, seriali.

Jest zbudowana za pomocą frameworka Angular.

Zostały w niej użyte użyte narzędzia takie jak:
- generatory komponentów - (komenda ng generate component component-name) dla każdej ważniejszej części zostały stworzone osobne komponenty np. landing-page, films, registration, news.
Stworzone zostały także modele np. news.model.ts
- routing - plik app-routing.module.ts, np:  { path: 'strona-główna', component: LandingPageComponent }, pozwala na przekierowanie na stronę główną i załadowanie komponentu LandingPageComponent
- serwisy - współpraca z REST API, pobieranie danych z bazy danych w formie JSON, np serwis films.service.ts pobiera listę filmów z bazy danych (https://filmix-80ef5-default-rtdb.firebaseio.com/g.json)
lub auth.service.ts pozwala na rejestrację i logowanie użytkowników

Angular dzięki tworzeniu osobnych komponentów pozwolił na uporządkowanie kodu, podzielenia go na 'części', co zwiększyło czytelność projektu.
