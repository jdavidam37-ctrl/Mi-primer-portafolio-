# Portafolio — Juan David Arenas

## ¿Por qué este diseño?

Pedí un estilo oscuro y moderno con acentos neón, y en lugar de aplicar un
solo color llamativo sobre un fondo negro genérico, tomé como inspiración
un editor de código (tipo VS Code / Tokyo Night): fondo azul muy oscuro
(`#0D1117`), tres acentos que imitan el resaltado de sintaxis —morado,
cian y naranja— y una tipografía monoespaciada (`JetBrains Mono`) para
títulos y navegación, combinada con `Inter` para el texto de lectura.

Elegí esta dirección porque el sitio es el portafolio de alguien que
estudia **Análisis y Desarrollo de Software**: tiene sentido que el
"empaque" visual hable el mismo idioma que el contenido. Por eso:

- La barra superior imita la barra de título de un editor (con los tres
  puntos de "cerrar / minimizar / maximizar").
- Los encabezados de sección están escritos como comentarios de código
  (`// sobre-mi.md`, `// proyectos/`).
- El encabezado principal simula una línea de terminal (`$ whoami`) con
  un cursor parpadeante.
- Cada proyecto tiene un borde lateral de color distinto (cian / naranja)
  para diferenciarlos visualmente sin usar tarjetas idénticas con sombra.

## Funcionalidades JavaScript agregadas

1. **Modo oscuro / claro**: un botón en la barra superior cambia entre
   los dos temas y recuerda la elección del usuario usando
   `localStorage`, así la preferencia persiste al recargar la página.
2. **Contador de visitas**: cada vez que se carga la página, el contador
   en el pie de página aumenta y guarda el valor en `localStorage`, para
   que muestre visitas reales acumuladas y no se reinicie en cada visita.
3. **Mensaje interactivo**: al hacer clic en el botón "Salúdame 👋" en la
   sección de contacto aparece un mensaje aleatorio, como pequeño gesto
   de bienvenida para quien visita el sitio.

## Contenido

Toda la información (nombre, especialidad, sobre mí y contacto) es real,
proporcionada por mí. Los dos proyectos (**Gestor de Tareas** y
**Sistema de Inventario**) son ejemplos típicos de un estudiante de ADSI
en formación, pensados para mostrar variedad de tecnologías (web con
JavaScript y localStorage, y una app de escritorio en Java con MySQL);
puedes reemplazarlos por proyectos reales a medida que los desarrolles.