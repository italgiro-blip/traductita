Traductor Español ⇄ Italiano B1 (Web App)
Aplicación web interactiva y moderna diseñada para la traducción y el aprendizaje de nivel intermedio (B1) entre el español y el italiano. Cuenta con una interfaz elegante y minimalista desarrollada con Tailwind CSS, utilizando APIs nativas del navegador para ofrecer funciones avanzadas de voz y almacenamiento local.

🚀 Características Principales
Traducción Bidireccional: Permite traducir fácilmente de Español a Italiano y viceversa (ES ⇄ IT).

Traducción Instantánea sin API Key: Utiliza el servicio público de Google Translate mediante peticiones asíncronas (fetch), permitiendo traducciones rápidas sin necesidad de registrar claves de API.

Sistema de Caché Local (localStorage): Guarda las traducciones recientes en el almacenamiento del navegador para recuperarlas al instante sin gastar recursos de red.

Pronunciación Interactiva (Text-to-Speech):

Reproducción de audio con voces nativas del navegador (window.speechSynthesis).

Control de velocidad ajustable (0.7x, 0.8x, 0.9x y 1.0x).

Opción de detener la reproducción en cualquier momento.

Dictado por Voz (Speech Recognition): Permite dictar texto mediante el micrófono del dispositivo (window.SpeechRecognition / webkitSpeechRecognition).

Guía Gramatical B1 y Falsos Amigos: Muestra automáticamente consejos gramaticales contextuales y advertencias sobre falsos amigos (falsi amici) específicos del par de idiomas.

Historial Dinámico: Muestra las últimas consultas realizadas de forma rápida y limpia.

Diseño Responsivo: Interfaz moderna, limpia y adaptada a dispositivos móviles y de escritorio gracias a Tailwind CSS.

🛠️ Tecnologías Utilizadas
HTML5 (Estructura semántica)

Tailwind CSS (vía CDN para estilos rápidos y responsivos)

JavaScript Moderno (ES6+) (Lógica de la aplicación, promesas async/await, APIs de síntesis y reconocimiento de voz)

📦 Instrucciones de Uso
Guarda el código completo de la aplicación en un archivo con extensión .html (por ejemplo, traductores.html).

Abre el archivo directamente en cualquier navegador web moderno compatible (se recomienda fuertemente Google Chrome o Microsoft Edge para el correcto funcionamiento del reconocimiento de voz y las síntesis de audio nativas).

Selecciona la dirección de la traducción deseada en el menú desplegable (Spagnolo ➔ Italiano o Italiano ➔ Spagnolo).

Escribe el texto o utiliza el botón de Detto vocale (Dictado por voz) para ingresar tu frase.

Haz clic en Traduci e Analizza para obtener la traducción junto con su análisis gramatical y opciones de audio.
