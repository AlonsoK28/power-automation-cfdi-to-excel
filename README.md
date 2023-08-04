# power-automation-cfdi-to-excel

## Como usar

1. Importa el proyecto en [Power automate desktop](https://powerautomate.microsoft.com/es-mx/) usando `CTRL + C` y `CTRL + V`
  - Ejemplo de [Como importar un project a Power automate desktop](https://youtu.be/M-VEP2eAih0?t=443) 

2. Selecciona el `archivo` o `directorio de trabajo` que contenga todos los `CFDI del SAT` en formato `XML` comprimidos como `ZIP`

3. El reporte será generado y podrás visualizarlo a partir en ese momento

## Pre-requisitos

- [Descargar del portal de SAT](https://www.youtube.com/watch?v=5eg26HsKI9Q) los CFDI que se deseen procesar 

- Tener instalada la paquetería de Microsoft Office en el dispositivo

## Descripcion del proceso
 
- El proceso `read_sat_cfdi_by_file` permite seleccionar un archivo ZIP para procesar
- El proceso `read_sat_cfdi_by_path` permite seleccionar un directorio que contenga múltiples  archivos  ZIP para procesar todos al mismo tiempo

## xml xpath query
Usa el servicio http://xpather.com/ para hacer tus propios `xpath query` al documento `XML`