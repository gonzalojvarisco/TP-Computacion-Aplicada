# Trabajo Práctico Integrador — Computación Aplicada

## Alumno
- Gonzalo Varisco

## Entorno
- Sistema operativo: Debian 12 (Bookworm)
- Virtualización: Oracle VirtualBox
- Hostname: TPServer
- Servidor web: Apache con PHP
- Base de datos: MariaDB
- Acceso remoto: SSH mediante claves

## Configuraciones realizadas
1. Configuración inicial del entorno.
2. Actualización del sistema operativo e instalación de servicios.
3. Configuración de red con IP estática.
4. Incorporación de un disco adicional y montaje de particiones.
5. Implementación de backups automatizados mediante Bash y cron.

## Entregables
Los archivos comprimidos de los directorios solicitados se encuentran en `entregables/`.

El archivo `var.tar.gz` se entrega dividido en partes numeradas.

Para reconstruirlo en Linux:

```bash
cat var.tar.gz.part-* > var.tar.gz
```

Para verificar su integridad:

```bash
gzip -t var.tar.gz
```

Para consultar su contenido:

```bash
tar -tzf var.tar.gz
```

## Observaciones
La entrega contiene configuraciones de un entorno académico de laboratorio y está destinada exclusivamente a su evaluación.