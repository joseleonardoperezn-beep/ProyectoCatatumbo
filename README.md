# POA Restauración Ecológica Catatumbo (v2)

Plataforma de Control, Seguimiento Técnico, Jurídico y Financiero del Plan Operativo de Acción (POA) — Convenio MADS & Universidad de Pamplona (`BPIN 20253201010065`).

## Características Principales

- **Envíos Parciales Acumulables por Indicador**: Cada subactividad/indicador permite registrar múltiples envíos parciales con selección de **Mes y Año** que se suman progresivamente hasta completar el 100% de la meta física (ej. `960.000` plántulas o `1.600` hectáreas). Una vez alcanzada la meta, el sistema bloquea automáticamente nuevos envíos.
- **Carga Múltiple de Informes por Componente con Mes y Año**: Los componentes Jurídico, Financiero, Dirección Técnica OE1, OE2 y OE3 pueden subir múltiples archivos seleccionando el **Mes** y **Año** correspondientes.
- **Control de Eliminación de Archivos por Rol y Estado**:
  - El **Administrador** puede eliminar cualquier archivo en cualquier momento.
  - El **Técnico / Componente** que sube un archivo puede eliminarlo únicamente mientras aún **no haya sido aprobado** por las instancias superiores (`En Revisión` o `Devuelto`). Una vez aprobado, queda bloqueado para eliminación por parte del técnico.
- **Revisión y Comentarios por Archivo (Interventoría e Instancias Superiores)**:
  - La **Interventoría (`Entidad Supervisora / Cliente`)**, la **Dirección Técnica (`Gerente`)** y el **Administrador** pueden evaluar cada archivo individualmente, registrar observaciones y decidir si **Aprobar con comentarios** o **Devolver con comentarios**.
  - Si un envío parcial es devuelto con comentarios, su cantidad se descuenta del acumulado comprometido para permitir al técnico subsanar y volver a enviar.

## Estructura del Proyecto

- `index.html`: Aplicación principal lista para despliegue en GitHub Pages o Vercel.
