# skeleton-help

> Este repositorio es un complemento del sistema de ayuda creado en [SDras-Helper](https://github.com/Gonzalo2310/SDras-Helper)

## Configuración de la construcción

``` bash
# instalar dependencias
npm install

# crea el proyecto para desarrollo en localhost:8080
npm run dev

# crea el proyecto para produccion y minificacion
npm run build

```

Para una explicación detallada de cómo funcionan las cosas, consulte la [guía](http://vuejs-templates.github.io/webpack/) y los [documentos para vue-loader](http://vuejs.github.io/vue-loader).

Las modificaciones o mejoras del sistema de soporte no deben aplicarse aquí sino en el repositorio original.

Este proyecto es un visualizador de ayudas creados con [SDras-Helper](https://github.com/Gonzalo2310/SDras-Helper)
El resultado es un componente Vue y aqui se entrega un scaffolding con un ejemplo integrado.

El resultado de [SDras-Helper](https://github.com/Gonzalo2310/SDras-Helper) es una carpeta con el componente integrado y un conjunto de archivos que forman la ayuda.

La carpeta es el nombre de proyecto en cuestion y para adaptarlo solo se deben seguir los siguientes pasos:
* Copiar la carpeta del proyecto de ayuda a src/components/ 
* Cambiar la siguiente linea de src/App.vue `import helper from './components/Example/helper'` por `import nombreproyecto from './components/nombreproyecto/helper'`

Y sencillamente ya tendra adaptado la ayuda creada con el programa anteriormente citado.



`Creado por @Gonzalo2310`