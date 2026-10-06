# Distribución de tareas

Aplicación de escritorio para gestionar categorías, empleados, vehículos y distribución diaria de tareas con guardado local y exportación a Excel.

## Qué incluye
- Selección de categoría
- Lista de trabajadores por categoría
- Asignación de tareas por día
- Descripción de trabajos, clase y tipo
- Vehículos asociados
- No duplica trabajadores entre tareas del mismo día
- Guarda datos automáticamente en base local SQLite
- Exporta un archivo Excel acumulativo a `Documentos/Distribucion_Tareas/registro_tareas.xlsx`

## Cómo ejecutar

1. Instala dependencias:
   npm install

2. Ejecuta la app:
   npm start

## Cómo crear instalador para Windows

npm run build

Se generará un ejecutable portable para Windows y un AppImage para Linux en la carpeta `dist/`.

## Formato del Excel

La hoja exportada tendrá esta estructura:
- Fecha
- Tarea
- Clase de trabajo
- Tipo de trabajo
- Descripción
- Trabajadores
- Vehículo 1
- Vehículo 2
- Vehículo 3

Todo queda acumulado en el mismo archivo para cada día nuevo.
