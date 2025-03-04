# IA-Bullying-Detection 🚸

Este proyecto utiliza **Inteligencia Artificial** para **detectar y prevenir el bullying** en entornos escolares mediante **análisis de video, audio y texto en tiempo real**.

## 📌 Características del Proyecto
- 🔍 **Visión por Computadora**: Detección de agresiones físicas con YOLOv8, Faster R-CNN y OpenPose.
- 🎙 **Análisis de Voz**: Identificación de insultos y tono agresivo con Whisper y Wav2Vec 2.0.
- 💬 **Procesamiento de Texto (NLP)**: Detección de acoso en chats con BERT y RoBERTa.
- 📢 **Alertas Inteligentes**: Notificaciones a docentes y administradores en tiempo real.
- 🌐 **Interfaz Web**: Panel de monitoreo con reportes e historial de incidentes.

## 📂 Estructura del Proyecto
```plaintext
IA-Bullying-Detection/
│── data/            # 📂 Almacena datasets (videos, audios, textos)
│── models/          # 📂 Modelos de IA entrenados
│── src/             # 📂 Código fuente (visión, audio, texto, alertas)
│── app/             # 📂 Aplicación web (backend y frontend)
│── deployment/      # 📂 Configuración para despliegue (Docker, Cloud)
│── tests/           # 📂 Pruebas unitarias e integración
│── docs/            # 📂 Documentación del proyecto
│── requirements.txt # 📄 Dependencias
│── README.md        # 📄 Descripción del proyecto

plaintext```

🚀 Instalación y Configuración
1️⃣ Clonar el repositorio

- git clone https://github.com/Franz-Gonzales/IA-Bullying-Detection.git
- cd IA-Bullying-Detection


2️⃣ Crear un entorno virtual y activar
- python -m venv envpython -m venv env
source env/bin/activate  # Mac/Linux
env\Scripts\activate  # Windows

3️⃣ Instalar dependencias

 - pip install -r requirements.txt


4️⃣ Ejecutar la aplicación
- python app/backend/main.py

🔧 Tecnologías Utilizadas
- Python 3.x 🐍
- TensorFlow / PyTorch 🧠
- YOLOv8 / Faster R-CNN 📹
- Whisper / Wav2Vec 2.0 🎙
- BERT / RoBERTa 📝
- FastAPI / Flask 🚀
- MongoDB / Firebase 🗄