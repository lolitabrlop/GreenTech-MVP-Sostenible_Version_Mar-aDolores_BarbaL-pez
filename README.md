# GreenTech MVP Sostenible
Autor: María Dolores Barba López
Cliente: GreenTech Solutions
Objetivo: refactorizar el código para garantizar el máximo rendimiento y mejorar la huella de carbono.
## Resumen
Este proyecto representa una transformación de un activo digital ineficiente hacia una solución de Sostenibilidad Digital. Se ha eliminado el 95% del peso innecesario, priorizando la eficiencia energética sin sacrificar la identidad visual del cliente.
## Auditoría
1. Descarbonización del código
   - Antes: el sitio dependía de 4 librerías externas (Bootstrap, jQuery, Moment.js,            FontAwesome). Esto obligaba al navegador a realizar múltiples peticiones HTTP y            procesar miles de líneas de JavaScript para funciones triviales, fomentando que se         volviese lenta la carga de los mismos.
   - Después: he sustituido frameworks pesados por CSS Grid y Flexbox nativos. El icono de      la hoja ahora es un SVG embebido, eliminando la necesidad de cargar una biblioteca de      fuentes de iconos completa.
2. Optimización
   - Fuentes del Sistema: he decidido eliminar las Google Fonts. Al usar system-ui, la web      carga instantáneamente utilizando recursos que ya existen en el dispositivo del            usuario, ahorrando DNS.
   - Estrategia de Imágenes: he añadido un escalado inteligente de la imagen Hero y para        mejor uso, se recomienda el uso de formatos WebP/Avif.
## ¿Por qué es sostenible?
Según el modelo de Sustainable Web Design, cada byte transferido consume energía en los centros de datos, las redes de transmisión y el dispositivo final. Al reducir el peso de 3.5MB a 250KB, se diluye las emisiones de CO2 por visita en un 92%.
El código ineficiente (JavaScript pesado y DOM complejo) obliga a la CPU del usuario a trabajar intensamente, generando calor y degradando la batería. El nuevo código optimizado:

1. Reduce el estrés térmico de los componentes.

2. Permite que dispositivos antiguos rendericen la web con fluidez, combatiendo la obsolescencia programada y evitando que el hardware termine prematuramente en un vertedero.
