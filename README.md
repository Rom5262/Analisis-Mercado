
# 📝 Análisis de Hipótesis y Test A/B para una Tienda Online

## Descripción del Proyecto

Este proyecto se enfoca en el análisis de datos para una tienda online, con el objetivo de aumentar los ingresos. El trabajo se divide en dos partes principales:

1.  **Priorización de Hipótesis:** Se evalúan y priorizan nueve hipótesis para aumentar los ingresos utilizando los frameworks **ICE** y **RICE**.
2.  **Análisis de Test A/B:** Se realiza un análisis de los resultados de un test A/B para determinar si un nuevo enfoque (Grupo B) es más efectivo que el actual (Grupo A) en términos de ingresos y conversión.

El análisis de datos incluye preprocesamiento, visualización de métricas acumuladas, identificación de anomalías y la aplicación de pruebas de significancia estadística para tomar una decisión informada sobre el resultado del test.

---

## Tecnologías Utilizadas

-   **Python**
-   **Pandas:** Para la manipulación y análisis de datos.
-   **NumPy:** Para operaciones numéricas.
-   **Matplotlib / Seaborn:** Para la visualización de datos.
-   **SciPy:** Para las pruebas de significancia estadística.

---

### 📊 Conclusiones y Resultados Clave

#### 💰 Diferencia en el Tamaño de Pedido (Ingresos)
* **Conclusión:** No se encontró una diferencia estadísticamente significativa en el tamaño promedio de los pedidos entre ambos grupos.
* **Valor P:** [Aquí va el valor p de la prueba Mann-Whitney U para revenue]

#### 🛒 Diferencia en el Número de Pedidos por Usuario (Conversión)
* **Conclusión:** Se encontró una diferencia estadísticamente significativa. El Grupo B realizó un **13.8%** más de pedidos en promedio que el Grupo A.
* **Valor P:** Con un valor de 0.017, que es menor al nivel de significancia de 0.05, podemos afirmar que la diferencia en el número de pedidos por usuario entre los grupos es estadísticamente significativa. 
Esto sugiere que la estrategia implementada fue efectiva y tuvo un impacto positivo en la tasa de pedidos

---

### 🚀 Recomendación Final

Basado en los resultados, la mejor decisión es **continuar la prueba durante un período de tiempo adicional**. Esto nos permitirá recopilar más datos, lo que podría confirmar de manera más sólida la superioridad de uno de los grupos y validar si la diferencia en el número de pedidos se mantiene a largo plazo.

## Autor

-   **Nombre:** Rom5262
