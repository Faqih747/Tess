📄 CV Analyzer AI
CV Analyzer AI adalah aplikasi berbasis Streamlit yang dirancang untuk menganalisis dan mengevaluasi CV (Curriculum Vitae) secara otomatis menggunakan teknologi AI dari Groq/OpenAI. Aplikasi ini dapat memberikan:

Ringkasan isi CV

Rekomendasi perbaikan

Perbandingan antar-CV

Skor CV berdasarkan kualitas

🚀 Fitur Utama
📤 Upload Banyak CV (format PDF)

🔍 Ringkasan Otomatis dari isi CV

🤖 Rekomendasi AI untuk perbaikan CV

⚖️ Perbandingan CV antar kandidat

📊 Skoring CV berdasarkan metrik tertentu

🛠️ Instalasi
Clone repository:
git clone https://github.com/username/cv-analyzer-ai.git
cd cv-analyzer-ai

Instal dependensi:

pip install -r requirements.txt
Jika belum ada requirements.txt, gunakan ini:

pip install streamlit pyngrok langchain langchain-groq chromadb sentence-transformers pymupdf python-dotenv pdfplumber pandas matplotlib

▶️ Menjalankan Aplikasi
bash
Copy
Edit
streamlit run app.py
