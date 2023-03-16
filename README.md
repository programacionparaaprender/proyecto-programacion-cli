# proyecto-programacion-cli
Proyecto de prueba de un cli

### cursos
https://www.udemy.com/course/npm-librerias-node-con-js-typescript-angular-y-otras-herramientas/

# paquetes npm
npm install chalk@4.1.2 inquirer figlet shelljs@0.8.3

npm install figlet@1.2.1
npm install inquirer@6.2.2

### repositorios

https://github.com/SBoudrias/Inquirer.js/
https://github.com/shelljs/shelljs
https://github.com/patorjk/figlet.js/
http://patorjk.com/software/taag/#p=display&f=Graffiti&t=Type%20Something%20
https://github.com/chalk/chalk


# Creador de ficheros mediante CLI
En este proyecto vamos a poder crear un fichero introduciendo el nombre y la extensión que deseamos.

## Instrucciones
Para un correcto uso, hay que seguir estas instrucciones.

### Instalación

* GLOBAL
```
npm install -g cli-file-creator
```
* LOCAL
```
npm install cli-file-creator
```

### Para usarlo
* Global
Ejecutamos **cli-file-creator**
* Local
Añadir en el package.json
```
"scripts": {
    "cli-file-creator": "./node_modules/.bin/cli-file-creator"
},
```
Ejecutamos con
```
npm run cli-file-creator
```
