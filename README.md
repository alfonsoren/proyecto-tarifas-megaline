# proyecto-tarifas-megaline
# Análisis de Tarifas de Telecomunicaciones: Surf vs. Ultimate 📞📊

Este proyecto analiza el comportamiento de los clientes de **Megaline**, un operador de telecomunicaciones, para determinar cuál de sus dos tarifas de prepago —**Surf** o **Ultimate**— genera mayores ingresos. El análisis está diseñado para ayudar al departamento comercial de Megaline a tomar decisiones sobre publicidad y estrategias de marketing.

## ❓ Pregunta de Investigación

**¿Cuál tarifa de prepago, Surf o Ultimate, genera más ingresos para Megaline?**

## 🗂️ Datos Utilizados

- `megaline_calls.csv`: Datos de llamadas (duración, fecha y hora).
- `megaline_internet.csv`: Datos de uso de internet (MB consumidos).
- `megaline_messages.csv`: Datos de mensajes de texto enviados.
- `megaline_tariffs.csv`: Detalles de las tarifas Surf y Ultimate.
- `megaline_users.csv`: Información de clientes (nombre, ubicación, tarifa).

## 🔍 Pasos del Análisis

1. **Carga y preprocesamiento de datos**
   - Limpieza y transformación de los datos.
   - Conversión de formatos y manejo de valores nulos.

2. **Cálculo de métricas por usuario y mes**
   - Minutos utilizados, mensajes enviados y datos en GB.
   - Redondeo según política de cobro de Megaline.

3. **Cálculo de ingresos mensuales**
   - Suma de costos fijos y variables según consumo.

4. **Análisis del comportamiento del cliente**
   - Distribuciones y promedios de uso por tarifa.
   - Visualizaciones con histogramas y boxplots.

5. **Comparación de ingresos por tarifa**
   - Ingresos mensuales promedio.
   - Prueba t de Student para comparar tarifas.

6. **Conclusiones y recomendaciones**
   - Resumen de hallazgos y sugerencias para la empresa.

## 📈 Tecnologías Usadas

- Python
- Pandas
- Matplotlib
- Seaborn
- SciPy

## ⚙️ Cómo Ejecutar el Proyecto

1. Clona este repositorio:
   ```bash
   git clone https://github.com/tuusuario/proyecto-tarifas-megaline.git
