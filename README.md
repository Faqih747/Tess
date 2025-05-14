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


🖼️ Tampilan Aplikasi
st.set_page_config(page_title="CV Analyzer AI", layout="wide")
st.title("📄 CV Analyzer AI")

Aplikasi ini dibagi dalam lima tab utama:

tab1, tab2, tab3, tab4, tab5 = st.tabs([
    "📤 Upload CV", "🔍 Ringkasan", "🤖 Rekomendasi", 
    "⚖️ Perbandingan", "📊 Skoring CV"
])


📎 Contoh Penggunaan
Setelah aplikasi berjalan, kamu dapat:

Upload beberapa CV dalam format PDF.

Melihat ringkasan dari masing-masing dokumen.

Mendapatkan saran dan rekomendasi dari AI.

Membandingkan beberapa CV berdasarkan aspek tertentu (misalnya: pengalaman kerja, pendidikan).

Melihat skoring CV dengan indikator visual (grafik batang atau radar).

📝 Catatan Tambahan
Model LLM yang digunakan adalah dari Groq/OpenAI.

Aplikasi ini cocok digunakan dalam proses rekrutmen, penyaringan kandidat, atau personal branding review.
