# Nivel 2 – Resumen completo

## 1. Profundización del concepto

### Definición formal
**Un requerimiento es una propiedad documentada que un sistema debe poseer para resolver un problema o lograr un objetivo. Es una declaración verificable de una funcionalidad, restricción o característica de calidad.**

Las dos palabras clave son:
- **Documentada**
- **Verificable**

Si no se puede escribir y comprobar, **NO es un requerimiento**.

### Niveles de abstracción

**Necesidad del usuario**
> "Quiero saber qué hay de comida para no perder el viaje a la cafetería."

**Requerimiento del sistema**
> "El sistema debe mostrar el menú del día actualizado a todos los estudiantes autenticados."

**Especificación técnica**
> "La API /menu/dia debe retornar un JSON con los platos del día, en menos de 300 ms, usando HTTPS."

**Tu trabajo como analista es traducir hacia arriba: tomar lo que dice el usuario (informal, emocional) y convertirlo en algo formal, documentado y verificable.**

### Fuentes de requerimientos

- **Usuarios finales:** los que usarán el sistema día a día.
- **Clientes / patrocinadores:** los que pagan y tienen objetivos de negocio.
- **Leyes y normas:** regulaciones que el sistema debe cumplir.
- **Sistemas externos:** otros programas con los que se debe integrar.

### Características de un buen requerimiento

- **Necesario**
- **No ambiguo**
- **Verificable**
- **Consistente**
- **Completo**
- **Atómico**
- **Trazable**

---

## 2. Requerimientos Funcionales (RF)

### Definición

**Un requerimiento funcional (RF) describe una acción concreta que el sistema debe realizar. Define las funciones, tareas, cálculos o respuestas del sistema ante entradas específicas.**

Representan el **qué hace el sistema**.

### Cómo identificarlos

- **Verbos de acción:** permitir, registrar, calcular, mostrar, enviar, generar, validar, modificar.
- **Entradas y salidas:** "el sistema recibe X y produce Y".
- **Decisiones:** "si pasa X, hacer Y; si no, hacer Z".
- **Roles:** "el administrador puede...", "el estudiante debe...".

### Plantilla

> El sistema deberá [acción/verbo] [objeto] [condiciones/restricciones].

### Categorías

- **Autenticación**
- **Cálculo**
- **Persistencia**
- **Comunicación**
- **Reporte**
- **Validación**

### Regla importante

Si un requerimiento tiene más de una idea, **no es atómico**.

---

## 3. Requerimientos No Funcionales (RNF)

### Definición

**Un requerimiento no funcional (RNF) describe cómo debe comportarse el sistema, no qué hace.**

- RF = QUÉ hace el sistema
- RNF = CÓMO lo hace

### Importancia

Un sistema puede fallar aunque cumpla sus RF si no cumple RNF como:

- Seguridad
- Rendimiento
- Usabilidad

### Categorías

- Rendimiento (Performance)
- Seguridad
- Usabilidad
- Confiabilidad
- Escalabilidad
- Mantenibilidad
- Portabilidad / Compatibilidad
- Legales / Regulatorios

### Regla de oro

**Un RNF sin métrica es un deseo, no un requerimiento.**

Todo RNF debe definir:
- Métrica
- Umbral
- Forma de verificación

### Trade-offs

- Seguridad ↔ Usabilidad
- Rendimiento ↔ Mantenibilidad
- Escalabilidad ↔ Costo

---

## 4. Atributos de Calidad

### Definición

**Los atributos de calidad son las características generales que determinan qué tan bueno es un software.**

Son conceptos abstractos que se convierten en RNF.

### Relación

- Atributo = concepto general
- RNF = forma concreta y medible

### ISO/IEC 25010

1. Adecuación funcional  
2. Eficiencia de desempeño  
3. Compatibilidad  
4. Usabilidad  
5. Confiabilidad  
6. Seguridad  
7. Mantenibilidad  
8. Portabilidad  