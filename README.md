# Portafolio de Jaume

Muestra tus mejores proyectos acompañados de una paleta de colores azules vibrantes. Además añade opiniones o reviews de tu trabajo para humanizarte.

## Tabla de Contenidos

- [General](#general)
  - [El Reto](#el-reto)
  - [Captura](#captura)
  - [Enlaces](#enlaces)
- [Mi Proceso](#mi-proceso)
  - [Tecnologías](#tecnologías)
  - [Lo que aprendí](#lo-que-aprendí)
  - [Desarrollo continuo](#desarrollo-continuo)
  - [Recursos](#recursos)
- [Autor](#autor)
- [Agradecimientos](#agradecimientos)

## General

### El Reto

- Estilo libre. Lleva el diseño al código utilizando tu framework favorito, o con HTML y CSS, no hay ninguna limitación.

- Accesibilidad como prioridad.

- Sube tu código a GitHub.

- Publica tu resultado con github pages.

- Mándalo a revisión desde tu [perfil](https://leonidasesteban.com/estudiante).

### Captura

<img width="400px"  src="https://github.com/no-te-rindas/imagenes/blob/main/Readmes/portafolio-jaume/jaume-desktop.png?raw=true" />

<img width="200px" src="https://github.com/no-te-rindas/imagenes/blob/main/Readmes/portafolio-jaume/jaume-mobile.png?raw=true" />

### Enlaces

- [Repositorio](https://github.com/heraldofortuna/portafolio-jaume)
- [Sitio en vivo](https://heraldofortuna.github.io/portafolio-jaume/)

## Mi Proceso

### Tecnologías

- HTML5
- CSS3
- Flexbox
- Responsive Design

### Lo que aprendí

Aprendí distintas cosas en este taller como:

- A usar la propiedad "sticky" para el header, además de darle un efecto interesante usando "backdrop-filter":

```css
.header {
  position: sticky;
  top: 0;
  z-index: 1;
  backdrop-filter: blur(10px);
}
```

- Por más pequeño que sea un archivo css, siempre es importante separar en componentes la estructura:

```css
.title {
  background-color: var(--purple);
  color: var(--white);
  text-decoration: none;
  font: var(--headline5);
  align-self: flex-start;
  padding-block: 4px;
  padding-inline: 8px;
  box-shadow: -4px 4px 0 var(--white);
}
```

- Lo que es el "aria-label" y su función.

```html
<nav class="menu" aria-label="main-navigation">
  <ul>
    <li><a class="is-active" href="#main">Hola</a></li>
    <li><a href="#project">Proyectos</a></li>
    <li><a href="#contact">Hablemos</a></li>
  </ul>
</nav>
```

- Vincular label con su input siempre como buena práctica, además de como colocar este último embebido en el primero:

```html
<label for="form-name"
  >Nombre Completo<input
    required
    name="name"
    id="form-name"
    type="text"
    placeholder="Juan"
/></label>
```

## Desarrollo continuo

Lo siguiente que haré será aprender a usar el Figma desde el punto de vista de un desarrollador Frontend, además de mejorar mis skills en flexbox y grid llevando algun curso con Leonidas.

## Recursos

Todos los recursos usados en este proyecto son de la autoría de LeonidasEsteban.com

## Autor

- LeonidasEsteban.com - [LeonidasEsteban.com](https://leonidasesteban.com/)
- Twitter - [@heraldofortuna](https://twitter.com/heraldofortuna)

## Agradecimientos

A Leonidas, por darlo todo en cada clase. Siento que no se guardó nada en este taller. Un genio del frontend.
