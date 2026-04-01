# Onboarding

Este documento sirve como punto de entrada para cualquier IA o colaborador humano que se incorpore al proyecto `Admira Next Dream Team`.

## Que estamos construyendo

`Admira Next Dream Team` nace como un repositorio preparado para trabajo asistido por varias IAs.

La idea no es empezar por tecnologia pesada, sino por una base compartida de contexto, normas y direccion. Antes de elegir stack o arquitectura, estamos definiendo:

- como colaboran varias IAs en un mismo repositorio,
- como mantener continuidad entre sesiones,
- como documentar decisiones desde el primer momento,
- y como crear una estructura suficientemente clara para humanos y asistentes.

## Estado actual del proyecto

- El repositorio esta en fase inicial.
- Ya existe una base de documentacion para colaboracion con IAs.
- Todavia no hay stack tecnico cerrado.
- No hay producto implementado aun.
- La prioridad actual es organizar contexto y preparar el terreno para siguientes iteraciones.
- `ONBOARDING.md` es el primer archivo que debe revisarse antes de cada actualizacion y al inicio de cada dia de trabajo.

## Marco estrategico de Admira Next

Todo el Dream Team debe trabajar teniendo presentes estos retos principales de Admira Next:

1. escasez de trabajadores,
2. restricciones de capital,
3. energia, infraestructuras y regulacion.

Estos retos funcionan como marco comun para priorizar ideas, roles, research, producto y narrativa.

La primera solucion ya identificada dentro de ese marco es esta:

- para el reto 1, escasez de trabajadores, Admira ha respondido creando su propia Universidad.
- para el reto 2, restricciones de capital, Admira responde con `Admira Next`, apostando por innovacion y soluciones mas automatizadas para hacer mas con los mismos recursos.
- para el reto 3, energia, infraestructuras y regulacion, Admira ha activado una estrategia de internacionalizacion con foco en China.

## Modelo organizativo en definicion

Admira Next quiere evolucionar hacia una `organizacion Pulpo` con 8 extremidades directivas.

Los roles definidos en este modelo son:

1. `CEO`
2. `CFO`
3. `CTO`
4. `CMO`
5. `COO`
6. `CHRO`
7. `CLO`
8. `CSO`

Este modelo debe leerse como una arquitectura de liderazgo pensada para cubrir vision, capital, tecnologia, mercado, operaciones, talento, regulacion y estrategia.

## Documentos existentes

- `README.md`: vision general del repositorio.
- `CLAUDE.md`: instrucciones iniciales para Claude.
- `AI_COLLABORATION.md`: reglas compartidas para varias IAs.
- `ONBOARDING.md`: este documento, pensado como guia central.
- `INSTRUCCIONES.md`: como debe trabajarse durante el proceso.
- `OFFBOARDING.md`: guia de cierre diario y relevo del trabajo.
- `onboarding.html`: version HTML de este onboarding para lectura humana.
- `dream-team/`: carpeta con una subestructura por cada estrella del equipo.

## Conceptos que estamos trabajando

### 1. Colaboracion multi-IA

Queremos que varias IAs puedan participar en el mismo proyecto sin crear caos. Eso implica:

- trabajar con cambios pequenos y bien delimitados,
- dejar contexto facil de recuperar,
- no asumir que la siguiente IA conoce el historial completo,
- y reducir al minimo el trabajo duplicado.

### 2. Contexto persistente

Cada IA debe poder leer rapidamente:

- que es el proyecto,
- en que estado se encuentra,
- que decisiones ya existen,
- que reglas de colaboracion debe respetar,
- y cual es el siguiente paso razonable.

La documentacion cumple esa funcion.

### 3. Claridad antes que stack

En esta fase estamos priorizando definicion sobre implementacion. Antes de crear una app, queremos responder:

- que va a ser exactamente este proyecto,
- para quien se construye,
- cual es su primera entrega visible,
- y que tecnologia tiene sentido usar.

### 4. Doble formato de conocimiento

Estamos separando la informacion en dos formatos:

- Markdown para IAs y trabajo tecnico.
- HTML para humanos que prefieran una lectura mas visual y directa.

Esto permite que el mismo conocimiento sea util en distintos contextos.

### 5. Iteracion ligera

No queremos sobredisenar el proyecto demasiado pronto. La estrategia actual es:

1. definir contexto,
2. documentar normas,
3. preparar onboarding,
4. elegir direccion del producto,
5. construir una primera version visible.

## Principios actuales

- Claridad antes que complejidad.
- Cambios faciles de revisar.
- Documentacion como infraestructura.
- Continuidad entre sesiones y entre asistentes.
- Base ligera hasta que el producto este definido.
- Revisar siempre el onboarding antes de trabajar para no perder novedades dejadas por otras IAs.

## Como debe entrar una nueva IA

Cuando una nueva IA llegue al proyecto, deberia:

1. leer `ONBOARDING.md` como primer paso obligatorio,
2. leer `README.md`,
3. leer `AI_COLLABORATION.md`,
4. leer `INSTRUCCIONES.md`,
5. revisar `CLAUDE.md` si aplica al asistente o a su forma de trabajo,
6. identificar el objetivo actual antes de proponer cambios.

## Regla operativa diaria

Antes de cada actualizacion y antes de empezar cualquier jornada de trabajo en `Admira Next Dream Team`, lo primero que debe revisarse es `ONBOARDING.md`.

La razon es simple: otra IA puede haber dejado consejos, novedades, contexto nuevo o cambios de direccion, y el equipo debe empezar siempre desde la informacion mas actualizada disponible.

Ademas, toda actualizacion visible para humanos debe reflejarse tambien en su version HTML correspondiente.

Cada vez que se actualice una salida HTML, debe subirse la version visible `+1` dentro de la propia pagina para que, tras limpiar cache, se pueda comprobar rapidamente que se esta viendo la ultima version publicada.

Mientras se trabaja, debe aplicarse tambien `INSTRUCCIONES.md` para recordar la conducta esperada y la secuencia obligatoria de entrega visible.

Al terminar la jornada o un bloque relevante de trabajo, debe revisarse y aplicarse `OFFBOARDING.md` para dejar el relevo correctamente documentado.

## Ritual diario completo

El flujo diario del equipo queda asi:

1. entrar leyendo `ONBOARDING.md`,
2. trabajar sobre el contexto actualizado,
3. trabajar segun `INSTRUCCIONES.md`,
4. documentar cambios relevantes durante el proceso,
5. actualizar tambien la salida HTML y subir su version visible `+1`,
6. limpiar cache, abrir la URL publica y dejarla lista para supervision,
7. cerrar con `OFFBOARDING.md`,
8. y reflejar la actualizacion diaria en la web principal del proyecto.

## Siguientes direcciones posibles

Ahora mismo el proyecto puede evolucionar hacia una de estas opciones:

1. una landing comercial,
2. una aplicacion web,
3. un workspace con varios modulos,
4. una base experimental de colaboracion entre IAs.

## Estructura Dream Team

Ya existe una estructura inicial para organizar el equipo de asistentes dentro de `dream-team/`.

Las estrellas iniciales son:

- `claude`
- `codex`
- `gemini`
- `perplexity`
- `mistral`
- `customer-care`

Cada una tiene su propia subcarpeta para poder separar rol, contexto y futuras responsabilidades.

## Recomendacion actual

La recomendacion mas razonable en este momento es decidir primero la forma del proyecto y, a partir de ahi, crear la estructura tecnica minima necesaria.

## Resumen corto para IAs

`Admira Next Dream Team` es un repositorio en fase inicial, orientado a colaboracion entre varias IAs. Aun no tiene stack ni producto final definidos. La prioridad actual es documentar contexto, ordenar la colaboracion y preparar una base clara para construir el siguiente paso con coherencia.
