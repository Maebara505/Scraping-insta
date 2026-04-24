# Scraping-insta Arquitectura
Code de insta para obtener del usuario sus seguidores y sus post con 3 comentarios

Tras el análisis de los datos extraídos del perfil de usuario, se concluyen los siguientes puntos técnicos y funcionales:

  - Efectividad del Scraping Híbrido: Se logró la extracción exitosa de metadatos de nivel 1 (seguidores: 395, seguidos: 315) mediante el uso de requests y la persistencia de sesión. Esto confirma que el acceso a la API interna de Instagram sigue siendo el método más eficiente para datos numéricos de perfil sin activar bloqueos por exceso de peticiones.
  - Resiliencia ante Contenido Dinámico: El uso de Playwright permitió superar la renderización asíncrona de JavaScript de la plataforma. Se extrajeron con éxito 10 publicaciones, incluyendo el conteo de interacciones (Likes) incluso cuando estos están parametrizados como "Ocultos" en la interfaz estándar, demostrando que el bot puede leer datos que el usuario común no visualiza a simple vista.
  - Filtrado de Ruido y Análisis de Sentimiento Social: El algoritmo de limpieza basado en Expresiones Regulares filtró efectivamente elementos de la interfaz. Los resultados muestran una interacción social activa en los posts analizados, recuperando comentarios de usuarios como justferc, cristina.frey y soy_xgabo. Esto valida que el procesamiento de lenguaje natural aplicado fue capaz de distinguir entre la descripción del autor y el feedback genuino de la comunidad, cumpliendo con los objetivos de minería de datos web propuestos.


Los datos de luis no muestran a un estudiante de sistemas aburrido metido en un sótano. Muestran a un estratega social, alguien que sabe trabajar duro, pero que prioriza la salud mental, los viajes y la familia.
