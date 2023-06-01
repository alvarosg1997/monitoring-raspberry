# Repositorio de Docker Compose para el Monitoreo de Raspberry Pi y la Red Doméstica

Este repositorio contiene un Docker Compose preconfigurado que permite realizar el monitoreo de las Raspberry Pi y la red doméstica de manera sencilla. El Docker Compose incluye una serie de servicios y herramientas de monitoreo que facilitan la recopilación de datos y la visualización de métricas en tiempo real.
## Características

Monitoreo de Raspberry Pi: El Docker Compose incluye servicios para recopilar información relevante de las Raspberry Pi, como el uso de CPU, memoria y temperatura. Estos servicios permiten obtener métricas en tiempo real y realizar un seguimiento del rendimiento de cada dispositivo.

Monitoreo de la red doméstica: Además de monitorear las Raspberry Pi, el Docker Compose proporciona herramientas para supervisar la red doméstica. Esto incluye servicios para escanear la red, identificar dispositivos conectados, monitorear el tráfico de red y realizar análisis de seguridad básicos.

Visualización de datos: Se incluye una interfaz web que proporciona una visualización intuitiva de los datos de monitoreo recopilados. Esta interfaz permite acceder a paneles de control personalizables que muestran gráficos y estadísticas en tiempo real sobre el rendimiento de las Raspberry Pi y el estado de la red doméstica.

Integración con alertas: El Docker Compose se puede configurar para enviar notificaciones y alertas en caso de eventos críticos o situaciones anómalas. Esto permite una respuesta rápida ante posibles problemas en las Raspberry Pi o en la red doméstica.
## Requisitos previos

Antes de utilizar este repositorio, asegúrate de tener instalados Docker y Docker-compose
## Cómo utilizar este repositorio

1. Clona este repositorio en tu máquina local utilizando el siguiente comando:

```bash
git clone https://github.com/alvarosg1997/monitoring-raspberry.git

2. Accede al directorio del repositorio clonado:

```bash
cd repo-monitoreo-raspberry
```
3. Abre el archivo docker-compose.yml en un editor de texto y personaliza la configuración según tus necesidades. Por ejemplo, puedes ajustar los puertos de exposición o las credenciales de autenticación.

4. Ejecuta el siguiente comando para iniciar los servicios de monitoreo en segundo plano:

```bash
docker-compose up -d
```
Esto creará y levantará los contenedores Docker correspondientes a cada servicio definido en el Docker Compose.

5. Una vez que los servicios estén en funcionamiento, puedes acceder a la interfaz de visualización abriendo un navegador web y visitando la dirección http://localhost:3030. Si has personalizado los puertos en el paso anterior, asegúrate de utilizar el puerto correcto en la URL.

## Configuración adicional
El repositorio proporciona una configuración básica para el monitoreo de las Raspberry Pi y la red doméstica. Sin embargo, es posible que desees realizar ajustes adicionales según tus necesidades específicas. Algunas opciones de configuración adicionales que podrías considerar son:

- Configurar alertas y notificaciones para recibir notificaciones en caso de eventos críticos.
- Personalizar los paneles de control en la interfaz de visualización para mostrar las métricas y estadísticas que sean más relevantes para ti.
- Agregar o ajustar servicios de monitoreo específicos según los dispositivos o servicios que desees supervisar en tu red doméstica.

Consulta la documentación de cada servicio incluido en el Docker Compose para obtener información detallada sobre las opciones de configuración disponibles.

## Contribución

Si deseas contribuir a este repositorio, siéntete libre de abrir un issue o enviar una solicitud de extracción. Agradecemos tus contribuciones y sugerencias para mejorar este proyecto.


