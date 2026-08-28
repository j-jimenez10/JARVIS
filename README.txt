JARVIS FINAL — PWA

IMPORTANTE:
El archivo index.html es una web-app. Para instalarla como app en iPhone debe estar publicada mediante HTTPS.

PASOS:
1. Sube TODOS los archivos de esta carpeta a un repositorio de GitHub.
2. En GitHub: Settings > Pages > Deploy from a branch > main > /(root) > Save.
3. Espera a que GitHub publique la página.
4. Abre la dirección https://TUUSUARIO.github.io/NOMBRE-REPOSITORIO/ en Safari.
5. Compartir ↑ > Añadir a pantalla de inicio > Añadir.

FUNCIONAMIENTO:
- Sin API Key: incluye un modo local de demostración que responde a hora, fecha, saludos, identidad y agradecimientos.
- Con API Key: conecta con OpenAI GPT-4o.
- Voz: usa SpeechRecognition cuando el navegador lo permite.
- Voz de salida: usa SpeechSynthesis.
- Memoria: localStorage del dispositivo.

SEGURIDAD:
La versión es un prototipo personal. La API Key se guarda localmente y se utiliza desde el navegador. Para una aplicación pública hay que añadir un backend y no exponer la clave.
