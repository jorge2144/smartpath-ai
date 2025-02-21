# 📚 Optimización de la Oferta Académica mediante Predicción de Demanda de Cursos

## 🚀 Descripción del Proyecto
Este proyecto tiene como objetivo **optimizar la oferta de cursos en instituciones de educación superior** mediante **predicción de demanda basada en datos históricos y modelos de Machine Learning**. Busca mejorar la planificación académica, reducir la subutilización de recursos y minimizar la falta de cupos para estudiantes.

## 🎯 Objetivos
- **Predecir la demanda de cursos** con modelos de aprendizaje automático.
- **Optimizar la asignación de secciones y horarios**, considerando restricciones físicas y operativas.
- **Reducir la incertidumbre en la planificación académica** con decisiones basadas en datos.
- **Facilitar la toma de decisiones** mediante visualizaciones y reportes interactivos.

## 🔧 Tech Stack

### 🖥️ **Frontend**
- React + Next.js + TypeScript
- Shadcn UI + Tailwind CSS
- Recharts para visualización de datos
- Zustand para gestión de estado

### 🏗️ **Backend**
- FastAPI + PostgreSQL
- SQLAlchemy como ORM
- Docker para despliegue

### 📊 **Machine Learning**
- Scikit-learn + XGBoost
- Jupyter Notebook para pruebas y análisis de datos

### 🔐 **Autenticación**
- Firebase Auth

## 🏛️ Arquitectura
El sistema sigue una arquitectura escalable y modular:
- **Frontend:** Aplicación React con Next.js que consume la API de FastAPI.
- **Backend:** API REST con FastAPI conectada a una base de datos PostgreSQL.
- **ML Pipeline:** Modelos de predicción entrenados y desplegados con un flujo automatizado.
- **CI/CD:** Despliegue automatizado en Google Cloud Platform (GCP) con Kubernetes y Terraform.

## ⚙️ Características Principales
✅ **Predicción de demanda de cursos** con modelos de Machine Learning.
✅ **Gestión de horarios y secciones** en base a restricciones académicas y preferencias estudiantiles.
✅ **Visualización de datos interactiva** para la toma de decisiones.
✅ **Sistema escalable** con despliegue en Kubernetes.
✅ **Seguridad integrada** con OAuth2, encriptación y protección contra ataques CSRF/XSS.

## 📌 Instalación y Configuración
### 🚀 Requisitos previos
- Node.js 18+
- Python 3.10+
- Docker y Docker Compose
- PostgreSQL
- Firebase (para autenticación)

### 🔨 Clonar el repositorio
```sh
git clone https://github.com/jorge2144/smartpath-ai.git
cd smartpath-ai
```

### 🖥️ Configurar el backend
```sh
cd backend
python -m venv venv
source venv/bin/activate  # En Windows: venv\Scripts\activate
pip install -r requirements.txt
uvicorn main:app --reload
```

### 💻 Configurar el frontend
```sh
cd frontend
npm install
npm run dev
```

### 🐳 Desplegar con Docker
```sh
docker-compose up --build
```

## 📊 Monitoreo y Seguridad
🔹 **Logs y monitoreo:** Integración con Loguru, Prometheus, Grafana y Sentry.
🔹 **Seguridad:** Implementación de OAuth2, CORS, CSRF y encriptación con Fernet.
🔹 **CI/CD:** Pipelines con GitHub Actions y Terraform para despliegue automatizado en GCP.

## 📈 Métricas de Éxito
- **Precisión del modelo de predicción.**
- **Tiempo de respuesta del sistema.**
- **Satisfacción de usuarios (profesores y alumnos).**
- **Reducción de cursos con baja demanda.**

## 🏗️ Roadmap de Desarrollo
✅ **Fase 1 (MVP)** – Integración de modelos de predicción y despliegue en GCP.
🔲 **Fase 2** – Optimización del modelo y mejora de la visualización de datos.
🔲 **Fase 3** – Expansión a otras instituciones y escalabilidad a nivel nacional.

## ✨ Contribuciones
Este proyecto es de código abierto y se aceptan contribuciones. Para contribuir:
1. **Fork el repositorio**.
2. **Cree una rama con su feature** (`git checkout -b feature-nueva`).
3. **Haga commit de sus cambios** (`git commit -m "Agregando nueva funcionalidad"`).
4. **Realice un push a su rama** (`git push origin feature-nueva`).
5. **Abra un Pull Request**.

## 📜 Licencia
Este proyecto está bajo la licencia MIT. Ver [LICENSE](LICENSE) para más detalles.

## 🤝 Contacto
📧 Email: ccjorge2144@gmail.com
💻 GitHub: [SmartPath-AI](https://github.com/jorge2144/smartpath-ai)

---
**Optimización de la Oferta Académica con Análisis Predictivo** 📊🚀
