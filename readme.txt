🤖 Robot de Trading Basado en Desviación Estándar
Este es un Jupyter Notebook (Standard_Deviation_Trading_Bot.ipynb) diseñado para realizar análisis técnico y generar señales de trading automáticas basadas principalmente en la Desviación Estándar y el Índice de Fuerza Relativa (RSI).
El bot utiliza datos históricos de acciones para simular una estrategia de trading, graficar los resultados y evaluar el rendimiento.
🌟 Características
* Descarga de Datos: Obtiene datos de precios de acciones directamente a través de yfinance.
* Análisis Técnico: Calcula indicadores clave como Desviación Estándar, Bandas de Bollinger (implícitas) y RSI.
* Generación de Señales: Implementa una lógica de trading simple para generar señales de Compra (BUY) o Venta (SELL).
* Backtesting Básico: Simula el rendimiento de la estrategia a lo largo del tiempo.
* Visualización: Genera gráficos claros de los precios de cierre y las señales de trading.
🛠️ Requisitos
Para ejecutar este programa, necesitarás tener instalado Python (preferiblemente Python 3.x) y las siguientes librerías:
pip install yfinance pandas numpy matplotlib

🚀 Uso e Instalación
1. Clona o Descarga el Repositorio
git clone [https://github.com/pmonsivaisrviera08/nombre-del-repositorio.git](https://github.com/pmonsivaisrviera08/nombre-del-repositorio.git)
cd nombre-del-repositorio

(Nota: Reemplaza nombre-del-repositorio con el nombre real de tu repositorio en GitHub.)
2. Abre el Notebook
Inicia Jupyter Notebook o JupyterLab y abre el archivo Standard_Deviation_Trading_Bot.ipynb.
3. Configuración de Parámetros
Dentro de las primeras celdas del notebook, puedes modificar fácilmente los siguientes parámetros:
   * ticker: Símbolo bursátil de la acción (ej: 'AAPL', 'GOOG').
   * start_date: Fecha de inicio del análisis (formato 'AAAA-MM-DD').
   * end_date: Fecha de fin del análisis (formato 'AAAA-MM-DD').
   * window_val: Período para el cálculo de la Desviación Estándar y el RSI (generalmente 20 o 14).
   4. Ejecución
Ejecuta todas las celdas del notebook en orden para descargar los datos, calcular los indicadores, generar las señales y visualizar los resultados del backtesting.
🛑 Propiedad y Licencia
Propiedad: Este programa es una creación original y es propiedad total y exclusiva de su autor, pmonsivaisrviera08.
Licencia: Este software no tiene ninguna licencia de código abierto (Open Source). Queda prohibida la copia, distribución, modificación o uso comercial de este código sin el permiso explícito y por escrito del propietario.