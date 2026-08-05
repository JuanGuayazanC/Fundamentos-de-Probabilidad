# Fundamentos de Probabilidad (FPRO)

Agrupa los talleres y el proyecto del curso.

## Estructura del proyecto

```
Fundamentos-de-Probabilidad/
├── Talleres/
│   ├── Probabilidad_Bayes_FPRO/
│   ├── DISTRIBUCIONES-FPRO/
│   └── Algebra-Lineal-FPRO/
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

- Cada repositorio corresponde a una entrega puntual (talleres agrupados por corte, o el proyecto del curso); el tipo de actividad está indicado en la descripción de cada repositorio, no en su nombre.
- Los talleres se entregaron en equipo (Gabriel Alejandro Rodríguez Pulido, Nicol Sofía Guerra Lasso y Juan Sebastián Guayazán Clavijo).
- El proyecto del curso (`Distribuciones-Rademacher-y-Erlang-FPRO`) tiene una estructura de README distinta a la del resto de actividades académicas, ya que corresponde a un trabajo de análisis extendido y no a una entrega puntual.

## Profesora

Ana Carolina Cabrera Blandón.

## Cómo usar este repositorio

Este repositorio no contiene código directamente: es una colección de repositorios independientes, uno por actividad, organizados por carpetas (`Talleres/`, `Proyectos/`). Cada carpeta es un submódulo de git que apunta al repositorio real de esa actividad.

- **Para consultar una actividad puntual**: entra directamente a su carpeta en GitHub (o navega el submódulo) y revisa su propio README.
- **Para tener todo el contenido en tu máquina**:

```bash
git clone --recurse-submodules https://github.com/JuanGuayazanC/Fundamentos-de-Probabilidad.git
```

Si ya clonaste el repositorio sin submódulos:

```bash
git submodule update --init --recursive
```
