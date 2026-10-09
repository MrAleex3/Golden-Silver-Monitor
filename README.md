# Golden & Silver Monitor

Herramienta interna para monitorear los registros de producción de varios equipos, detectar automáticamente la primera Golden válida a partir de las repeticiones de seriales y revisar el estado de las Silver. Está pensada para entornos de manufactura: verifica que los equipos cumplan con los controles de calidad por turno y notifica por correo electrónico cuando detecta fallos o ausencias.

![Interfaz](https://github.com/user-attachments/assets/67d4727a-9e34-4cf6-b480-0c78732c6ec5)

## Características

- Monitoreo en tiempo real de las carpetas de producción.
- Identificación de la Golden por turno.
- Notificación automática por correo si no se detecta Golden una hora después del inicio del turno.
- Clasificación y registro de pruebas por carpeta y turno.
- Reportes de actividad con el detalle de equipos y estatus.

## Funcionamiento

### Detección de Golden

- Analiza los registros generados por los equipos.
- Registra las fechas y horas de ejecución.
- Marca la Golden como válida dentro del turno.

### Detección de Silver

- Procesa las pruebas Silver en paralelo a la Golden.
- Reporta el estado PASS/FAIL con marcas de tiempo.

### Sistema de alertas

- Envío de correos electrónicos a varios destinatarios.
- Reporte detallado con las carpetas y equipos que no cumplieron.
- Alertas automáticas una hora después del inicio del turno.

### Interfaz

- Interfaz gráfica sencilla.
- Consola integrada para seguir el proceso y los logs.
- Registro histórico por turno y equipo.

## Licencia

Este proyecto está bajo la Licencia MIT. Consulta el archivo [LICENSE](LICENSE).

## Autor

Alejandro Espinoza
Foxconn México
