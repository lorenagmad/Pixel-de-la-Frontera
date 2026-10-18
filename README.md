# Píxel de la Frontera · Operación Feria

Juego de plataformas educativo para repasar los **temas 1, 2 y 3** de la asignatura: información digital, sistemas de numeración, profundidad de color, peso de las imágenes, resolución, modelos de color, formatos, imágenes vectoriales, remuestreo, histograma, imagen publicitaria, colores corporativos, derechos de imagen y proporciones.

Eres el becario de la agencia **Píxel de la Frontera** y tienes que preparar todo el material de la **Feria de Jerez**: cartel, web, redes sociales, abanicos, farolillos y cartelería de calle. Recorre las plantas de la agencia, habla con el equipo, usa las máquinas y resuelve los retos.

## Cómo jugar

- **Ordenador:** flechas ← → (o A/D) para moverte, espacio o ↑ para saltar, E o Intro para hablar y usar objetos.
- **Móvil:** botones en pantalla. Mejor en horizontal.
- El signo **!** indica dónde hay una tarea pendiente. El botón **Tareas** muestra lo que te falta y **Chuleta** tiene las fórmulas.

## Guardar la partida y cambiar de dispositivo

- El progreso se guarda **en el navegador del dispositivo** en el que juegas. En otro ordenador o móvil, o en modo incógnito, empezarás de cero.
- Para seguir en otro dispositivo: **Menú › Llevarme la partida** descarga un archivo. En el otro dispositivo, pulsa **Cargar partida** en la pantalla de inicio y elige ese archivo.
- **Menú › Guardar y salir** guarda y vuelve a la pantalla de inicio.

## Entrega del registro de actividad

Al empezar, el juego pide tu nombre y tu correo de la UCA. Tus acciones se guardan en formato **xAPI** para que el profesorado analice el aprendizaje.

- Al terminar el juego aparece el botón **Descargar registro (xAPI)**. También está en **Menú › Registro de actividad**.
- Entrega el archivo a tu profesor/a por correo o en la tarea del Campus Virtual.
- El archivo de **«Llevarme la partida»** también sirve como entrega: incluye el registro completo.
- Tus datos identificativos no se publicarán. Si los resultados se difunden, se usará solo un código anónimo (PF-…).

## Para el profesorado

- **Panel de análisis:** el archivo `panel-profesorado-pixel-frontera.html` (se distribuye aparte) analiza los registros de la clase en tu navegador, sin subir nada a internet.
- **Envío automático a un LRS (opcional):** en `index.html`, busca el bloque `const XAPI={endpoint:'',auth:'',base:...}` y rellena `endpoint` (la dirección del LRS, terminada en `/`) y `auth` (`'Basic ' + btoa('clave:secreto')`). Usa unas credenciales **solo de escritura**, porque quedan visibles en el código de la página.

## Publicar en GitHub Pages

1. Sube a la raíz del repositorio los archivos `index.html`, `README.md` y `.nojekyll`.
2. En **Settings › Pages**, elige **Deploy from a branch**, rama **main** y carpeta **/ (root)**.
3. Espera uno o dos minutos (pestaña **Actions**) y abre `https://TU-USUARIO.github.io/NOMBRE-DEL-REPOSITORIO/`.

## Créditos

- Diseño didáctico y gráficos: profesorado de la asignatura (Universidad de Cádiz). Personajes y escenarios generados con ludo.ai y editados con Affinity.
- Programación del juego: generada con la ayuda de Claude (Anthropic).
