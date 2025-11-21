Proyecto de Dashboard Profesional Unicamente con CSS Y HTML.

En este proyecto pongo a prueba mis conocimientos aprendidos de CSS y HTML para la producción de una Pagina totalmente Accesible, Funcional y Estetica. cumpliendo los siguientes Objetivos/Requisitos: 

Objetivo: Diseñar una página de "Dashboard/Aplicación" moderna y 100% responsiva.

Requisitos de Estructura y Layout (Grid/Flexbox/Semántica)
Layout Principal: Usa CSS Grid en el <body> para definir tres áreas: Sidebar (250px fijo), Header (ancho completo) y Main Content (el resto).

Sidebar: Debe ser position: sticky o fixed (tú eliges el mejor método) y tener un menú interno alineado con Flexbox.

Tarjetas de Datos: Dentro del Main Content, crea una sección con 4 tarjetas de estadísticas. Técnica Obligatoria: Usa CSS Grid con minmax() y auto-fit para que estas 4 tarjetas se ajusten automáticamente al ancho disponible sin usar media queries.

Tipografía: El título principal de la página debe usar la función clamp() para su font-size.

Semántica y ARIA: Todo elemento interactivo o de sección principal debe llevar la etiqueta HTML semántica correcta (<aside>, <nav>, <main>) y atributos role/aria-label según sea necesario.

Requisitos de Interacción y Estilo Avanzado
Elevación: Todas las tarjetas deben tener el efecto de elevación suave (transform: translateY y box-shadow) al hacer hover.

Focus: Todos los enlaces y botones deben tener un estado de :focus visible que reemplace el outline del navegador.

Variables: Todo el esquema de color (primario, secundario, fondo) debe ser manejado por Variables CSS definidas en :root.
