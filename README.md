# Moto Market

## This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 17.3.0

---

[![Quality Gate Status](https://sonarcloud.io/api/project_badges/measure?project=Malethik_MotoMarket_Front&metric=alert_status)](https://sonarcloud.io/summary/new_code?id=Malethik_MotoMarket_Front)
[![Coverage](https://sonarcloud.io/api/project_badges/measure?project=Malethik_MotoMarket_Front&metric=coverage)](https://sonarcloud.io/summary/new_code?id=Malethik_MotoMarket_Front)
[![Technical Debt](https://sonarcloud.io/api/project_badges/measure?project=Malethik_MotoMarket_Front&metric=sqale_index)](https://sonarcloud.io/summary/new_code?id=Malethik_MotoMarket_Front)
[![Vulnerabilities](https://sonarcloud.io/api/project_badges/measure?project=Malethik_MotoMarket_Front&metric=vulnerabilities)](https://sonarcloud.io/summary/new_code?id=Malethik_MotoMarket_Front)
[![Reliability Rating](https://sonarcloud.io/api/project_badges/measure?project=Malethik_MotoMarket_Front&metric=reliability_rating)](https://sonarcloud.io/summary/new_code?id=Malethik_MotoMarket_Front)

---

## Descripción de la aplicación

La aplicación se ejecuta con Angular 17 al front con el framework NestJS en el backend.
Es un SPA que se ejecuta en una base de datos MySQL.
La aplicación cuenta con dos partes principales main y header.
El header mostrará solo la opción del menú y el logotipo.
Main renderizará toda la aplicación.
El core tiene el servicio y las guard para la correcta ejecución de la aplicación.Ademas en el core esta la directiva que permite al menu un cierre automatico y el servicio payment realizado a traves de STRIPE.
Sigo los patrones del repositorio y todos los métodos que traen datos del servidor se almacenan en el servicio de repositorio.
El servicio de estado es quien permite que la aplicación sea reactiva con el cambio de usuario.
Agregué una protección como la protección del propietario que permite que solo el usuario que publica el elemento pueda eliminarlo.
La aplicación utiliza JwT para iniciar sesión y autenticar. Auth0 es la futura implementacion.
La aplicación es un comercio electrónico social como eBay o Wallapop en el que el usuario puede vender todos los artículos relacionados con el mundo de la moto.
Esta implementada una pasarela de pago siendo de pruba la unica carta aceptada es `4242 4242 4242 4242`

---

Application run with Angular 17 in front with a Nest framework on backend.
Is an SPA running on a MySQL database.
The application in composite with a main and header.
Header will render the menu option and the logo only.
Main will render all the application.
The core have the service and guard for the correct run of the application.
I follow the repository patterns and all the method that bring data from server are stored in repo service.
The state service is who permits that application will be reactive with user change.
I added some guard like owner guard that permits only to user that publish the item can remove it. In the core there's too the directive for autoclosing the menu and payment service that use STRIPE.
The application use JwT for the log in and auth. Auth0 is the future feature.
The application is a social e-commerce like ebay or wallapop the user can sell all items related on the world of the motorbike.
There's implement of a payment section in details but for testing the only card accepted is `4242 4242 4242 4242`.

### Empezar la aplicación

En la consola ejecuta `ng serve` y navigar a `http://localhost:4200/`.

---

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`.

### Test

Esta cubierta por el 95% de coverage de testing
`npm run test:prod` por empezar los test y ver el coverage.

---

Is covered with a 95% of coverage with testing.

`npm run test:prod` for run test and see coverage.
