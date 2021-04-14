# My json resume

## Setup

1. Clonamos el repositorio

```sh
git clone git@github.com:chudix/my-json-resume.git
```

2. Instalamos dependencias

```sh
npm install
```

## Utilizacion

El cv se encuentra escrito en formato json en el archivo [resume.json](./resume.json).

Se utiliza la libreria [resume-cli](https://jsonresume.org/) para parsearlo y transformarlo a pdf; junto
con el theme paper.

Para generar el cv se debe ejecutar:

```sh
npx resume export <nombre_pdf>.pdf --theme paper
```


