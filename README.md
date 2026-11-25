# Agenda de Audiencias - JG Illapel

Aplicación web de programación y control diario de audiencias en intervalos de 15 minutos con sincronización en tiempo real, acceso restringido a usuarios autorizados y carga masiva desde planillas Excel.

## Funcionalidades principales

- **Grilla estilo Google Calendar (15 minutos):** Visualización diaria, semanal y mensual con bloques simultáneos lado a lado, creación por selección de rango, arrastrar/soltar y ajuste de duración.
- **Control de acceso:** Autenticación mediante Firebase Authentication limitada exclusivamente a cuentas autorizadas.
- **Sincronización en tiempo real:** Actualización instantánea entre usuarios conectados mediante Firebase Realtime Database, con registro de creación y última modificación.
- **Importación masiva desde Excel:** Carga directa de archivos `.xlsx`/`.xls` (`RIT/Año`, `Día`, `Hora inicio`, `Hora término`, `Tipo audiencia`, `Sala`) con validación de duplicados y descarga de plantilla base.

## Acceso en línea

Disponible en GitHub Pages: `https://efra-dev25.github.io/agenda/`
