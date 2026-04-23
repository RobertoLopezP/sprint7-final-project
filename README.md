📊 #**Proyecto ConnectaTel – Análisis de Datos de Clientes**

🧠 #**Descripción del Proyecto**

Este proyecto consiste en un análisis exploratorio y segmentación de clientes para ConnectaTel, con el objetivo de entender patrones de uso, detectar anomalías y generar recomendaciones estratégicas para la optimización de planes telefónicos.

El análisis se realizó utilizando Python en un notebook, aplicando técnicas de limpieza, exploración de datos (EDA) y análisis de comportamiento.

🎯 #**Objetivos**
Evaluar la calidad de los datos
Identificar patrones de uso en clientes
Detectar outliers y comportamientos extremos
Segmentar clientes según edad y nivel de consumo
Generar recomendaciones de negocio basadas en datos

📁 Estructura del Proyecto
📦 ConnectaTel-Analysis
 ┣ 📜 S7_Version_Estudiante_Project_ConnectaTel.ipynb
 ┣ 📜 README.md
 

 
🔍 #**Principales Hallazgos**

🧹 ##**Calidad de Datos**
No se encontraron valores nulos críticos
Datos consistentes en variables clave (edad, uso)
Presencia de asimetría en variables de consumo


📊 ##**Segmentación de Clientes**

###**Se identificaron tres segmentos principales:**

Bajo uso: consumo mínimo de llamadas y mensajes
Uso medio: comportamiento estable (mayoría de clientes)
Alto uso (power users): consumo intensivo

👥 ##**Comportamiento por Edad**
Jóvenes: mayor uso, especialmente en mensajería
Adultos: uso moderado y estable
Adultos mayores: menor consumo

🚨 ##**Outliers**
Usuarios con consumo extremadamente alto en:
Mensajes
Llamadas
Duración de llamadas
Representan <10% pero afectan significativamente el promedio


💡 ##**Insights de Negocio**
Los usuarios intensivos concentran gran parte del consumo
El segmento de uso medio es el más rentable a largo plazo
Los outliers pueden representar oportunidades o riesgos (fraude o sobreuso)


🚀 ##**Recomendaciones**
Crear planes diferenciados:
Básico (bajo uso)
Estándar (uso medio)
Premium (alto uso)
Implementar:
Estrategias de upselling
Monitoreo de anomalías
Segmentación avanzada de clientes


🛠️ ##**Tecnologías Utilizadas**
Python 🐍
Pandas
NumPy
Matplotlib / Seaborn
Jupyter Notebook


📈 ##**Posibles Mejoras**
Modelos de predicción de churn
Clustering avanzado (K-Means, DBSCAN)
Análisis de ingresos por cliente (ARPU)
Dashboards interactivos (Power BI / Tableau)

👨‍💼 ##**Autor**
Roberto Eduardo López Padilla

**Proyecto desarrollado como parte de un análisis de datos aplicado a negocio.**

**Este proyecto es de uso educativo y puede ser reutilizado con fines de aprendizaje.**
