# Proyecto HTML & CSS (2º Trimestre)

## [:link: EDevAWeb](https://leo0756.github.io/)

### Importante ⚠

- Probado en el navegador Brave con la resolución 1920x1080.

### Advertencia ⚠
- Este proyecto contiene varios apartados en cuanto a contenido, por lo cual es fácil perderse al tratar de leer el código.

---

### Descripción 📋

**Temática** 🌐

Página web de una empresa/agencia de desarrollo app y web.

**Tecnologías utilizadas** ⚙

1. HTML
1. CSS

**Recursos utilizados** ⛰

- [Imagénes de contenido](https://github.com/Leo0756/leo0756.github.io/tree/main/img).
- [Fuente de Texto](https://fonts.google.com/specimen/Raleway).

**Derechos de Autor**
- [Referencia, Diseño, Contenido, etc](https://appdesign.dev/). → Esta página web fue tomada como referencia, así como las imágenes y todo el contenido le pertenecen a la misma.

**Requisitos** ✔

- [✔] Elementos maquetados adecuadamente.
- [✔] Al menos 6 páginas.
- [✔] Hoja de estilo común.
- [✔] Sección Inicio.
- [✔] Lista.
- [✔] Galería (Con CSS GRID).
- [✔] Formulario
- [✔] Texto.
- [✔] Archivos validados.
- [✔] Archivos ordenados.
- [✔] Etiquetas meta.

---

### Explicaciones :key:

**Propiedades CSS no vistas en clase**

`Position: sticky;` → El elemento se mantiene en la posición de su contenedor hasta que alcanza el borde superior de la pantalla, entonces se mantendrá fijo en el borde superior.

`transform: scale(<Tamaño a escalar>);` → Define una transformación que modifica el tamaño de un elemento en el plano 2D. A nivel visual podriamos decir que amplia el elemento con el que es usado.

`animation: <nombre-del-keyframe> <Segundos> <Veces que debe repetirse>;` → Permite la animación de elementos HTML sin usar JavaScript o Flash!

```
    /*
    Definimos lo que queremos que haga nuestra animación.
    */

    @keyframes example {
        0%   {background-color:red; left:0px; top:0px;}
        25%  {background-color:yellow; left:200px; top:0px;}
        50%  {background-color:blue; left:200px; top:200px;}
        75%  {background-color:green; left:0px; top:200px;}
        100% {background-color:red; left:0px; top:0px;}
    }

    /*

    Aplicacimos el CSS Animation sobre la etiqueta|capa|selector al cual le queramos dar la animación.
    */
    div {
    width: 100px;
    height: 100px;
    background-color: red;
    position: relative;
    animation: example 4s infinite;
    }
```

Para mas información consultar en: [Usando animaciones CSS](https://developer.mozilla.org/es/docs/Web/CSS/CSS_Animations/Using_CSS_animations)

`display: flex;` → Es una propiedad resumida que indica la capacidad de un elemento flexible para alterar sus dimensiones y llenar el espacio disponible. Los elementos flexibles pueden ser estirados para utilizar el espacio disponible proporcional a su factor de crecimiento flexible o su factor de contracción flexible para evitar desbordamiento.

- `justify-content: center;` → Centra los elementos "hijos" horizontalmente.
- `align-items: center;` → Centra los elementos "hijos" verticalmente.
- `flex-wrap:` → Especifica si los elementos "hijos" son obligados a permanecer en una misma línea o pueden fluir en varias líneas.
- `flex-direction: column;` → Especifica cómo colocar los objetos flexibles en el contenedor flexible definiendo el eje principal y la dirección (normal o al revés).

Para mas información consultar en: [Flex CSS](https://developer.mozilla.org/es/docs/Web/CSS/flex)

