# bedrock-rag-chat
# 🏢 PAC Inmobiliaria - Asesor Virtual con AWS Bedrock

¡Bienvenido al repositorio de **PAC Inmobiliaria**! 

Esta es una aplicación web interactiva construida con **Streamlit** que actúa como un Asesor Inmobiliario virtual. El "cerebro" de la aplicación está impulsado por **AWS Bedrock** (Agent Runtime), lo que le permite consultar una base de conocimientos (Knowledge Base) para ofrecer respuestas precisas y fundamentadas en el sector inmobiliario.

---

## ✨ Características Principales

* 💬 **Interfaz de Chat Personalizada:** Diseño UI/UX adaptado a la marca "PAC", con colores corporativos (Azul y Verde), avatares personalizados y animaciones de carga fluidas.
* 🧠 **Integración con AWS Bedrock:** Conexión directa con agentes de IA mediante `boto3` para procesar consultas en tiempo real.
* 🗂️ **Gestión de Historial:** Las conversaciones se guardan de forma persistente en formato local (`respaldo_conversaciones.json`).
* 🎛️ **Panel Lateral (Sidebar):** * Creación rápida de nuevas consultas.
  * Navegación entre las conversaciones.
  * Opción para eliminar historiales de forma individual.
* 🏷️ **Auto-titulado:** La aplicación genera automáticamente el título de la sesión basándose en el primer mensaje (prompt) enviado por el usuario.

---

## 🛠️ Tecnologías Utilizadas

* **Frontend:** [Streamlit](https://streamlit.io/) (Python)
* **Backend Cloud:** Amazon Web Services (AWS)
  * **AWS Bedrock:** Motor principal del LLM y RAG.
  * **Boto3:** SDK de AWS para Python.
* **Gestión de Entorno:** `python-dotenv` para la carga segura de credenciales.
* **Almacenamiento:** JSON local para persistencia rápida de sesiones.

---

## 🚀 Requisitos e Instalación

### Prerrequisitos
1. Tener **Python 3.8 o superior** instalado en tu sistema.
2. Contar con credenciales válidas de AWS (`AWS_ACCESS_KEY_ID` y `AWS_SECRET_ACCESS_KEY`) configuradas en tu máquina o en el archivo `.env`.
3. Tener un **Agente activo en AWS Bedrock** en la región `us-east-1` (o cambiar la región en el código).


https://github.com/user-attachments/assets/8cc7cf07-ae8d-423b-83ae-f8d5a55308a8


