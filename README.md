# Píxel de la Frontera · Operación Feria

Juego de plataformas educativo para repasar los **temas 1, 2 y 3** de la asignatura: información digital, sistemas de numeración, profundidad de color, peso de las imágenes, resolución, modelos de color, formatos, imágenes vectoriales, remuestreo, histograma, imagen publicitaria, colores corporativos, derechos de imagen y proporciones.

Eres el becario de la agencia **Píxel de la Frontera** y tienes que preparar todo el material de la **Feria de Jerez**: cartel, web, redes sociales, abanicos, farolillos y cartelería de calle. Recorre las plantas de la agencia, habla con el equipo, usa las máquinas y resuelve los retos.

## Cómo jugar

- **Ordenador:** flechas ← → (o A/D) para moverte, espacio o ↑ para saltar, E o Intro para hablar y usar objetos.
- **Móvil:** botones en pantalla. Mejor en horizontal.
- El signo **!** indica dónde hay una tarea pendiente. El botón **Tareas** muestra lo que te falta y **Chuleta** tiene las fórmulas.

## Mi partida: un solo archivo

- Al empezar, el juego pide tu nombre y tu correo de la UCA. Tu partida y tus acciones se guardan en el navegador.
- En **Menú › Mi partida** (y al terminar el juego o al pulsar **Guardar y salir**) descargas **un único archivo** que sirve para dos cosas:
  - **Entregarlo** a tu profesor/a, por correo o en la tarea del Campus Virtual.
  - **Seguir en otro ordenador o móvil**: en la pantalla de inicio pulsa **Cargar partida** y elige el archivo.
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
