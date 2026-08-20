# 🐾 ZooPlot AI: Visualización y Regresión Polinómica de Patrones Animales

**ZooPlot AI** es una plataforma interactiva que aplica modelos de **Regresión Polinómica** para graficar, analizar y predecir relaciones no lineales en el comportamiento animal y dinámicas de ecosistemas.

---

## 🎯 Objetivo

Demostrar la superioridad de las funciones polinómicas frente a la regresión lineal simple al representar puntos de saturación, curvas de rendimiento y patrones metabólicos en datos biológicos.

---

## 🚀 Arquitectura

* **Machine Learning:** Scikit-learn (`PolynomialFeatures`, `LinearRegression`).
* **Backend:** FastAPI para servir el modelo de inferencia en tiempo real (`POST /predict`).
* **Frontend:** Streamlit para la manipulación interactiva de variables y renderizado gráfico.
* **Contenedorización:** Docker & Docker Compose.

---

## 🛠️ Instalación Rápida

```bash
# Clonar repositorio
git clone [https://github.com/tu-usuario/zooplot-ai.git](https://github.com/tu-usuario/zooplot-ai.git)
cd zooplot-ai

# Ejecutar con Docker
docker-compose up --build
