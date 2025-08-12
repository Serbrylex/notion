---
title: Notas pedorras
---

how to start with this project

Tienes que tener instalado:

- git
- node

Comandos paso a paso:

Te vas en la consola al lugar donde quieres bajar el proyecto

```bat
git clone https://github.com/Serbrylex/notion.git

cd notion

# instala los paquetes
npm i

# hacer build y correr el proyecto en local
npx quartz build --serve

# sincronizar con el repo
npx quartz sync
```

How does it work? magic

Quartz pasa los archivos markdown que se encuentre en /content y los pasa a html, md se renderea casi siempre como html entonces es bastante facil hacerlo, de ahi todos los archivos estaticos los pasa a la carpeta /public y cuando se hace el sync primero se bajan cambios del repo, luego se mergean con tus cambios y luego se suben y todo esto lo gestiona automaticamente quartz.

Luego en github gracias a las github pages, toma lo que hay en /public y lo publica vea, easy peace.

Por ahora solo hay que crear archivos md en /content y ya we

Ejemplo de links
[Anal-isis](LOL/anal-isis.md)
