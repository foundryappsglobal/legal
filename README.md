# Legales — foundry.apps

Políticas de privacidad de las apps publicadas por foundry.apps.

## Este contenido es generado

Las páginas de cada app salen del template `foundry`, con `npm run legal:build`, que las
construye leyendo `src/config/app.ts` de la app. **No las edites acá:** el próximo
`legal:build` las sobreescribe y el cambio se pierde. Editá el config de la app y volvé a
generar.

La única excepción es `index.html`: desde la segunda app conviene editarlo a mano para que
liste todas, porque el generador de cada app sólo conoce la suya.

## Estructura

```
style.css              hoja de estilos compartida
index.html             listado de apps (editable a mano)
<app-slug>/
  privacy.html           inglés, canónica
  privacy.es.html        español
```

Nada de nombres con `_` adelante: GitHub Pages corre Jekyll y Jekyll ignora esos archivos,
así que la hoja de estilos no se serviría. `.nojekyll` desactiva ese procesamiento de todos
modos, por las dudas.

## Términos de uso

Las apps se rigen por el EULA estándar de Apple, que no se hospeda acá:
<https://www.apple.com/legal/internet-services/itunes/dev/stdeula/>
