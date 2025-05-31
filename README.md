 #                                                    Proyecto: Predicción de Cancelación de Servicios

![Análisis de datos](https://image.lexica.art/full_webp/7b3d9d65-32a9-4468-bded-d1c2926f77da)

# 🧠 Descripción

Este proyecto utiliza Machine Learning para predecir la probabilidad de que un cliente cancele su servicio. Se emplean modelos de **Random Forest** y **XGBoost** para analizar múltiples variables demográficas y de comportamiento.

- **ETL (Extract, Transform, Load):** Limpieza y preparación de datos desde múltiples fuentes.
- **EDA (Exploratory Data Analysis):** Análisis exploratorio para entender patrones y relaciones en los datos.
- **Machine Learning:** Modelos predictivos (Random Forest, XGBoost) para predecir la probabilidad de cancelación y ayudar a la toma de decisiones.

---

# 🛠️ Variables principales

- `Cancelado` (variable objetivo)
- `Tiene_dependientes`
- `Protección_dispositivos`
- `Servicio_telefonía`
- `Tiene_pareja`
- `Factura_sin_papel`
- `Cargo_mensual`
- `Antigüedad_meses`
- ...y otras variables relevantes de comportamiento y facturación.

---

# 📂 Estructura del proyecto

- `data/` - Datos de entrada.
- `notebooks/` - Análisis exploratorio, entrenamiento y evaluación.
- `models/` - Modelos entrenados.
- `scripts/` - Código de procesamiento y modelado.
- `README.md` - Este archivo.

---

# 🔑 Requisitos

Python 3.8+ con librerías:

```bash
pip install pandas scikit-learn xgboost matplotlib seaborn
```
---

# 🚀 Uso del Proyecto
Cargar y limpiar los datos.

Transformar Datos en Insights de valor .

Evaluar resultados con métricas Estadisticas.

Visualizar la importancia de variables con gráficos.

---
# 📊 Resultados Obtenidos

 Variables mas correlacionadas: 

  Tipo_contrato        -0.396713  
  Antigüedad_meses     -0.352229  
  Seguridad_en_línea   -0.289309   
  Soporte_técnico      -0.282492  
  Cargo_total          -0.199484  
  
---
# 📈 Mejoras Futuras

 🚀 Diseñar campañas de retención dirigidas a nuevos clientes (0–6 meses).
 
 📈 Ofrecer beneficios adicionales o descuentos para contratos de mayor duración.
 
 🗝️ Mejorar la experiencia de soporte técnico y la percepción de seguridad digital.
 
 🎯 Monitorear y segmentar a los clientes con cargos altos, ofreciendo planes ajustados a su uso.

---
# 📄 Licencia  

  Este proyecto está bajo la Licencia MIT. Puedes consultar el archivo LICENSE para más detalles.

---

# 🤝 Contribuciones
¡Tu contribución es muy bienvenida! Si te gustaría mejorar este proyecto, puedes:

- Forkear el repositorio.
- Crear una nueva rama (git checkout -b feature/AmazingFeature).
- Realizar tus cambios y commitarlos (git commit -m 'Add some AmazingFeature').

- Hacer push a la rama (git push origin feature/AmazingFeature).
- Abrir un Pull Request.

  **¡Agradecemos de antemano tu colaboración!**
  
---

# ✉️ Contacto
¡No dudes en contactarme para cualquier pregunta o colaboración!

📧 [Correo](mailto:angeltroncoso2019@outlook.es)  
🔗 [LinkedIn](https://www.linkedin.com/in/angeltroncoso)  
🐦 [Twitter](https://twitter.com/angeltronc26452)  
💼 [GitHub](https://github.com/angeltroncoso)  

---
