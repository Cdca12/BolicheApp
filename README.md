<p align="center">
  <a href="https://github.com/jasmine/jasmine">
    <img src="/src/assets/Jasmine + Karma Logo.png" width="600" title="Angular con Jasmine y Karma">
  </a>
</p>

[![license](https://img.shields.io/badge/license-MIT-red)](LICENSE.md)

# BolicheApp

Este proyecto fue generado con [Angular CLI](https://github.com/angular/angular-cli) versión 11.0.2.

## Instalación

Ejecuta `npm install` en la carpeta del proyecto.

## Development server

Ejecuta `ng serve` para ejecutarlo en un servidor de desarrollo. Navega a `http://localhost:4200/`. La aplicación se recargará automáticamente si modificas cualquier archivo del proyecto. 

## Code scaffolding

### Generar un nuevo componente

Ejecuta `ng generate component component-name` para generar un nuevo componente. También puedes usar `ng generate directive|pipe|service|class|guard|interface|enum|module`.

### Añadir una clase con pruebas unitarias

Ejecuta `ng generate class folder-name\className` para añadir una nueva clase con pruebas unitarias con Jasmine. Esto te generará una carpeta con 2 archivos .ts.

## Build

Ejecuta `ng build` para hacer un build al proyecto. Los artefactos en build se guardarán en la carpeta `dist/`. Usa la bandera `--prod` para realizar un build de tipo productivo.

## Ejecutar pruebas unitarias (Unit tests)

Ejecuta `ng test` para ejecutar las pruebas unitarias vía [Karma](https://karma-runner.github.io).

## Ejecutar pruebas extremo-a-extremo (End-to-end test)

Ejecuta `ng e2e` para ejecutar las pruebas de extremo-a-extremo via [Protractor](http://www.protractortest.org/).

## Ayuda

Para obtener más ayuda en el uso de Angular CLI usa `ng help` o consulta la página de [Angular CLI Overview and Command Reference](https://angular.io/cli).

## Troubleshooting

### Habilitar la ejecución de scripts para Powershell
En algunas ocasiones nos podemos encontrar con que no podemos ejecutar los comandos con `ng` debido a que en el sistema está deshabilitada la ejecución de scripts. 

Para corregir esto, tenemos que abrir el Windows PowerShell como administrador y ejecutamos el comando `Get-ExecutionPolicy`, nos tendría que devolver «Unrestricted» o lo que es lo mismo «Restringido». Para cambiar esta configuración basta con ejecutar el comando `Set-ExecutionPolicy Unrestricted`.

En ese momento ya se pueden ejecutar los scripts sin problemas.
