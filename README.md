# DataScience_Fraud
# Proyecto Final: Análisis Exploratorio de Transacciones Financieras en Línea

Prof. : David Palacio Jiménez

Est. : Eloisa Cardona Botero - Simón Callejas Pérez - Luisa Fernanda Escobar Gutiérrez

## Descripción del proyecto  
El proyecto final del curso consiste en desarrollar un **análisis exploratorio exhaustivo** de un dataset que contiene información de transacciones financieras en línea.  

En este conjunto de datos se registran detalles como:  
- El monto de la transacción  
- Los saldos previos y posteriores a la operación  
- La detección de transacciones fraudulentas  

Este escenario simulado corresponde al entorno operativo de una **entidad financiera o sistema de pagos en línea**, lo cual lo convierte en un caso de estudio ideal para abordar temas de **seguridad y detección de fraudes**.  

---

## Problema a Abordar  
El objetivo principal es **identificar patrones** que permitan diferenciar entre transacciones legítimas y fraudulentas.  
Además, se plantea el desarrollo de un **modelo predictivo** basado en las variables del dataset, que ayude a predecir la probabilidad de que una transacción sea fraudulenta.  

---

## Descripción de las Variables  

- **step**: Unidad de tiempo (1 step equivale a 1 hora).  
- **type**: Tipo de transacción en línea.  
- **amount**: Monto de la transacción.  
- **nameOrig**: Cliente que inicia la transacción.  
- **oldbalanceOrg**: Saldo del cliente antes de la transacción.  
- **newbalanceOrig**: Saldo del cliente después de la transacción.  
- **nameDest**: Destinatario de la transacción.  
- **oldbalanceDest**: Saldo inicial del destinatario antes de la transacción.  
- **newbalanceDest**: Nuevo saldo del destinatario después de la transacción.  
- **isFraud**: Indicador de transacción fraudulenta (1 = fraudulenta).  
- **isFlaggedFraud**: Indicador de transacción marcada por un sistema de alerta.  

---

## Entregables del Proyecto  

1. **Análisis Inicial**  
   - Identificación del tipo de datos  
   - Cantidad de registros  
   - Análisis de relaciones entre variables  

2. **Visualizaciones**  
   - Histogramas  
   - Gráficos de barras  
   - Series temporales (aprovechando la variable `step`)  

3. **Preprocesamiento**  
   - Limpieza y transformación de datos  
   - Tratamiento de valores nulos o inconsistentes  

4. **Análisis Avanzado**  
   - Matrices de correlación  
   - Gráficos interactivos para extraer información relevante  

5. **Conclusiones**  
   - Síntesis final de hallazgos  

---

## Nota Adicional  
Aunque el enfoque principal es el **análisis exploratorio**, se valorará positivamente el desarrollo de un **modelo predictivo** para la detección de transacciones fraudulentas, dado que se trata de un problema de **clasificación**.  

Se espera que el trabajo haga uso de las librerías vistas en el curso, tales como:  
- **NumPy**  
- **Pandas**  
- **Polars**  
- **SciPy**  
- **Plotly**  
- **Seaborn**  
entre otras.  
