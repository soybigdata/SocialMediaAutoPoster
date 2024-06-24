# Bot de Publicación Automática de Contenido Social

Este proyecto consiste en un bot desarrollado con Google Apps Script que automatiza la publicación de contenido en diversas redes sociales a partir de un archivo Google Sheet. Utiliza las APIs oficiales de las plataformas para garantizar la integridad y seguridad de los datos.

## Características

- **Soporte múltiple de plataformas**: Capacidad para publicar en múltiples redes sociales simultáneamente, incluyendo Facebook, Twitter, LinkedIn, Instagram, y más.
- **Automatización a través de Google Sheets**: Lee contenido y configuraciones de publicación desde un archivo Google Sheet, facilitando la gestión de múltiples publicaciones.
- **Seguridad y autenticación**: Implementa OAuth para autenticación segura con cada plataforma, asegurando que las publicaciones solo se realicen con cuentas autorizadas.

## Cómo funciona

1. **Configuración inicial**: Crea un archivo Google Sheet con las columnas necesarias para definir el contenido y las configuraciones de publicación.
2. **Autenticación**: Sigue los pasos para autenticar tu bot con cada plataforma social utilizando sus APIs y obtén las credenciales necesarias.
3. **Ejecución del bot**: Ejecuta el script de Google Apps Script para iniciar la publicación automática de contenido según las instrucciones en tu Google Sheet.

## Requisitos

- Un archivo Google Sheet con el formato especificado.
- Credenciales de OAuth para cada plataforma social objetivo.
- Conocimientos básicos de Google Apps Script.

## Instalación y Uso

1. Clona este repositorio en tu cuenta de Google Drive.
2. Abre el archivo `.gs` en Google Apps Script Editor.
3. Configura las credenciales de OAuth para cada plataforma en el script.
4. Personaliza el archivo Google Sheet según las instrucciones en el script.
5. Ejecuta el script para probar la publicación automática.

## Contribuciones

Las contribuciones son bienvenidas Si tienes ideas para mejorar este proyecto o quieres agregar soporte para nuevas plataformas, por favor abre un issue o haz un pull request.

## Licencia

Este proyecto está licenciado bajo la licencia MIT. Consulta el archivo `LICENSE` para más detalles.
