# Análisis para decidir qué tienda vender - *Alura Store*

![Portada del proyecto](https://www.loquequierasya.com/wp-content/uploads/2012/09/aumentar-ventas.jpg)

---

## 📘 Índice
1. [Descripción del Proyecto](#descripción-del-proyecto)  
2. [Estado del Proyecto](#estado-del-proyecto)  
3. [Demostración de funciones y resultados](#demostración-de-funciones-y-resultados)  
4. [Acceso al Proyecto](#acceso-al-proyecto)  
5. [Tecnologías Utilizadas](#tecnologías-utilizadas)  
6. [Análisis y Recomendación Final](#análisis-y-recomendación-final)  
7. [Personas Desarrolladoras del Proyecto](#personas-desarrolladoras-del-proyecto)  
8. [Licencia](#licencia)  

---

## Descripción del Proyecto
El Sr. Juan busca decidir qué tienda de su cadena **Alura Store** debería vender para iniciar un nuevo emprendimiento.  
Se analizan datos de ventas, ingresos, costos de envío y calificaciones de las **cuatro tiendas** para identificar la mejor opción de venta.  
El objetivo principal es ofrecer una **recomendación basada en datos**, considerando rendimiento financiero, satisfacción del cliente y potencial de crecimiento.

---

## Estado del Proyecto
**Terminado** – El análisis y las visualizaciones fueron completados exitosamente.

---

## Demostración de funciones y resultados
- Integración de los datos de las cuatro tiendas desde archivos CSV.  
- Análisis de ingresos totales, ventas por categoría, calificación promedio y productos más y menos vendidos.  
- Visualizaciones interactivas con **Plotly**: gráficos de barras, cajas y mapa geográfico.  
- Informe final con conclusiones estratégicas para la toma de decisiones.

---

## Acceso al Proyecto
Puedes ejecutar el análisis en **Google Colab** o localmente con Jupyter Notebook.  
Los datos se cargan automáticamente desde el repositorio original de Alura Latam.  
```python
import plotly.express as px
import pandas as pd
```

---

##  Tecnologías Utilizadas
- **Python 3.12**  
- **Plotly Express** – visualizaciones interactivas  
- **Pandas** – análisis y manejo de datos  
- **Jupyter Notebook / Colab** – entorno de ejecución  

---

## Análisis y Recomendación Final
Tras evaluar ingresos, ventas, calificaciones y costos de envío:

- **Tienda 1**: presenta los mayores ingresos y volumen de ventas, siendo el activo más valioso. Sin embargo, posee **altos costos de envío y menor satisfacción del cliente**, lo que puede afectar su rentabilidad futura.  
- **Tienda 4**: destaca por sus **bajos costos de envío** y potencial de crecimiento en mercados sensibles al precio, especialmente en Bogotá.  

 **Conclusión**: se recomienda **vender la Tienda 1** aprovechando su alta valorización actual y **fortalecer la Tienda 4** como estrategia sostenible de expansión.

---

## 👩‍💻 Personas Desarrolladoras del Proyecto
**Cyndi Nayeli Silva Abanto**  
[🔗 LinkedIn](https://www.linkedin.com/in/cyndi-nayeli-silva-abanto)

---

## Licencia
Este proyecto se encuentra bajo la licencia **MIT**, por lo que puede ser usado y modificado libremente con fines educativos y de análisis.
