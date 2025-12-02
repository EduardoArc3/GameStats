# Ticket de Cambio (CH-001)

## ID del Cambio
CH-001

## Descripción del Cambio
Reestructuración completa de la arquitectura inicial del proyecto GameStats, incorporando la organización formal de directorios, clasificación de Objetos de Configuración (CI) según Pressman y creación de archivos base requeridos para establecer la Línea Base 1.1.

## Motivo
La estructura inicial del repositorio era mínima y no correspondía a la documentación técnica generada en actividades previas.  
Este cambio es necesario para:
- Organizar los CIs conforme a Pressman.
- Crear directorios oficiales (/docs, /src, /database, /frontend, /pruebas).
- Incorporar archivos representativos del diseño conceptual.
- Mantener trazabilidad entre diseño, código y documentos.

## Impacto
- Modifica la estructura raíz del repositorio.
- Afecta múltiples módulos del proyecto.
- Permite definir la Línea Base 1.1.
- Agrega nuevos CIs clave: controladores, servicios, modelos, vistas, scripts SQL y documentación.

## CI Afectados
- /docs/
- /src/
- /database/
- /frontend/
- /pruebas/

## Responsable
Ángel Eduardo Arce Gaxiola.

## Riesgo
Bajo.  
El cambio agrega estructura y documentación inicial, sin riesgos sobre funcionalidad existente.

## Costo Estimado
2 horas.
