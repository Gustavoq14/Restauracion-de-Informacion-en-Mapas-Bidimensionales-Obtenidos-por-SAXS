# Restauración de Información en Mapas Bidimensionales

Este repositorio contiene el código desarrollado para el trabajo de investigación titulado:
> [**"Restauración de información en mapas bidimensionales obtenidos en experimentos por dispersión de rayos X"**](https://www.researchgate.net/publication/396706739_Restauracion_de_informacion_en_mapas_bidimensionales_obtenidos_en_experimentos_por_dispersion_de_rayos_X)

El objetivo principal es la implementación de algoritmos de restauración de imágenes para mejorar la calidad de la información en mapas de **transmisión**, **absorción** y **dispersión** de fotones.

---

## Contexto del Proyecto

El trabajo fue desarrollado como parte de los requisitos para optar al título de [**Especialista en Aplicaciones Tecnológicas de la Energía Nuclear (CEATEN)**](https://www.ib.edu.ar/academicas/ceaten.html), posgrado dictado conjuntamente por el **Instituto Balseiro (IB)** y la **Universidad de Buenos Aires (UBA)**.

Los datos analizados provienen del equipo [Xeuss 2.0 SAXS/WAXS](https://www.xenocs.com/xenocs-saxs-waxs-instrument-at-the-national-university-of-san-martin/) del [Laboratorio de Cristalografía Aplicada (LCA)](https://iteca.conicet.gov.ar/laboratorio-de-cristalografia-aplicada-lca/) de la UNSAM.

---

## Contenido del Repositorio

A continuación se detallan los notebooks principales utilizados para el procesamiento de los mapas:

| Notebook | Descripción | Tipo de Muestra |
| :--- | :--- | :--- |
| [**Restauración_I.ipynb**](./Restauración_I.ipynb) | Aplicación de algoritmos a mapas de **transmisión** y **absorción**. | Una sola densidad electrónica. |
| [**Restauración_II.ipynb**](./Restauración_II.ipynb) | Aplicación de algoritmos al mapa de **dispersión**. | Dos densidades electrónicas. |

---

## Trabajo en Desarrollo

Actualmente, el proyecto se encuentra en fase de mejora mediante la implementación de:

* **LIRA (Low-counts Image Restoration and Analysis):** Algoritmo de restauración de imágenes astronómicas basado en un enfoque bayesiano, ideal para mejorar datos con baja estadística de conteo.
* Puedes consultar la documentación oficial de la librería aquí: [PyLIRA](https://pylira.readthedocs.io/en/latest/).

---

## Créditos

* **Instituciones:** Instituto Balseiro (CNEA-UNCUYO), Facultad de Ingeniería (UBA).
* **Laboratorio:** Laboratorio de Cristalografía Aplicada (LCA - UNSAM).
