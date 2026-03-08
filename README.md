# Proyecto-Alura-Store
Análisis de datos con Python para la optimización de ventas y toma de decisiones estratégicas en Alura Store. Proyecto desarrollado para el Challenge de Alura Latam.
Alura Store - Análisis de Rendimiento y Estrategia de Ventas
📝 Descripción del Proyecto
Este proyecto consiste en un análisis de datos detallado de cuatro tiendas pertenecientes a la cadena Alura Store. El objetivo principal es asesorar al Sr. Juan en una decisión estratégica: identificar cuál de las cuatro tiendas presenta el menor desempeño para proceder con su venta e invertir el capital en un nuevo modelo de negocio.

El análisis se centra en cinco ejes clave:

Facturación Total: Identificación de la tienda con mayores y menores ingresos.

Popularidad por Categoría: Determinación de los nichos de mercado más fuertes en cada ubicación.

Satisfacción del Cliente: Análisis de las calificaciones promedio (1-5 estrellas).

Inventario y Rotación: Listado de los productos más y menos vendidos.

Eficiencia Logística: Evaluación del costo promedio de envío por tienda.

🚀 Instalación y Requisitos
Para ejecutar este análisis, se requiere un entorno de Python 3.x. El proyecto está diseñado para ser utilizado en Google Colab, pero también puede ejecutarse localmente.

Dependencias
El análisis utiliza las siguientes librerías de Python:

pandas: Para la manipulación y limpieza de datos.

matplotlib: Para la creación de visualizaciones estáticas.

seaborn: Para gráficos estadísticos avanzados.

Si trabajas de forma local, puedes instalar las dependencias con:

Bash
pip install pandas matplotlib seaborn
📂 Estructura del Repositorio
AluraStoreLatam.ipynb: Cuaderno de Jupyter/Colab con el código fuente y el informe final.

tienda_1.csv, tienda_2.csv, tienda_3.csv, tienda_4.csv: Bases de datos con el histórico de ventas de cada sucursal.

README.md: Documentación del proyecto.

📊 Metodología de Ejecución
Carga de Datos: Importación de archivos CSV mediante pandas.read_csv.

Procesamiento: Limpieza de datos y cálculos agregados (sumas, promedios y conteos).

Visualización: Generación de gráficos de barras y pasteles para facilitar la interpretación de métricas complejas.

Informe Final: Síntesis de hallazgos y recomendación final basada en evidencia.

🔍 Hallazgos Principales
Tienda 4 fue identificada como la sucursal con menor facturación total.

La Tienda 3 mantiene el estándar más alto de satisfacción al cliente.

La categoría de Muebles es el motor principal de ventas en todo el grupo Alura Store.

💡 Solución de Problemas
Error de carga de archivos: Asegúrate de que los archivos .csv estén en la misma carpeta que el cuaderno o cargados en la sesión de Google Colab antes de ejecutar las celdas de importación.

Visualización vacía: Si los gráficos no se muestran, verifica que has incluido la línea %matplotlib inline o ejecutado plt.show().

Autor: [Tu Nombre]

Curso: Ciencia de Datos con Python - Alura Latam / Oracle Next Education.
