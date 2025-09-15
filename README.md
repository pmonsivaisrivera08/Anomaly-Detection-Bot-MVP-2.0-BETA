Anomaly Detection Bot MVP 2.0

This project is an anomaly detection bot for financial data built in Python. Its goal is to analyze time series (e.g., stock prices) and detect unusual behaviors using statistical and machine learning techniques.

Key Features

Historical data download with yfinance.

Automatic data cleaning and preprocessing.

Implementation of anomaly detection algorithms.

Interactive menu that guides the user step by step.

Important Note ⚠️

There is currently a small issue with the menu flow:

If the user selects "Yes" when asked to display the DataFrame, the program gets stuck and does not move on to the next question.

If the user selects "No", the program continues normally.

👉 Temporary recommendation: for smoother usage, please select "No" when asked to display the DataFrame until this part of the code is fixed.

Next Improvements

Fix the menu flow so the program continues even after displaying the DataFrame.

Improve the interaction to make it more user-friendly.

Add additional visualizations for detected anomalies.
____________________________________________
Bot de Detección de Anomalías MVP 2.0

Este proyecto es un bot de detección de anomalías en datos financieros desarrollado en Python. Su objetivo es analizar series temporales (por ejemplo, precios de acciones) y detectar comportamientos fuera de lo común utilizando técnicas estadísticas y de machine learning.

Características principales

Descarga de datos históricos con yfinance.

Limpieza y preprocesamiento automático de la información.

Implementación de algoritmos de detección de anomalías.

Menú interactivo que permite al usuario elegir las acciones a realizar paso por paso.

Nota importante ⚠️

Actualmente, existe un detalle en el flujo del menú:

Si el usuario selecciona "Sí" cuando se le pregunta si quiere mostrar el DataFrame, el programa se queda atorado y no avanza a la siguiente pregunta.

En cambio, si selecciona "No", el flujo continúa normalmente.

👉 Recomendación temporal: para un mejor uso del bot, evita mostrar el DataFrame desde el menú y selecciona "No" hasta que se optimice esa parte del código.

Próximas mejoras

Corregir el flujo del menú para que el programa continúe después de mostrar el DataFrame.

Optimizar la interacción para hacerla más fluida y amigable.

Incluir visualizaciones adicionales de las anomalías detectadas.
