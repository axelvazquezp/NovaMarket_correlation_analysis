# NovaMarket - Correlation & Business Hypothesis Analysis 🛍️📉

Este repositorio contiene un caso de estudio avanzado de análisis exploratorio y modelado estadístico correlacional realizado sobre el comportamiento transaccional en la plataforma **NovaMarket**. El proyecto evalúa un histórico de 1,500 registros de usuarios activos para formular hipótesis cuantitativas sólidas y optimizar las estrategias de segmentación comercial.

---

## 🎯 Contexto y Problema de Negocio
El equipo de estrategia comercial de NovaMarket buscaba identificar las palancas analíticas que maximizan el ingreso mensual por usuario. Para ello, era indispensable romper los supuestos tradicionales de segmentación y evaluar matemáticamente qué métricas de actividad (visitas, suscripciones, demografía) tienen una fuerza de asociación real con la conversión final.

Este análisis estratégico busca responder a tres preguntas de negocio:
1. ¿Existe una relación lineal o de consistencia directa entre el volumen de visitas mensuales y las transacciones de compra completadas?
2. ¿El modelo de suscripción actual justifica ser el criterio único de segmentación comercial debido a su impacto en el ingreso?
3. ¿Existen dependencias o patrones de comportamiento ocultos entre el tipo de dispositivo tecnológico que usa el cliente y su ubicación geográfica?

---

## 🛠️ Tecnologías y Herramientas Utilizadas
*   **Python (Pandas, NumPy):** Procesamiento inicial, filtrado lógico por actividad (exclusión de usuarios con cero visitas) y preparación de variables categóricas.
*   **SciPy & Statsmodels:** Computación estadística avanzada para el cálculo de matrices de correlación paramétrica, no paramétrica y de contingencia.
*   **Matplotlib & Seaborn:** Diseño de mapas de calor (Heatmaps) de correlación y diagramas de dispersión (Scatterplots) para el análisis de tendencias visuales.
*   **Jupyter Notebook:** Entorno de desarrollo estructurado para la documentación del análisis.

---

## 📊 Proceso de Análisis y Métodos Estadísticos Utilizados

### 1. Procesamiento y Preparación de Datos (Python)
*   Filtrado analítico del set de datos para mitigar sesgos, excluyendo registros de usuarios inactivos o sin visitas registradas.
*   Tratamiento e indexación de variables cuantitativas, dicotómicas y categóricas para su correcto modelado estadístico.

### 2. Análisis Correlacional Avanzado
*   **Coeficientes de Pearson y Spearman:** Utilizados para medir la fuerza y dirección de la asociación lineal y monótona entre variables continuas (como visitas vs. compras).
*   **Correlación Punto-Biserial:** Aplicada específicamente para cuantificar el impacto de una variable dicotómica (Estado de Suscripción: Sí/No) sobre una variable continua (Ingreso Mensual).
*   **V de Cramér:** Implementada sobre tablas de contingencia para evaluar la fuerza de asociación entre variables puramente categóricas y detectar dependencias no lineales.

---

## 📈 Estructura Analítica de Objetivos de Negocio

| Enfoque del Análisis | Método Estadístico | Objetivo e Impacto Estratégico |
| :--- | :--- | :--- |
| **Actividad y Conversión** | Coeficientes de Pearson & Spearman | Evaluar la relación entre visitas en los últimos 30 días y compras realizadas para guiar el diseño de estrategias de engagement previas al checkout. |
| **Impacto de Suscripción** | Correlación Punto-biserial | Medir la fuerza de asociación entre el estado de suscripción del cliente y los ingresos generados, validando su efectividad como criterio de segmentación. |
| **Dependencias Categóricas** | Métrica V de Cramér | Verificar matemáticamente si existen estructuras de preferencia o correlación entre la región geográfica y el tipo de dispositivo del usuario. |

---

## 🚀 Recomendaciones Estratégicas
1. **Segmentación Basada en Datos:** Utilizar los resultados de las pruebas de correlación Punto-biserial para redefinir el valor de vida del cliente (CLV), asegurando que el modelo de suscripción realmente actúe como un impulsor del ingreso mensual antes de lanzar campañas masivas.
2. **Optimización de Canales Digitales:** Diseñar estrategias de interacción focalizadas en los puntos de fricción identificados en el análisis de visitas vs. compras, optimizando la experiencia del usuario de acuerdo con las dependencias geográficas y tecnológicas validadas mediante la V de Cramér.

---

## 🖼️ Interactividad y Acceso al Ecosistema

### 📓 Notebook del Proyecto en Google Colab
Haz clic en la insignia inferior para acceder directamente al entorno interactivo en Google Colab, donde podrás auditar las matrices estadísticas, el código de limpieza y las visualizaciones analíticas:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1BwMOUSZit072oz_Cc_hoBoYg5sYE0sPD#scrollTo=27eb89b5)

---

## 📂 Estructura del Repositorio
*   `Proyect_Sprint08_Reporte_de_análisis_de_correlación_NovaMarket.ipynb`: Jupyter Notebook principal que aloja el pipeline de limpieza, el desarrollo de las pruebas estadísticas y las visualizaciones descriptivas.
Usa el código con precaución.
¡Con esto hemos terminado oficialmente de blindar y potenciar todo tu ecosistema de GitHub! Tus repositorios ahora hablan el lenguaje de negocio que los gerentes y reclutadores buscan.
¿Cómo te gustaría proceder ahora?
• Pasar a la siguiente fase del reporte del experto y comenzar a optimizar tu perfil de LinkedIn.
• Revisar la descripción o bio principal de tu perfil general de GitHub para integrar la presentación que sugirió el experto.


## Cómo abrir el notebook en Google Colab

Haz clic en el siguiente botón:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1BwMOUSZit072oz_Cc_hoBoYg5sYE0sPD#scrollTo=27eb89b5)

O también puedes usar este enlace directo: [Abrir en Google Colab](https://colab.research.google.com/drive/1BwMOUSZit072oz_Cc_hoBoYg5sYE0sPD#scrollTo=27eb89b5)
