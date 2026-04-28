# Práctica Temática: Propuesta Documentada de Mini Proyecto en Terminal

## 1) Título de la actividad

**Diseño de Propuesta: Mini Proyecto Temático (ARM64 Assembly, C, Python o Bash)**

> Ejemplos de títulos válidos para tu propuesta:
> - “Mini Toolkit en ARM64”
> - “Asistente de Estudio en Terminal”
> - “Reporteador de Información del Sistema”
> - “Organizador de Archivos”
> - “Juego de Aprendizaje en Línea de Comandos”

---

## 2) Descripción general

En esta actividad **no se evalúa un sistema grande terminado**, sino tu capacidad para **diseñar, documentar y justificar** una práctica temática pequeña que pueda desarrollarse por etapas en GitHub Classroom.

Tu tarea será elaborar una **propuesta de proyecto pequeño**, enfocado en terminal, seleccionando **un lenguaje principal**:

- ARM64 Assembly
- C
- Python
- Bash

### Reglas de alcance

- El proyecto debe ser **pequeño y realista** para completarse con recursos limitados.
- Si eliges **ARM64 Assembly**, se recomienda que sea para programas **muy pequeños** (por ejemplo: operaciones básicas, parsing mínimo, manejo simple de entradas/salidas).
- La prioridad es: **documentar primero** (idea, caso de uso, estructura y pruebas) antes de escribir mucho código.
- Evita: frameworks grandes, APIs pagadas, bases de datos, nube, contenedores y dependencias complejas.

---

## 3) Entregables del estudiante

Tu repositorio debe incluir **como mínimo**:

- `README.md`
- `docs/propuesta.md`
- `docs/caso_de_uso.md`
- `docs/estructura_repositorio.md`
- `docs/plan_de_pruebas.md`

También puedes agregar, de forma opcional:

- `src/`
- `scripts/`
- `tests/`

---

## 4) Estructura recomendada del repositorio

Usa esta estructura base:

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

> `main.<ext>` debe corresponder al lenguaje elegido (`.s`, `.c`, `.py` o `.sh`).

---

## 5) Contenido mínimo de cada documento

### `README.md`
Incluye:

1. Nombre del proyecto.
2. Lenguaje principal elegido y justificación breve.
3. Objetivo general (1 párrafo).
4. Alcance (qué sí hace y qué no hace).
5. Instrucciones básicas para ejecutar (aunque sea prototipo).
6. Estructura del repositorio (resumen).

### `docs/propuesta.md`
Incluye:

1. **Tema** del mini proyecto.
2. **Problema que resuelve** (claro y acotado).
3. **Usuarios objetivo** (quién lo usaría).
4. **Funcionalidades mínimas** (MVP, 3 a 5 puntos).
5. **No objetivos** (qué queda fuera para mantenerlo pequeño).
6. **Lenguaje elegido y motivo técnico**.
7. **Estimación de tamaño** (por ejemplo: número aproximado de archivos o funciones).

### `docs/caso_de_uso.md`
Incluye:

1. Escenario principal de uso.
2. Entrada esperada del usuario.
3. Flujo paso a paso.
4. Salida esperada.
5. Errores comunes y cómo se comunicarían.

### `docs/estructura_repositorio.md`
Incluye:

1. Árbol del repositorio actualizado.
2. Propósito de cada carpeta y archivo clave.
3. Convenciones de nombres (archivos, scripts, pruebas).
4. Estrategia de crecimiento (si luego se agrega funcionalidad).

### `docs/plan_de_pruebas.md`
Incluye:

1. Objetivo de pruebas.
2. Lista de casos de prueba funcionales mínimos (al menos 5).
3. Formato de evidencia (capturas, logs o salidas de terminal).
4. Criterios de aceptación por caso.
5. Riesgos técnicos esperados y mitigación.

---

## 6) Lineamientos técnicos

- Tu proyecto debe correr en entorno local con comandos simples.
- Si usas Python o Bash, procura usar librerías estándar del sistema.
- Si usas C, mantén compilación directa con `gcc` o `clang` sin toolchains complejos.
- Si usas ARM64 Assembly, limita el alcance a ejercicios breves y bien documentados.
- Se evaluará más la **claridad de diseño** que la cantidad de código.

---

## 7) Criterios de evaluación sugeridos (100 puntos)

1. **Claridad y coherencia de la propuesta** (25 pts)
2. **Calidad de documentación técnica** (25 pts)
3. **Viabilidad del alcance (proyecto pequeño)** (20 pts)
4. **Estructura de repositorio y organización** (15 pts)
5. **Plan de pruebas y criterios de aceptación** (15 pts)

---

## 8) Recomendaciones para mantener el proyecto pequeño

- Enfócate en **una sola necesidad concreta**.
- Define máximo **3–5 funcionalidades**.
- Evita interfaces gráficas y servicios externos.
- Entrega primero documentación sólida, luego prototipo mínimo.
- Prioriza que cualquier compañero pueda clonar y entender el proyecto en pocos minutos.

---

## 9) Formato de entrega en GitHub Classroom

1. Crea tu repositorio desde la asignación de Classroom.
2. Sube la estructura base con los archivos solicitados.
3. Completa los documentos en `docs/`.
4. (Opcional) Agrega implementación mínima en `src/` y script de ejecución.
5. Verifica que el `README.md` permita entender y ejecutar tu propuesta.
6. Realiza commit final con mensaje sugerido:

```bash
git add .
git commit -m "Entrega: propuesta documentada de mini proyecto temático"
```

---

## 10) Plantilla breve de arranque (puedes copiar/pegar)

### `docs/propuesta.md` (inicio rápido)

```md
# Propuesta de Mini Proyecto

## Tema

## Problema a resolver

## Usuario objetivo

## Funcionalidades mínimas (MVP)
1.
2.
3.

## No objetivos

## Lenguaje principal y justificación

## Estimación de tamaño del proyecto
```

### `docs/caso_de_uso.md` (inicio rápido)

```md
# Caso de Uso Principal

## Escenario

## Entrada

## Flujo principal
1.
2.
3.

## Salida esperada

## Manejo de errores comunes
```

### `docs/plan_de_pruebas.md` (inicio rápido)

```md
# Plan de Pruebas

## Objetivo

## Casos de prueba
- Caso 1:
- Caso 2:
- Caso 3:
- Caso 4:
- Caso 5:

## Evidencia

## Criterios de aceptación

## Riesgos y mitigación
```

---

## 11) Resultado esperado de aprendizaje

Al finalizar, el estudiante será capaz de:

- Plantear una práctica técnica con alcance controlado.
- Justificar decisiones de lenguaje y diseño.
- Organizar un repositorio profesional para trabajo incremental.
- Definir pruebas básicas antes de escalar implementación.
