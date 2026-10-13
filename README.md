# NovaMarket Correlation and Business Hypothesis Analysis – Sprint 8

Este repositorio contiene el análisis exploratorio y correlacional realizado durante el Sprint 8 para identificar relaciones estadísticas entre las métricas clave de actividad, comportamiento de compra, perfiles de clientes y el ingreso mensual en la plataforma NovaMarket. El proyecto trabaja con un dataset de 1,500 registros de usuarios activos, los cuales se limpian y analizan para formular hipótesis sólidas de negocio y optimizar las estrategias de segmentación.

## Contenido del repositorio

* `Proyect_Sprint08_Reporte_de_análisis_de_correlación_NovaMarket.ipynb`: Notebook principal que incluye la carga de datos, la limpieza mediante la exclusión de usuarios sin visitas, el análisis estadístico descriptivo, la visualización global de relaciones a través de mapas de calor y scatterplots, y el cálculo de coeficientes avanzados (Pearson, Spearman, Punto-biserial y V de Cramér) para la generación de hallazgos orientados al negocio.

## Cómo abrir el notebook en Google Colab

Haz clic en el siguiente botón:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1BwMOUSZit072oz_Cc_hoBoYg5sYE0sPD#scrollTo=27eb89b5)

O también puedes usar este enlace directo: [Abrir en Google Colab](https://colab.research.google.com/drive/1BwMOUSZit072oz_Cc_hoBoYg5sYE0sPD#scrollTo=27eb89b5)

## Objetivo del análisis

* **Identificar relaciones de actividad y conversión:** Evaluar la correlación lineal y de consistencia (Pearson y Spearman) entre el número de visitas en los últimos 30 días y las compras realizadas para guiar el diseño de estrategias de *engagement* previas al checkout.
* **Evaluar el impacto del modelo de suscripción:** Medir mediante el coeficiente Punto-biserial la fuerza de asociación entre el estado de suscripción del cliente y los ingresos mensuales generados, validando su efectividad como criterio único de segmentación comercial.
* **Analizar dependencias categóricas:** Utilizar la métrica V de Cramér para verificar matemáticamente si existen estructuras de preferencia o correlación no lineales entre la distribución geográfica (región) y la tecnología del usuario (tipo de dispositivo).
