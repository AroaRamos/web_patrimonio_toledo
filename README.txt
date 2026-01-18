PROYECTO: DESCUBRE NUESTRO PATRIMONIO - TOLEDO
==============================================

ALUMNA: Aroa Ramos
CURSO: 2º Desarrollo de Aplicaciones Web (DAW)
MÓDULO: Diseño de Interfaces Web
IES: Juan Bosco - Alcázar de San Juan
FECHA: Enero 2025

---------------------------------------------------

LUGAR ELEGIDO: Toledo (Castilla-La Mancha)

He elegido Toledo porque es una ciudad histórica muy importante y declarada 
Patrimonio de la Humanidad. Se conoce como "la ciudad de las tres culturas" 
porque convivieron cristianos, judíos y musulmanes durante siglos.

---------------------------------------------------

PUNTOS DE INTERÉS:

1. LA CATEDRAL PRIMADA
   Es una catedral gótica impresionante construida entre 1226 y 1493. Tiene obras 
   de arte de El Greco, Goya y Caravaggio. Es una de las catedrales más importantes 
   de Europa.

2. EL ALCÁZAR DE TOLEDO
   Es una fortaleza que está en lo alto de la ciudad. Tiene origen romano y ahora 
   es el Museo del Ejército. Se reconoce fácil por sus cuatro torres en las esquinas.

3. MIRADOR DEL VALLE
   Es el mejor sitio para ver Toledo desde fuera. Desde ahí se ve toda la ciudad 
   rodeada por el río Tajo. 

---------------------------------------------------

FUENTES Y LICENCIAS DE RECURSOS:

IMÁGENES:
Todas las imágenes las he descargado de:
- Pexels (https://www.pexels.com/) - Licencia gratuita
- Pixabay (https://pixabay.com/) - Licencia CC0 (dominio público)

VÍDEOS:
Los tres vídeos los he descargado de:
- Pexels Videos (https://www.pexels.com/videos/)
- Pixabay Videos (https://pixabay.com/videos/)

Son vídeos con licencia gratuita.

AUDIOS:
Los audios los he generado con la herramienta online TTSMaker (https://ttsmaker.com/es)
He escrito los textos siguiendo la información de cada punto y luego 
los he convertido a audio con voz en español.

TEXTOS DESCRIPTIVOS:
Los textos descriptivos de cada punto los he generado con ayuda de Gemini (IA de Google).
Le he pedido que me escribiera descripciones de 120-200 palabras sobre cada punto 
y luego los he revisado para que fueran coherentes con el proyecto.

SUBTÍTULOS:
Los archivos .vtt de subtítulos los he creado con el Bloc de notas.
He escrito las frases y puesto las marcas de tiempo manualmente.

---------------------------------------------------

ATRIBUTOS HTML5 UTILIZADOS:

He usado estos atributos en las etiquetas de vídeo y audio:

ETIQUETA <VIDEO>:
- controls: Para que salgan los botones de play, pausa y volumen
- muted: Para que el vídeo empiece sin sonido (si no los navegadores lo bloquean)
- poster: Para poner una imagen antes de darle al play
- width: Para controlar el tamaño del vídeo

ETIQUETA <AUDIO>:
- controls: Para que aparezcan los controles del reproductor

ETIQUETA <TRACK>:
- kind="subtitles": Para indicar que son subtítulos
- src: La ruta donde está el archivo .vtt
- srclang="es": Para decir que están en español
- label="Español": El nombre que aparece en el botón de subtítulos
- default: Para que se activen automáticamente

ETIQUETA <SOURCE>:
- src: La ruta del archivo de vídeo o audio
- type: El tipo de archivo (video/mp4 o audio/mpeg)

---------------------------------------------------

ESTRUCTURA DEL PROYECTO:

toledo-patrimonio/
├── index.html              (Página principal)
├── catedral.html           (Página de la Catedral)
├── alcazar.html            (Página del Alcázar)
├── mirador.html            (Página del Mirador)
├── README.txt              (Este archivo)
│
├── css/
│   └── styles.css          (Los estilos de la web)
│
├── img/                    (Todas las imágenes)
│
└── media/
    ├── video/              (Los 3 vídeos en MP4)
    ├── audio/              (Los 3 audios en MP3)
    └── subtitulos/         (Los 3 archivos .vtt)