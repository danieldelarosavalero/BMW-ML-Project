# 🚗 BMW Price Prediction - Machine Learning Project

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone)

Proyecto completo de Machine Learning para predicción de precios de vehículos BMW convertido a HTML estático para despliegue en Vercel.

## 🌟 Características del Proyecto

- ✅ **Dataset:** 10,781 vehículos BMW (1996-2020)
- ✅ **Algoritmos:** 6 modelos comparados (XGBoost, Random Forest, Neural Network, SVR, Ridge, Lineal)
- ✅ **Mejor Modelo:** XGBoost con R² = 0.88
- ✅ **Precisión:** Error promedio de £1,650 (7.2%)
- ✅ **Pruebas:** Suite de 7 pruebas automáticas (100% éxito)

## 🚀 Ver el Proyecto Online

**Demo en vivo:** [https://tu-proyecto.vercel.app](https://vercel.com)

## 📦 Archivos del Proyecto

```
bmw-ml-vercel/
├── index.html          # Notebook convertido a HTML
├── vercel.json         # Configuración de Vercel
├── README.md           # Este archivo
└── .gitignore          # Archivos a ignorar
```

## 🛠️ Desplegar en Vercel

### Opción 1: Desde GitHub (Recomendado)

1. **Sube estos archivos a un repositorio de GitHub**
   ```bash
   git init
   git add .
   git commit -m "Initial commit: BMW ML Project"
   git branch -M main
   git remote add origin https://github.com/TU-USUARIO/bmw-ml-vercel.git
   git push -u origin main
   ```

2. **Conecta con Vercel**
   - Ve a [vercel.com](https://vercel.com)
   - Click en "New Project"
   - Importa tu repositorio de GitHub
   - Click en "Deploy"

3. **¡Listo!** Tu proyecto estará en: `https://tu-proyecto.vercel.app`

### Opción 2: Vercel CLI

```bash
# Instalar Vercel CLI
npm install -g vercel

# Navegar a la carpeta del proyecto
cd bmw-ml-vercel

# Desplegar
vercel

# Seguir las instrucciones en pantalla
```

### Opción 3: Drag & Drop

1. Ve a [vercel.com/new](https://vercel.com/new)
2. Arrastra la carpeta completa
3. Click en "Deploy"

## 📊 Contenido del Notebook

El proyecto incluye:

### 1. Marco Teórico del Machine Learning
- Fundamentos de ML
- Tipos de aprendizaje
- Taxonomía de algoritmos

### 2. Análisis Exploratorio de Datos (EDA)
- Dataset de 10,781 vehículos
- Análisis de variables
- Visualizaciones
- Correlaciones

### 3. Preparación de Datos
- Feature Engineering (6 nuevas variables)
- Encoding de categóricas
- Train/Test split (80/20)
- Escalado de variables

### 4. Modelado
- **6 Algoritmos Implementados:**
  1. Regresión Lineal (baseline)
  2. Ridge Regression
  3. Random Forest
  4. XGBoost ⭐ (mejor)
  5. SVR (RBF kernel)
  6. Neural Network (MLP)

### 5. Evaluación y Resultados
| Modelo | R² Score | MAE (£) | RMSE (£) |
|--------|----------|---------|----------|
| **XGBoost** 🥇 | **0.88** | **1,650** | **2,200** |
| Random Forest 🥈 | 0.85 | 1,850 | 2,450 |
| Neural Network 🥉 | 0.82 | 2,000 | 2,650 |
| SVR | 0.80 | 2,150 | 2,800 |
| Ridge | 0.75 | 2,400 | 3,100 |
| Lineal | 0.72 | 2,550 | 3,300 |

### 6. Pruebas Automáticas
- Suite de 7 pruebas implementadas
- 100% de pruebas pasadas

## 🎯 Objetivos Alcanzados

- ✅ R² Score > 0.85 (Logrado: 0.88)
- ✅ RMSE < £2,500 (Logrado: £2,200)
- ✅ MAE < £2,000 (Logrado: £1,650)
- ✅ Velocidad < 100ms (Logrado: 45ms)

## 🛠️ Tecnologías Utilizadas

- **Python 3.8+**
- **Jupyter Notebook**
- **scikit-learn** - Modelos ML
- **XGBoost** - Gradient Boosting
- **pandas** - Manipulación de datos
- **numpy** - Cálculos numéricos
- **matplotlib/seaborn** - Visualizaciones

## 📈 Insights Principales

1. **Features más importantes:**
   - year (+0.49 correlación)
   - mileage (-0.47 correlación)
   - model (target encoding)

2. **Depreciación promedio:** ~£3,000/año

3. **Premium por transmisión automática:** ~£4,000

4. **Modelos más comunes:**
   - Serie 3: 24%
   - Serie 1: 16%
   - Serie 5: 15%

## 👨‍💻 Autor

**Rabindranath Andujar**

- Proyecto: Unit 25 - Applied Machine Learning
- Institución: PEARSON HND - Computer Science & AI
- Año: 2024-2025

## 📄 Licencia

Este proyecto es parte de un trabajo académico para PEARSON HND.

## 🙏 Agradecimientos

- Dataset: Kaggle - Used Car Dataset
- Framework: Jupyter Notebook
- Algoritmos: scikit-learn y XGBoost

---

## 📞 Soporte

Si tienes problemas con el despliegue:

1. Verifica que todos los archivos estén en la carpeta
2. Asegúrate de que `index.html` esté en la raíz
3. Revisa la documentación de Vercel: [docs.vercel.com](https://vercel.com/docs)

---

**⭐ Si te gusta este proyecto, dale una estrella en GitHub!**

**🚀 Deploy to Vercel:** [vercel.com/new](https://vercel.com/new)
