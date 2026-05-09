🎨 Generador de Paleta de Colores y Círculo Cromático

Una aplicación web interactiva de una sola página (Single Page Application) diseñada para ayudar a diseñadores, artistas y desarrolladores a encontrar la combinación de colores perfecta. La herramienta ofrece tanto un círculo cromático con reglas de armonía clásicas como un extractor de paletas a partir de imágenes.

✨ Características Principales

1. Círculo Cromático Interactivo

Selección Visual: Haz clic en cualquier parte del círculo cromático para seleccionar un color base.

Reglas de Armonía: Aplica automáticamente 10 reglas de teoría del color diferentes:

Color Único

Colores Primarios y Secundarios

Colores Análogos

Matiz y Tonalidad

Monocromáticos

La Díada (Complementarios)

Tríada y Tétrada

División Complementaria

Formatos de Color: Genera instantáneamente los códigos de color en HEX, RGB (ideal para diseño web) y CMYK (ideal para impresión).

Copiar al Portapapeles: Haz clic en cualquier muestra de color generada para copiar su código HEX directamente a tu portapapeles.

2. Extractor de Paleta desde Imagen

Carga de Imágenes: Sube cualquier imagen desde tu dispositivo de forma local (los datos no se envían a ningún servidor, todo se procesa en tu navegador).

Análisis de Color: Extrae automáticamente el Color Dominante y una paleta complementaria representativa de la imagen.

Copiar Fácilmente: Al igual que en el círculo cromático, puedes hacer clic en los colores extraídos para copiar sus códigos HEX.

🛠️ Tecnologías Utilizadas

Este proyecto está construido en un único archivo HTML para facilitar su portabilidad y uso:

HTML5: Estructura semántica de la aplicación.

Tailwind CSS (vía CDN): Para un diseño moderno, limpio y completamente responsivo.

Vanilla JavaScript: Toda la lógica de conversión de color (HSL a RGB/CMYK) y manipulación del DOM sin frameworks pesados.

Color Thief: Una librería de JavaScript utilizada para extraer la paleta de colores de las imágenes.

Google Fonts: Utiliza la fuente Bebas Neue (como alternativa a Bebas Kai) para darle un toque estilizado a la interfaz.

🚀 Cómo Usarlo

Al ser un proyecto de un solo archivo, no requiere instalación de dependencias ni servidores locales complejos.

Descarga el archivo index.html (o el nombre que le hayas asignado).

Haz doble clic sobre el archivo para abrirlo en cualquier navegador web moderno (Chrome, Firefox, Edge, Safari).

Para usar el Círculo Cromático: Selecciona una regla de armonía en el menú desplegable y haz clic en el círculo para ver los resultados.

Para usar el Extractor de Imágenes: Haz clic en "Subir Imagen", selecciona un archivo de tu computadora y luego presiona el botón "Extraer Colores".

📝 Notas de Desarrollo

El cálculo de CMYK es una aproximación matemática estándar desde RGB. Para trabajos de imprenta de alta precisión, se recomienda verificar los perfiles de color en software especializado (como Adobe Illustrator o Photoshop).

Las imágenes cargadas se dibujan temporalmente en la memoria del navegador para el análisis de píxeles, lo que garantiza la privacidad del usuario.