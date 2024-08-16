![Logo de ColDisBot](https://github.com/bladealex9848/asesor-legal-anticorrupcion-colombiano/blob/main/assets/logo.jpg)

# Asesor Legal Anticorrupción Colombiano

## Descripción

El Asesor Legal Anticorrupción Colombiano es una herramienta de inteligencia artificial diseñada para proporcionar información precisa y actualizada sobre la legislación colombiana contra la corrupción. Basándose en la API de OpenAI, este asistente ofrece respuestas fundamentadas en leyes y normativas vigentes, incluyendo el Código Iberoamericano de Ética Judicial, el Plan Anticorrupción de la Rama Judicial, tipologías de corrupción y la Carta de Trato Digno en los despachos judiciales.

## Introducción

Con el Asesor Legal Anticorrupción Colombiano, podrás interactuar con una IA especializada, capaz de asistirte en diversos aspectos de la lucha contra la corrupción en Colombia. Ya sea que necesites información sobre procedimientos legales, delitos, sanciones, garantías procesales o responsabilidades de los sujetos involucrados, este asistente está listo para ayudarte. Para desarrollar esta aplicación se utilizaron:

- OpenAI API
- Streamlit

## ¿Cómo funciona?

1. El usuario introduce una pregunta o solicitud relacionada con la legislación anticorrupción colombiana.
2. La aplicación crea un hilo de conversación con OpenAI.
3. La pregunta se envía al asistente especializado de OpenAI.
4. El asistente procesa la solicitud y genera una respuesta basada en las leyes y normativas vigentes.
5. La respuesta se muestra al usuario en la interfaz de Streamlit.

## Funcionalidades

- **Respuestas fundamentadas**: Proporciona información basada en la legislación anticorrupción colombiana.
- **Especialización jurídica**: Enfocado exclusivamente en la lucha contra la corrupción en Colombia.
- **Interfaz amigable**: Diseñado con Streamlit para una experiencia de usuario intuitiva.
- **Persistencia de conversación**: Mantiene el contexto de la consulta para una interacción más natural.

## Instalación

1. Asegúrate de tener Python 3.8 o superior instalado en tu máquina.
2. Clona este repositorio: `git clone https://github.com/bladealex9848/asesor-legal-anticorrupcion-colombiano.git`
3. Navega al directorio del proyecto: `cd asesor-legal-anticorrupcion-colombiano`
4. Instala las dependencias: `pip install -r requirements.txt`
5. Crea un archivo `.streamlit/secrets.toml` y añade tu ASSISTANT_ID de OpenAI:
   ```
   ASSISTANT_ID = "tu-assistant-id-aqui"
   ```
6. Configura tu clave API de OpenAI como variable de entorno o en el archivo `secrets.toml`.

## Uso

1. Ejecuta la aplicación: `streamlit run app.py`
2. Abre tu navegador y ve a `http://localhost:8501`
3. Comienza a interactuar con el Asistente Virtual escribiendo tus preguntas o solicitudes.

## Contribuciones

Las contribuciones son bienvenidas. Por favor, haz un fork del repositorio, crea una nueva rama para tus cambios, y envía un pull request.

## Licencia

Este proyecto está bajo la licencia MIT. Consulta el archivo `LICENSE` para más detalles.

## Autor

Creado por Alexander Oviedo Fadul

[GitHub](https://github.com/bladealex9848) | [Website](https://alexander.oviedo.isabellaea.com/) | [LinkedIn](https://www.linkedin.com/in/alexander-oviedo-fadul-49434b9a/) | [Instagram](https://www.instagram.com/alexander.oviedo.fadul) | [Twitter](https://twitter.com/alexanderofadul) | [Facebook](https://www.facebook.com/alexanderof/) | [WhatsApp](https://api.whatsapp.com/send?phone=573015930519&text=Hola%20!Quiero%20conversar%20contigo!%20)