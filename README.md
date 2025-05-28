# Proyecto de Predicción de Cancelación de Clientes

![Análisis de datos](https://cdn-icons-png.flaticon.com/512/1170/1170576.png)

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

Entrenar los modelos Random Forest y XGBoost.

Evaluar resultados con métricas como accuracy, precision, recall, f1-score y ROC AUC.

Visualizar la importancia de variables con gráficos.

---
# 📊 Resultados Obtenidos

Random Forest alcanzó un accuracy aproximado del 56% y un f1-score balanceado.

XGBoost mostró métricas similares con un ROC AUC cercano a 0.52.

Variables como Cargo_mensual, Antigüedad_meses y Tiene_dependientes son clave para la predicción.
---
# 📈 Mejoras Futuras

⚙️Optimización de hiperparámetros con técnicas avanzadas.

🧪 Experimentar con otros modelos (SVM, Redes Neuronales).

🔄 Implementar pipelines para automatizar el flujo completo.

---

# ✉️ Contacto
¡No dudes en contactarme para cualquier pregunta o colaboración!

📧 [Correo](mailto:angeltroncoso2019@outlook.es)  
🔗 [LinkedIn](https://www.linkedin.com/in/angel-troncoso)  
🐦 [Twitter](https://twitter.com/angeltroncoso)  
💼 [GitHub](https://github.com/angeltroncoso)  

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

