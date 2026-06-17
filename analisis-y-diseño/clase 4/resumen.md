# Documentación Profesional de Requerimientos.

## Introducción.

Después de descubrir los requerimientos, el siguiente paso es documentarlos de manera profesional utilizando estándares reconocidos por la industria. La documentación convierte los hallazgos en documentos oficiales que cualquier empresa puede comprender y utilizar.

# ¿Por qué documentar?

La documentación evita depender de la memoria del analista.

## Información en la mente:
- Se olvidan detalles.
- Nadie más puede consultarla.
- Se pierde si una persona abandona el proyecto.
- No puede verificarse ni auditarse.

## Información documentada:
- Permanece en el tiempo.
- Todo el equipo puede consultarla.
- Sirve como evidencia.
- Puede revisarse y mejorarse.

## Funciones de la documentación:
- **Acuerdo:** define lo que cliente y equipo construirán.
- **Guía:** orienta a los desarrolladores.
- **Verificación:** sirve para pruebas.
- **Conocimiento:** conserva información del proyecto.
- **Legal:** evidencia en auditorías o conflictos.

**Regla:** a mayor riesgo del proyecto, mayor nivel de documentación.

# Estándar IEEE 830.

El IEEE 830 es un estándar internacional para elaborar un SRS (Software Requirements Specification), documento donde se registran todos los requerimientos del sistema.

## Beneficios:
- Organización clara.
- Evita olvidar información importante.
- Facilita comunicación.
- Facilita auditorías.
- Reconocimiento internacional.

## Estructura del SRS:
- Introducción.
- Descripción general.
- Requisitos específicos.
- Apéndices.

## Características de un buen SRS:
- Correcto.
- No ambiguo.
- Completo.
- Consistente.
- Clasificado por prioridad.
- Verificable.
- Modificable.
- Trazable.

# Casos de Uso.

Un caso de uso describe paso a paso cómo un actor interactúa con el sistema para cumplir un objetivo.

## Diferencia:
- **Requerimiento:** qué hace el sistema.
- **Caso de uso:** cómo ocurre la interacción.

## Componentes:
- Actor.
- Sistema.
- Objetivo.
- Escenario.

## UML:
- Actor: persona o sistema externo.
- Óvalos: casos de uso.
- Rectángulo: sistema.
- Líneas: relaciones.

## Relaciones UML:
### Include.
Un caso de uso siempre incluye otro.

### Extend.
Agrega comportamiento opcional.

# Plantilla de Caso de Uso:

## Elementos:
- ID.
- Nombre.
- Actor principal.
- Descripción.
- Precondiciones.
- Postcondiciones.
- Flujo principal.
- Flujos alternos.
- Excepciones.
- Reglas de negocio.
- Frecuencia de uso.
- Prioridad.

## Errores comunes:
- Confundir con manual de usuario.
- Mezclar acciones del actor y sistema.
- No incluir excepciones.
- Ser demasiado general o demasiado detallado.

# Plantilla SRS IEEE.

## 1. Introducción:
- Propósito.
- Alcance.
- Definiciones.
- Referencias.
- Visión general.

## 2. Descripción General:
- Perspectiva del producto.
- Funciones principales.
- Usuarios.
- Restricciones.
- Suposiciones.

## 3. Requisitos Específicos:

### RF.
Funciones del sistema.

### RNF.
Calidad del sistema.

### Interfaces externas.
Integraciones con otros sistemas.

### Casos de uso.
Referencias a diagramas y descripciones.

## 4. Apéndices:
- Casos de uso.
- Diagramas UML.
- Bocetos.
- Trazabilidad.
- Glosario.

## Identificadores.
RF-001, RNF-001, CU-001 para trazabilidad y pruebas.

# Revisión Cruzada.

Proceso donde otro analista revisa el documento para detectar errores.

## Qué revisar:
- Ambigüedades.
- Contradicciones.
- Faltantes.
- No medibles.
- Dependencias.
- No atómicos.
- Jerga técnica.
- No verificables.

## Proceso:
1. Leer el documento.
2. Marcar errores.
3. Discutir con el autor.
4. Revisar correcciones.
