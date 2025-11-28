## Título

Modelo Predictivo de Suscripción Bancaria: Clasificación de Clientes (XGBoost)

## Descripción del Proyecto

Este proyecto desarrolla un modelo de clasificación de Machine Learning para predecir si un cliente de una institución bancaria suscribirá un depósito a plazo fijo.

El análisis se basa en datos de campañas de marketing directo (llamadas telefónicas). Se utilizó el algoritmo XGBoost para manejar la complejidad de los datos y técnicas avanzadas como SMOTE para mitigar el fuerte desequilibrio de clases. El modelo final demostró una alta capacidad de generalización (AUC de 0.8914) y fue evaluado bajo un prisma de negocio (Precision vs. Recall).

## Objetivos

    Predecir si un cliente suscribirá un depósito a plazo fijo (variable y).

    Construir y optimizar un modelo de clasificación (XGBoost) para obtener métricas clave como el AUC y el F1-Score.

    Abordar el problema del desequilibrio de clases (pocos clientes suscriben) utilizando la técnica de sobremuestreo SMOTE.

    Evaluar el impacto financiero del modelo: determinar el umbral de probabilidad óptimo para equilibrar la Precision y el Recall, minimizando los Falsos Negativos (clientes que querían comprar, pero el modelo descartó).

## Herramientas o Lenguajes Utilizados

    Lenguaje: Python

    Librerías Clave de Machine Learning:

        XGBoost: Algoritmo principal de clasificación.

        Scikit-learn: Preprocesamiento, métricas de evaluación (AUC, F1-Score).

        Imblearn (SMOTE): Manejo de desequilibrio de clases.

    Librerías de Análisis: Pandas y NumPy (Manipulación de datos).

## Conjunto de Datos

    Fuente: Campañas de marketing directo de una institución bancaria portuguesa.

    Nombre del Archivo: bank-full.csv.

    Características: El conjunto de datos incluye información demográfica, atributos socioeconómicos y detalles de la campaña de marketing.

    Tamaño: Contiene más de 41,000 registros de clientes.

    Variable Objetivo: y (Indica si el cliente suscribió un depósito a plazo fijo).


