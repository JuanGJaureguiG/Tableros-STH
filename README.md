# Tableros de Control — UNIMINUTO Sede Tolima-Huila

Página de acceso a todos los tableros interactivos de la Sede. Cada tarjeta enlaza
al sitio publicado de un tablero (cada uno vive en su propio repositorio de GitHub
Pages).

## Cómo agregar un tablero nuevo

Abre `index.html` y busca el arreglo `DASHBOARDS` cerca del final del archivo.
Agrega un objeto con esta forma:

```js
{
  tag: 'Categoría corta',
  title: 'Nombre del tablero',
  desc: 'Una o dos frases describiendo qué muestra.',
  color: '#RRGGBB',       // color del acento superior de la tarjeta
  url: 'https://juangjaureguig.github.io/nombre-del-repo/'
}
```

No hace falta tocar nada más — la tarjeta se genera sola.

## Publicar en GitHub Pages

Igual que los demás tableros: sube `index.html` a un repositorio nuevo (por ejemplo
`tableros-uniminuto-tolima-huila`) y activa GitHub Pages en Settings → Pages,
rama `main`, carpeta `/ (root)`.

Ese repositorio puede convertirse en tu "página de inicio" — por ejemplo, compartes
un solo enlace (`https://juangjaureguig.github.io/tableros-uniminuto-tolima-huila/`)
y desde ahí cualquier persona navega a cada tablero individual.
