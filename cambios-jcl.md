# Documentación de Cambios en JCL

## Proyecto: Adaptaciones Easy Treve  
**Motivo del cambio**: Revisión de código COBOL  
**Tipo de cambio**: Modificación de múltiples JCLs  
**Duración estimada**: 1 año  
**Fecha de modificación**: 08/08/2025  
**Responsable**: [Nombre del analista/programador]

---

## Detalles del Cambio

| Elemento        | Valor anterior         | Valor nuevo              | Descripción del cambio                          |
|-----------------|------------------------|---------------------------|--------------------------------------------------|
| Programa COBOL  | `PROGOLD`              | `PROGNEW`                 | Se actualiza el programa tras revisión de código |
| Librería LOAD   | `APLIC.PROGOLD.LOADLIB`| `APLIC.PROGNEW.LOADLIB`  | Nueva ubicación del ejecutable                  |
| Dataset entrada | `DATOS.OLD.INPUT`      | `DATOS.EASYTREVE.INPUT`  | Se modifica el archivo de entrada               |
| Dataset salida  | `DATOS.OLD.OUTPUT`     | `DATOS.EASYTREVE.OUTPUT` | Se modifica el archivo de salida                |

---

## Comentarios Técnicos

- Se ha validado que el nuevo programa `PROGNEW` mantiene compatibilidad con el sistema de control de versiones.
- Se recomienda realizar pruebas de regresión para asegurar que el cambio no afecta otros procesos dependientes.
- Documentación actualizada en el repositorio interno: `[Ruta o enlace]`
