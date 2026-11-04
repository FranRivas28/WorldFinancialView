# World Financial View

Prototipo de **Atlas de Mercados**: un dashboard con un globo 3D que muestra 18 países: EE. UU., Canadá, México, Brasil, Argentina, Reino Unido, Alemania, Francia, Italia, España, Rusia, Arabia Saudita, Emiratos Árabes Unidos, Sudáfrica, India, China, Japón y Australia. Cada país tiene una barra con la métrica elegida (bolsa en el último mes, inflación, tasa de interés o crecimiento del PIB) y una ficha con pestañas de Economía, Política, Comercio y Finanzas que muestran los mismos campos para todos; lo que falta aparece como "sin dato". La vista "Comparar países" permite elegir países, tema, orden y ver gráficos o tabla.

Es un sitio estático: un solo `index.html` que carga d3 y topojson desde cdnjs. Para publicarlo en Vercel, importá este repositorio sin configurar nada; no hace falta un paso de build.

Los datos son una foto fija al 3 de noviembre de 2026 y no se actualizan solos. Las fuentes figuran en el pie de la página.
