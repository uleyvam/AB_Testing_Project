# Proyecto de Prueba A/B - Optimización de Ingresos

Este proyecto forma parte de mi portafolio en análisis de datos.  
El objetivo fue **priorizar hipótesis de negocio y evaluar los resultados de una prueba A/B** para ayudar a la empresa a tomar decisiones fundamentadas sobre una nueva versión del sitio web.

---

## 🚀 Objetivo del proyecto
1. **Priorización de hipótesis:**  
   - Aplicación de los frameworks **ICE** y **RICE** para ordenar hipótesis de marketing según impacto, confianza, esfuerzo y alcance.  
   - Comparación de cómo cambia el ranking de hipótesis al incluir el factor *Reach*.  

2. **Análisis de prueba A/B:**  
   - Evaluación del impacto de la nueva versión del sitio (grupo B) frente a la versión actual (grupo A).  
   - Comparación en métricas clave: ingresos acumulados, tasa de conversión y tamaño promedio de pedido.  
   - Aplicación de pruebas estadísticas para validar la significancia de los resultados.  

---

## 📂 Datos utilizados
- **Hypotheses dataset** → hipótesis de negocio con métricas ICE y RICE.  
- **Orders dataset** → registros de pedidos de clientes (transactionId, revenue, group).  
- **Visits dataset** → visitas diarias por grupo de prueba (A y B).  

---

## 🛠️ Herramientas y tecnologías
- Python (pandas, numpy, scipy, matplotlib)  
- Jupyter Notebook  
- Pruebas estadísticas: Mann–Whitney U  
- Visualización de datos  

---

## 📈 Principales hallazgos
- 📌 El framework **RICE** permitió identificar hipótesis con mayor alcance potencial, como agregar formularios de suscripción y recomendaciones de productos.  
- 📌 El grupo **B mostró una tasa de conversión significativamente mayor** (+15.3% después de filtrar outliers, p < 0.05).  
- 📌 No se encontraron diferencias significativas en el tamaño promedio de los pedidos entre los grupos.  
- 📌 Los ingresos acumulados y la tasa de conversión favorecieron consistentemente al grupo B.  

---

## ✅ Decisión final
- **Detener la prueba A/B** y considerar al **grupo B como líder**, ya que mostró mejoras estadísticamente significativas en la conversión sin efectos negativos en el tamaño promedio de los pedidos.  
- Este resultado respalda la implementación de la nueva versión del sitio.  

---

## 📄 Archivos en este repositorio
- `AB_Test.ipynb` → Notebook con el análisis completo.  
- `AB_Test.pdf` → Versión en PDF del notebook.  

---

## 👤 Autor
**Victor Uriel Leyva**  
Analista de Datos Jr.  
[LinkedIn](www.linkedin.com/in/victorurielleyva) | [GitHub](https://github.com/uleyvam)  

---
