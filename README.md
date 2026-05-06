# 🎓 Sistema de Alerta Temprana para la Deserción Estudiantil

## Universidad Continental - Construcción de Software - Grupo D

---

## 🏛️ Sobre el Grupo

**Universidad Continental · Ingeniería de Sistemas e Informática · NRC 23176**

El **Grupo D** está conformado por cinco estudiantes de la Universidad Continental, institución reconocida por su excelencia académica y su enfoque en la formación de profesionales con sólida preparación tecnológica, pensamiento crítico y compromiso con el desarrollo del país.

En el marco del curso de **Construcción de Software (NRC 23176)**, este equipo asume el desafío de aplicar metodologías ágiles, herramientas modernas y buenas prácticas de ingeniería de software para desarrollar soluciones robustas, escalables y centradas en el usuario. El grupo trabaja de manera colaborativa, integrando los conocimientos adquiridos a lo largo de su formación académica, con el objetivo de construir software funcional, mantenible y rigurosamente documentado.

> *"La Universidad Continental forma profesionales con visión global, compromiso ético y capacidad de innovación — valores que el Grupo D traslada al aula, a cada línea de código y a cada decisión técnica."*

Este repositorio representa el trabajo conjunto del equipo, abarcando desde la planificación estratégica y el diseño arquitectónico hasta la implementación, pruebas y documentación, reflejando el ciclo de vida completo del desarrollo de software con rigor académico y profesional.

---

## 👥 Integrantes del Grupo D

| # | Estudiante | Rol | Contacto |
|---|------------|-----|----------|
| 1 | **Fabrizio Yair Aguilar Vargas** | 🎓 Estudiante de Ingeniería de Sistemas | [GitHub](https://github.com/) |
| 2 | **Mariano Jhoshua Laura Paz** | 🎓 Estudiante de Ingeniería de Sistemas | [GitHub](https://github.com/) |
| 3 | **Maykol Rocca Puma** | 🎓 Estudiante de Ingeniería de Sistemas | [GitHub](https://github.com/) |
| 4 | **Fray Salcedo Ramos** | 🎓 Estudiante de Ingeniería de Sistemas | [GitHub](https://github.com/) |
| 5 | **Liz Eliana Vargas Rojas** | 🎓 Estudiante de Ingeniería de Sistemas | [GitHub](https://github.com/) |

---

## 📌 Descripción del Proyecto

Este proyecto desarrolla un **modelo de Machine Learning** (Red Neuronal MLP) capaz de predecir el riesgo de deserción estudiantil durante el primer año académico. El sistema permite a la **Universidad Continental** intervenir de forma proactiva con planes de acompañamiento personalizados.

**Objetivo:** Clasificar estudiantes en "riesgo de deserción" vs. "sin riesgo", priorizando la detección temprana para reducir la tasa de abandono actual del **15%** en el primer ciclo.

---
## 📁 Estructura del Proyecto

```bash
Desercion_Estudiantil/
│
├── app.py                  # Aplicación web con Streamlit
├── Parcial_Colab.ipynb     # Notebook de entrenamiento
├── modelo_mlp.h5           # Modelo MLP entrenado
├── escalador.pkl           # StandardScaler para normalizar
├── features_names.pkl      # 39 características del modelo
├── dataset.csv             # Dataset original (UCI #697)
├── requirements.txt        # Dependencias del proyecto
└── README.md               # Este documento

📦 Paso  Instalar dependencias
Abre la terminal (CMD, PowerShell o Git Bash) en la carpeta del proyecto y ejecuta:

pip install -r requirements.txt


streamlit run app.py

https://prediccion-desercion-jcvyfrmtpvqogzu7ctizvu.streamlit.app/ 
