# Instrucciones

Este documento define como debe trabajar cualquier miembro humano o IA dentro de `Admira Next`.

La idea es cubrir lo que pasa entre el onboarding y el offboarding: como se trabaja, como se entrega y que condiciones deben cumplirse antes de dar un cambio por cerrado.

## Principio base

Ser miembro de `Admira Next` no significa solo ejecutar tareas.

Significa actuar con criterio de equipo, cerrar ciclos de trabajo y dejar resultados visibles, supervisables y faciles de continuar.

## Regla central

`ONBOARDING.md` sirve para entrar.

`INSTRUCCIONES.md` sirve para trabajar correctamente durante el proceso.

`OFFBOARDING.md` sirve para salir dejando relevo.

Los tres documentos forman un mismo sistema y deben leerse como piezas complementarias.

## Como debe trabajar un miembro de Admira Next

- Trabajar pensando en el sistema completo, no solo en la tarea aislada.
- No dar por terminado un cambio si el resultado todavia no es visible para humanos.
- Convertir el trabajo tecnico en una salida clara, supervisable y util para la persona que coordina el proyecto.
- Comunicar bloqueos, supuestos, riesgos y decisiones abiertas antes de cerrar.
- Mantener continuidad para el siguiente relevo humano o IA.
- Priorizar claridad, trazabilidad y capacidad de supervision por encima de la velocidad ciega.

## Regla de entrega visible

No se considera terminado un cambio relevante hasta que exista una salida HTML que refleje el resultado para humanos.

Esa salida puede ser:

- una pagina nueva,
- una pagina existente actualizada,
- o una pagina de control, resumen o estado que permita revisar lo que acaba de cambiar.

## Secuencia obligatoria al final de los cambios

Al cerrar cualquier bloque relevante de trabajo, debe cumplirse esta secuencia completa:

1. actualizar o crear la pagina HTML que refleje el resultado visible;
2. subir la version a GitHub Pages;
3. asegurarse de que el cambio publicado tiene senal clara de version o `cache-busting` para evitar confusiones;
4. limpiar cache y recargar la URL publica real;
5. abrir esa URL publica en el navegador;
6. dejar la pagina lista para que Carlos, o la persona que coordina el proyecto, supervise el resultado final;
7. solo despues de eso, cerrar con `OFFBOARDING.md`.

## Lo que no debe pasar

- No cerrar un cambio dejando solo codigo interno sin reflejo visible.
- No decir que algo esta listo si la URL publica todavia no lo muestra.
- No confiar en una version local como validacion final cuando el resultado debe supervisarse en Pages.
- No saltarse la limpieza de cache si existe riesgo de estar viendo una version antigua.
- No cerrar la jornada sin dejar la pagina publica abierta para supervision.

## Relacion con la supervision

`Admira Next` necesita que el resultado final no sea solo correcto tecnicamente, sino tambien supervisable por la persona que dirige o coordina el trabajo.

Por eso la URL publica no es un detalle opcional: forma parte de la entrega.

## Checklist corto antes de decir "terminado"

- `ONBOARDING.md` revisado al entrar.
- Cambio realizado y documentado.
- Salida HTML actualizada o creada.
- GitHub Pages actualizado.
- Cache limpiada y version visible comprobada.
- URL publica abierta en navegador para supervision.
- `OFFBOARDING.md` completado al salir.
