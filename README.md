# World Financial View

Prototipo de **Atlas de Mercados**: un dashboard con un globo 3D que muestra seis países (EE. UU., Brasil, China, Alemania, Japón y Argentina). Cada país tiene una barra con la métrica elegida (bolsa en el último mes, inflación, tasa de interés o crecimiento del PIB) y una ficha con el gráfico de la bolsa, las acciones principales, los datos macro y noticias.

Es un sitio estático: un solo `index.html` que carga d3 y topojson desde cdnjs. Para publicarlo en Vercel, importá este repositorio sin configurar nada; no hace falta un paso de build.

Los datos son una foto fija al 3 de noviembre de 2026 y no se actualizan solos. Las fuentes figuran en el pie de la página.
