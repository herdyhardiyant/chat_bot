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
git clone https://github.com/username/chatbot.git
cd chatbot
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
# Silahkan gunakan kredensial saya untuk rekruiter XIONCO
AZURE_OPENAI_API_KEY=EfGdMwTUknSHwaZkDRZC1wimY5fQTd4tZmLRsLsDS0QN4f2sltHFJQQJ99BEACHYHv6XJ3w3AAAAACOGaprn
AZURE_OPENAI_ENDPOINT=https://ai-herdyhardiyant7096ai317864532559.cognitiveservices.azure.com/openai/deployments/gpt-4.1-nano/chat/completions?api-version=2025-01-01-preview
AZURE_DEPLOYMENT_NAME=gpt-4.1-nano
```

### 5. Jalankan Aplikasi
```bash
uvicorn main:app --reload

# Buka browser di http://localhost:8000/
```

## Struktur Proyek
chatbot/
├── main.py                  # Backend utama (FastAPI + Semantic Kernel)
├── templates/
│   └── index.html           # Halaman antarmuka chatbot
├── static/
│   └── script.js            # JavaScript frontend
├── .env                     # Konfigurasi Azure OpenAI
├── requirements.txt         # Daftar dependensi
└── README.md
