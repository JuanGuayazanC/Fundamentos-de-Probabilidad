# Fundamentos de Probabilidad (FPRO)

Agrupa los talleres, parciales, recursos y el proyecto del curso.

## Estructura del proyecto

```
Fundamentos-de-Probabilidad/
├── Talleres/
│   ├── Taller-Probabilidad-Condicional-en-R-FPRO/
│   ├── Taller-Distribucion-Normal-Salarios-FPRO/
│   ├── Taller-Distribucion-Discreta-Valor-Esperado-FPRO/
│   └── Algebra-Lineal-FPRO/
├── Parciales/
│   ├── Parcial-Clasificacion-de-Credito-FPRO/
│   └── Parcial-Distribucion-Binomial-FPRO/
├── Recursos/
│   ├── Simulacion-y-Probabilidad-Condicional-FPRO/
│   └── Distribuciones-Normal-y-Discreta-FPRO/
└── Proyectos/
    └── Distribuciones-Rademacher-y-Erlang-FPRO/
```

## Temas del curso

- Técnicas de conteo y conjuntos.
- Probabilidad: eventos, probabilidad total y teorema de Bayes.
- Variables aleatorias discretas y continuas.
- Distribuciones de probabilidad discretas y continuas.
- Fundamentos de álgebra lineal aplicados a probabilidad.

## Cosas a tener en cuenta

- Cada repositorio corresponde a una actividad puntual (taller, parcial o recurso) o al proyecto del curso; el tipo de actividad está indicado en la descripción de cada repositorio, no en su nombre.
- Los recursos (`Simulacion-y-Probabilidad-Condicional-FPRO`, `Distribuciones-Normal-y-Discreta-FPRO`) son ejercicios de clase trabajados a partir de material de la profesora, sin entrega individual.
- Los talleres y parciales de equipo se entregaron junto con Gabriel Alejandro Rodríguez Pulido y Nicol Sofía Guerra Lasso.
- El proyecto del curso (`Distribuciones-Rademacher-y-Erlang-FPRO`) tiene una estructura de README distinta a la del resto de actividades académicas, ya que corresponde a un trabajo de análisis extendido y no a una entrega puntual.

## Profesora

Ana Carolina Cabrera Blandón.

## Cómo usar este repositorio

Este repositorio no contiene código directamente: es una colección de repositorios independientes, uno por actividad, organizados por carpetas (`Talleres/`, `Parciales/`, `Recursos/`, `Proyectos/`). Cada carpeta es un submódulo de git que apunta al repositorio real de esa actividad.

- **Para consultar una actividad puntual**: entra directamente a su carpeta en GitHub (o navega el submódulo) y revisa su propio README.
- **Para tener todo el contenido en tu máquina**:

```bash
git clone --recurse-submodules https://github.com/JuanGuayazanC/Fundamentos-de-Probabilidad.git
```

Si ya clonaste el repositorio sin submódulos:

```bash
git submodule update --init --recursive
```
