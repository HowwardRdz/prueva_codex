# Actividad: Propuesta de Práctica Temática Pequeña (enfocada en documentación)

## 1) Título de la práctica
**Diseña un título claro y concreto para tu propuesta.**  
Puedes usar uno de estos ejemplos o crear uno similar:

- **Mini Toolkit en ARM64**
- **Asistente de Estudio en Terminal**
- **Reporteador de Información del Sistema**
- **Organizador de Archivos**
- **Juego de Aprendizaje en Línea de Comandos**

> Sugerencia: el título debe reflejar qué problema resuelves y para quién.

---

## 2) Descripción general
En esta actividad **no vas a empezar programando en grande**. Tu objetivo principal es **diseñar y documentar** una propuesta de proyecto pequeño y viable para desarrollarse en este curso.

Debes elegir **un lenguaje principal** para tu propuesta:

- ARM64 Assembly
- C
- Python
- Bash

### Importante
- Si eliges **ARM64 Assembly**, limita tu proyecto a un programa **muy pequeño** (por ejemplo: operaciones básicas, manejo simple de cadenas o flujo de control elemental).
- La prioridad de esta actividad es: **justificar la idea, planear el repositorio y definir pruebas básicas** antes de escribir mucho código.
- Mantén el alcance pequeño y realista para poder trabajar con herramientas de IA de uso gratuito y límites diarios.

---

## 3) Entregables del estudiante
Tu repositorio debe incluir, como mínimo, los siguientes archivos:

- `README.md`
- `docs/propuesta.md`
- `docs/caso_de_uso.md`
- `docs/estructura_repositorio.md`
- `docs/plan_de_pruebas.md`

Opcionales (si ya quieres adelantar implementación mínima):

- `src/`
- `scripts/`
- `tests/`

---

## 4) Estructura recomendada del repositorio
Usa como referencia esta estructura mínima:

```text
nombre-del-proyecto/
├── README.md
├── docs/
│   ├── propuesta.md
│   ├── caso_de_uso.md
│   ├── estructura_repositorio.md
│   └── plan_de_pruebas.md
├── src/
│   └── main.<ext>
├── scripts/
│   └── run.sh
└── tests/
    └── test_plan.md
```

---

## Instrucciones de contenido por archivo

## `README.md`
Debe incluir:
1. **Nombre del proyecto**.
2. **Resumen breve** (qué hace y por qué existe).
3. **Lenguaje principal elegido** (ARM64 Assembly, C, Python o Bash).
4. **Alcance pequeño** (qué sí hará y qué no hará).
5. **Cómo ejecutar** (aunque sea de forma preliminar).
6. **Estructura del repositorio** (enlace o referencia a `docs/estructura_repositorio.md`).

---

## `docs/propuesta.md`
Estructura mínima sugerida:

1. **Tema y contexto**
   - ¿Qué necesidad pequeña atiende tu proyecto?
2. **Objetivo general**
   - Una sola meta clara y medible.
3. **Objetivos específicos (3 a 5)**
   - En formato de lista.
4. **Lenguaje seleccionado y justificación**
   - ¿Por qué ese lenguaje y no otro?
5. **Alcance**
   - Incluye “Incluye” y “No incluye”.
6. **Entregable técnico mínimo (MVP)**
   - Define una versión funcional mínima y alcanzable.
7. **Riesgos y supuestos**
   - Ejemplo: tiempo, curva de aprendizaje, errores frecuentes.

---

## `docs/caso_de_uso.md`
Debe describir un escenario concreto de uso:

1. **Actor principal** (quién usa el proyecto).
2. **Problema que enfrenta**.
3. **Flujo principal paso a paso** (5 a 10 pasos).
4. **Entradas esperadas**.
5. **Salidas esperadas**.
6. **Criterios de aceptación** (cómo sabrás que sí funciona).

> Recomendación: usa lenguaje simple y comprobable.

---

## `docs/estructura_repositorio.md`
Debe explicar la organización del proyecto:

1. Árbol de carpetas (actualizado al estado real del repo).
2. Propósito de cada carpeta/archivo clave.
3. Convenciones de nombres (archivos, scripts, pruebas).
4. Estrategia básica de crecimiento (cómo escalar sin desordenar).

---

## `docs/plan_de_pruebas.md`
Incluye pruebas básicas, manuales y/o automatizadas:

1. **Objetivo de pruebas**.
2. **Casos de prueba mínimos (al menos 5)**:
   - ID
   - Descripción
   - Entrada
   - Resultado esperado
3. **Pruebas de error o borde (al menos 2)**.
4. **Cómo ejecutar pruebas** (comandos simples).

> Si todavía no hay código, documenta pruebas planeadas sobre prototipos o salidas esperadas.

---

## Restricciones de la actividad
Para mantener la práctica viable y enfocada en aprendizaje base:

- Evita proyectos grandes.
- No uses frameworks pesados.
- No uses APIs pagadas.
- No uses bases de datos.
- No uses servicios en la nube.
- No uses contenedores.
- Evita dependencias complejas.

El objetivo es que puedas terminar una versión mínima funcional con buena documentación y estructura.

---

## Criterios de evaluación sugeridos (100%)

- **Calidad de la propuesta** (claridad, enfoque, viabilidad): **30%**
- **Caso de uso** (coherencia y detalle operativo): **20%**
- **Estructura del repositorio** (orden, justificación): **20%**
- **Plan de pruebas** (cobertura mínima y criterios claros): **20%**
- **Presentación general** (redacción, formato Markdown, ortografía): **10%**

---

## Entrega
- Publica tu repositorio en GitHub Classroom con la estructura solicitada.
- Asegúrate de que todos los archivos Markdown abran correctamente.
- Si agregas código, que sea mínimo y consistente con tu propuesta.

**Meta final:** demostrar que puedes **pensar, justificar, planear y documentar** un proyecto técnico pequeño antes de escalar implementación.
