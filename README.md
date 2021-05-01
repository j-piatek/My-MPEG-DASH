# My-MPEG-DASH
Código correspondiente a la práctica de la asignatura Integración de Redes, Aplicaciones y Contenidos del Máster Universitario en Ingeniería de Telecomunicación. 

En esta práctica desarrollamos una aplicación web para proporcionar un servicio de streaming de vídeo básico. Para ello se creó un servidor que se encarga de organizar el acceso a los recursos a través del navegador y un cliente HTML que ofrece el entorno de visualización al usuario. Como última tarea se realizó un gráfico haciendo uso de la librería ChartJS para visualizar las métricas de la reproducción (bitrate y estado del buffer) y poder comprender el funcionamiento de DASH.

El servidor responde al cliente con los segmentos de un vídeo de prueba codificado en 3 calidades diferentes.

La práctica se divide en 4 partes.
  - Introducción a dash.js, en la que se visualiza un vídeo ofrecido por envivo a través del documento de presentación, o Media Presentation Document (MPD). (index_parte1.html)
  - Generación de vídeos para streaming y visualización en un cliente. (index_parte2.html)
  - Gestión de DRM con dash.js. (index_parte3.html)
  - Visualización de métricas (index_parte3.html)

