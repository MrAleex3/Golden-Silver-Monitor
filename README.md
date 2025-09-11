# ⚡ GTS Silver-Golden Finder

**GTS Silver-Golden Finder** es una herramienta que permite monitorear los registros de producción en múltiples equipos, detectando automaticamente la primera *Golden* válida (basada en repeticiones de seriales) y el estado de las *Silver*. Diseñada para entornos de manufactura, asegura que los equipos cumplan con los controles de calidad por turno y notifica por correo electrónico cuando se detectan fallos o ausencias.

<img width="1001" height="460" alt="image" src="https://github.com/user-attachments/assets/67d4727a-9e34-4cf6-b480-0c78732c6ec5" />


---

## ✅ Características Principales

- 🔍 Monitoreo en tiempo real de carpetas de producción
- ⚡ Identificación de Golden por turno
- 📧 Notificación automatica por correo si no se detecta Golden tras 1 hora del inicio del turno
- 📂 Clasificación y registro de pruebas por carpeta y turno
- 📝 Reportes de actividad con detalle de equipos y estatus

---

## 🚀 Funcionalidades Clave

### Detección de Golden
- Analiza los registros generados por los equipos
- Registra fechas y horas de ejecucion
- Marca la Golden como válida en el turno

### Detección de Silver
- Procesa pruebas Silver en paralelo a la Golden
- Reporta estado PASS/FAIL con marcas de tiempo

### Sistema de Alertas
- 📨 Envío de correos electronicos a multiples destinatarios
- 📋 Reporte detallado con carpetas/equipos que no cumplieron
- ⏱ Alertas automáticas después de 1 hora del inicio del turno

### Interfaz
- 🖥️ Interfaz gráfica sencilla
- 📊 Consola integrada para ver el proceso y logs
- 📂 Registro historico por turnos y equipos

---

## 📝 Licencia

Este proyecto está bajo la Licencia MIT.

## 🙋 Autor

**Jose Espinoza**  
Foxconn México · Herramienta desarrollada para el departamento de testing funcional
  ```bash
  pip install pillow
