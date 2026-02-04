# Venta-de-camiones
Predicción de Ventas de Camiones utilizando ARIMA y SARIMAX

Se buscó desarrollar un modelo que prediga con precisión las ventas de camiones en base a datos históricos, identificando tendencias y patrones estacionales.
Herramientas aplicadas: python, pandas, seaborn, statsmodels, matplotlib, calendar, itertools y sys.
**Análisis exploratorio:**
Visualicé correlaciones y patrones estacionales con seaborn, matplotlib y análisis calendario (calendar).
**Pruebas estadísticas:**
Evalué la estacionariedad con la prueba ADF (adfuller) y determiné órdenes del modelo usando plot_acf y plot_pacf.
**Modelado predictivo:**
Desarrollé modelos ARIMA y SARIMAX con optimización de parámetros para capturar componentes estacionales y no estacionales.
**Evaluación y visualización:**
Validé el rendimiento con métricas de error predictivo y generé reportes visuales claros para la toma de decisiones.

***Resultado:***
Generé predicciones confiables con representaciones gráficas intuitivas, ayudando a identificar picos de demanda y optimizar la logística.

# Análisis de rentabilidad en la venta de camiones

Este proyecto analiza distintos **escenarios de venta de camiones** con el objetivo de **maximizar la ganancia total**, considerando precios de venta, costos de producción y volúmenes vendidos.

El análisis permite evaluar decisiones comerciales desde una perspectiva **data-driven**, simulando distintos precios y cantidades.

---

## 🚚 Contexto del negocio

Una empresa dedicada a la venta de camiones necesita definir:
- precios de venta competitivos
- volúmenes óptimos de comercialización
- impacto de los costos en la rentabilidad

Este proyecto modela el problema para **comparar escenarios de negocio** y apoyar la toma de decisiones estratégicas.

---

## 🎯 Objetivos

- Calcular ingresos, costos y ganancias
- Comparar ganancias bajo distintos escenarios
- Analizar cómo varía la rentabilidad según el precio de venta
- Identificar el escenario más rentable

---

## 📊 Supuestos del modelo

- Se consideran precios de venta fijos por escenario
- El costo de producción por camión es constante
- El volumen de ventas depende del escenario evaluado
- No se incluyen impuestos ni costos financieros

Estos supuestos permiten **simplificar el análisis** y centrarse en la comparación relativa de escenarios.

---

## 🧮 Metodología

Para cada escenario se calcula:

- **Ingresos:**  
  `precio de venta × cantidad vendida`

- **Costos:**  
  `costo unitario × cantidad vendida`

- **Ganancia:**  
  `ingresos − costos`

Los resultados se comparan para determinar el escenario óptimo.

---

## 📌 Resultados principales

- Se identifican escenarios con ganancia positiva y negativa
- El aumento del precio de venta no siempre implica mayor ganancia
- Existe un punto donde el volumen vendido compensa un menor precio
- El análisis permite seleccionar el precio más conveniente

---

## 🛠️ Tecnologías utilizadas

- **Python**
- Estructuras básicas de programación
- Cálculos matemáticos y simulación simple

---

## 📂 Estructura del repositorio

├── venta_camiones.py
├── README.md


---

## 🚀 Próximos pasos

- Incorporar análisis de sensibilidad
- Simular escenarios con demanda variable
- Visualizar resultados con gráficos
- Añadir costos fijos y variables
- Extender el modelo a otros productos

---

## 👤 Autor

**Flavia Hepp**  
Data Analyst / Business Analytics en formación  
