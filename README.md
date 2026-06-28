# CureBot

CureBot is a friendly, AI-powered medical assistant designed to provide short, clear, and safe medical guidance. It helps users understand symptoms, suggests common over-the-counter (OTC) medicines, and provides home remedies. If symptoms are severe, CureBot advises consulting a doctor immediately.

## ✨ Features

*   **Multilingual Support**: Chat with CureBot in English, Telugu, or Hindi.
*   **Medical Image Analysis**: Upload images of medicines, prescriptions, or tablets to get details like medicine names and dosage strengths.
*   **Voice Input**: Speak to the bot easily using the built-in microphone feature.
*   **Safe Recommendations**: Strictly programmed to recommend only simple OTC medications and avoid prescribing restricted drugs, antibiotics, or steroids.
*   **Beautiful UI**: A visually appealing, responsive interface with nature-inspired elements and smooth animations.

## 🛠️ Technology Stack

**Frontend:**
*   HTML5
*   Vanilla CSS (Custom animations, glassmorphism design)
*   Vanilla JavaScript

**Backend:**
*   [FastAPI](https://fastapi.tiangolo.com/) (Python)
*   Uvicorn (ASGI server)
*   Azure Inference AI API (GPT models for chat and image analysis)
*   Pillow, python-multipart, requests

## 🚀 Getting Started

### Clone the Repository
```bash
git clone https://github.com/akarsh277/CureBot.git
cd CureBot
```

### Prerequisites
*   Python 3.8+
*   Node.js/Live Server (optional, for serving frontend easily)

### Backend Setup
1. Navigate to the `backend` directory:
   ```bash
   cd backend
   ```
2. Install the required Python packages:
   ```bash
   pip install -r requirements.txt
   ```
3. Set up your environment variables by creating a `.env` file in the `backend` directory with your API key:
   ```env
   API_KEY=your_azure_api_key_here
   ```
4. Run the FastAPI server:
   ```bash
   uvicorn main:app --reload
   ```

### Frontend Setup
1. Open the project root directory.
2. Serve the `index.html` using any local web server (e.g., VS Code Live Server).
3. The frontend will communicate with the local backend running on `http://localhost:8000`.

## ⚠️ Disclaimer
CureBot is an AI assistant intended for informational purposes only. It is **not** a substitute for professional medical advice, diagnosis, or treatment. Always seek the advice of your physician or other qualified health provider with any questions you may have regarding a medical condition.