# Informe del Trabajo Práctico 1: Proyecto "Turismo Jujuy"
Materia: Programación de Servicios Web

Link de la página funcionando: https://pyswtp1.netlify.app

1. ¿De qué trata el proyecto?
Armamos una página web para promocionar el turismo en la provincia de Jujuy. El objetivo era hacer un sitio funcional, rápido y fácil de navegar, utilizando únicamente HTML y CSS puro, sin depender de librerías externas pesadas ni frameworks como Bootstrap.

2. ¿Cómo nos dividimos el trabajo?
Para organizarnos mejor y no pisarnos el código entre nosotros, decidimos dividir el proyecto en distintas páginas y componentes. Cada integrante del grupo se hizo cargo de armar el HTML y el archivo CSS de su sección:

Valentín Farfán (Estructura Base y Home): Me encargué de armar el esqueleto principal de la página. Hice el index.html (la página de inicio), y armé la barra de navegación (Header/NavBar) y el pie de página (Footer) para que todos los chicos pudieran usar esa misma estructura en sus páginas y que el sitio se vea unificado.

Lucas Zerpa (Destinos): Desarrolló la página destinos.html con sus propios estilos CSS, donde se muestran los lugares turísticos para visitar y los precios.

Uriel Zambrano (Agencias): Se encargó de maquetar agencias.html y su CSS, armando la sección donde se muestra la información de las agencias de viaje.

Gustavo Yevara (Blog): Armó la página blog.html con su respectivo CSS, diseñando la parte de noticias y artículos de la provincia.

Elías Tolaba (Contacto): Creó la sección contacto.html y su CSS, dándole forma al formulario para que los usuarios puedan dejar sus consultas y a la info de contacto.

3. ¿Cómo trabajamos en equipo (Herramientas)?
Como éramos varios tocando código al mismo tiempo, usamos herramientas de trabajo reales para no hacer un lío con los archivos:

GitHub (Control de versiones): Usamos Git y armamos un repositorio en GitHub. Para trabajar ordenados, teníamos la rama principal (main) y cada uno iba subiendo su progreso desde su computadora a su propia rama. Cuando la página de cada uno estaba lista, la juntábamos en el main.

Netlify (Hosting): Para que la página no quede solo en nuestras compus y esté subida a internet, usamos Netlify. Lo conectamos directo a nuestro repositorio de GitHub. Lo bueno de esto es que cada vez que subíamos una corrección a la rama main, la página web se actualizaba sola automáticamente.

4. Decisiones de diseño

Separamos los estilos en varios archivos .css (por ejemplo, un css para el index, otro para destinos, otro para layout general) para que si alguien tenía que corregir un color en su página, no le rompiera el diseño al compañero.
