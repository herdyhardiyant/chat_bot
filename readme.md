# Chatbot Azure Semantic Kernel (Python + FastAPI)

Proyek ini adalah chatbot berbasis **Semantic Kernel** dan **Azure OpenAI** yang dibangun menggunakan **Python** dan **FastAPI**, serta dilengkapi dengan antarmuka frontend menggunakan **HTML + JavaScript** dalam satu codebase.

---

## Fitur

- Integrasi dengan **Azure OpenAI** (GPT-4.1-nano)
- Menggunakan **Semantic Kernel SDK (Python)** untuk orkestrasi percakapan
- API backend dengan **FastAPI**
- Frontend sederhana dengan **HTML + JS**
- Struktur proyek rapi dan mudah dikembangkan

---

## 🚀 Cara Menjalankan

### 1. Clone Repository

```bash
git clone https://github.com/herdyhardiyant/chat_bot
cd chat_bot
```

### 2. Buat dan Aktifkan Virtual Environment

```bash
python -m venv venv
source venv/bin/activate  # Windows: venv\Scripts\activate
```
### 3. Instalasi Dependensi
```bash
pip install -r requirements.txt
```

### 4. Atur Konfigurasi Azure di file .env
```ini

AZURE_OPENAI_API_KEY=""
AZURE_OPENAI_ENDPOINT=""
AZURE_DEPLOYMENT_NAME=""
```

### 5. Jalankan Aplikasi
```bash
uvicorn main:app --reload

# Buka browser di http://localhost:8000/
```

## Struktur Proyek
```
chatbot/
├── main.py           # Backend utama (FastAPI + Semantic Kernel)
├── templates/
│   └── index.html    # Halaman antarmuka chatbot
├── static/
│   └── script.js     # JavaScript frontend
├── .env              # Konfigurasi Azure OpenAI
├── requirements.txt  # Daftar dependensi
└── README.md
```
