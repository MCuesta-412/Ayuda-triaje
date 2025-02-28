# Ayuda-triaje
Chatbot para pacientes que ayuda a decidir a que centro médico acudir.
### Desarrollo de un Chatbot para Triaje Médico

#### Objetivo
El usuario quiere desarrollar un chatbot para ayudar a pacientes a decidir si deben acudir a un centro de salud o a urgencias de un hospital.

#### Características Clave
- **Plataforma:** Web
- **Interacción:** Entrada de texto y subida de imágenes
- **Uso de imágenes:** Solo como apoyo para la toma de decisión, no para prediagnóstico
- **Infraestructura recomendada:**
  - **Frontend:** React o Next.js con Tailwind CSS o Material UI
  - **Backend:** FastAPI, Flask o Node.js con Express
  - **IA:** Modelos de NLP (GPT-4, LlamaIndex) y modelos de visión (EfficientNet, YOLOv8) para analizar imágenes
  - **Almacenamiento:** AWS S3 o Firebase Storage
  - **Base de datos:** PostgreSQL o MongoDB
  - **Seguridad:** HTTPS, JWT para autenticación, cumplimiento con GDPR/HIPAA

#### Datasets Recomendados
- **Para texto:**
  - MTS (Manchester Triage System)
  - MedQuAD
  - SymCAT
  - NHANES (CDC)
- **Para imágenes:**
  - ISIC Archive (Dermatología)
  - CheXpert (Radiografías)
  - HAM10000 (Enfermedades dermatológicas)
  - Open-i (NIH, imágenes médicas diversas)

#### Prototipo Inicial
Se creó un prototipo de interfaz con React que permite:
- Introducir síntomas en un cuadro de texto
- Subir una imagen opcional
- Recibir una respuesta simulada basada en los datos ingresados

#### Siguientes Pasos
- Integrar un modelo de IA para procesamiento de lenguaje natural
- Explorar modelos de visión por computadora para evaluación de imágenes
- Desarrollar API backend para gestionar las consultas y respuestas
- Mejorar la UI/UX para una mejor experiencia de usuario

