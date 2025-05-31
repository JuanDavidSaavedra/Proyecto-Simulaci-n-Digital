# 🦠 Simulación de la Influenza Aviar H5N1 en Aves Silvestres – Irlanda 🇮🇪

Este proyecto implementa un modelo híbrido de simulación para analizar la transmisión y progresión de la influenza aviar H5N1 en aves silvestres en Irlanda. Utiliza un enfoque comparativo entre dos métodos:  
- **WSA** (*Without Sampling and Allocation*)  
- **OSA** (*Outcomes Sampling and Allocation*)

El objetivo es comparar eficiencia y precisión entre ambos modelos para evaluar años de vida, calidad de vida ajustada (QALYs) y costos sanitarios.

---

## 🎯 Objetivos del Proyecto

* Desarrollar y validar un método eficiente para estimar los resultados en modelos de simulación de transmisión/progresión del virus H5N1.
* Comparar el rendimiento entre WSA y OSA en términos de precisión y costo computacional.
* Evaluar métricas clave como **LY (Life Years)**, **QALYs** y **Costos** para guiar políticas públicas.

---

## 🧠 Modelo de Simulación

El modelo combina dos componentes principales:

* **Simulación Basada en Agentes (ABS)**: modela la transmisión entre aves a partir de atributos como especie, edad y migración.
* **Cadena de Markov Monte Carlo**: simula la progresión clínica del virus a través de estados de salud (S1, S2, S3, DRD).

---

## 📊 Dataset

Fuente: [Bird Flu Dataset – Avian Influenza (Kaggle)](https://www.kaggle.com/datasets/jasmeet0516/bird-flu-dataset-avian-influenza)
Observaciones: 16,304 aves (con un 15.85% infectadas)
Atributos clave:

* Nombre científico
* Ubicación geográfica (Latitud/Longitud)
* Estado de infección (target\_H5\_HPAI)
* Año de captura

---

## ⚙️ Tecnologías

* Lenguaje: **R**
* Librerías: `dplyr`, `ggplot2`, `tidyr`, `maps`, `knitr`, `kableExtra`
* Entorno sugerido: **RStudio**

---

## 🧪 Resultados

* **Reducción del 81% en tiempo de ejecución** usando OSA frente a WSA.
* **Alta concordancia** en resultados de QALYs, LY y Costos entre ambos modelos.
* Visualizaciones CDF permiten comparar distribuciones de resultados de manera clara.

---

## 👥 Roles del Equipo

| Integrante                      | Rol Principal                                   |
| ------------------------------- | ----------------------------------------------- |
| Juan David Saavedra González    | Líder del proyecto/ Analista de datos    |
| Sergio Nelson Alberto Gómez Gil | Analista de simulación / Experto en dominio     |
| Juan Pablo Ávila Quitián        | Desarrollador de modelos  / Especialista en validación |

---

## 📄 Documentos Relevantes

* [Informe Final del Proyecto (PDF)](./informe_final.pdf)
* [Artículo Base](https://informs-sim.org/wsc24papers/inv111.pdf)
* [Presentación en YouTube](https://youtu.be/5_sbM9FpJsc?si=QsEoswbqLccc8OEA)

---

## 💬 Contacto

Este proyecto fue desarrollado como parte del curso **Simulación Digital – 2025-1**
**Universidad Industrial de Santander**
Profesor: David Romo Bucheli, PhD

---


