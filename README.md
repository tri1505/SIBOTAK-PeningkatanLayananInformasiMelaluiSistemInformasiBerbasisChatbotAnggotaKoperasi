Ringkasan Penelitian
Koperasi, sebagai pilar ekonomi berbasis gotong royong, menghadapi tantangan signifikan dalam penyediaan layanan informasi akibat keterbatasan sumber daya manusia dan rendahnya adopsi teknologi digital. Koperasi Syariah AlMuhajir, khususnya, mengalami ketimpangan antara jumlah pengurus dan anggota, sehingga pelayanan informasi menjadi tidak optimal. Kondisi ini berpotensi menurunkan kepuasan anggota dan mendorong migrasi ke platform fintech digital yang lebih responsif.

Untuk mengatasi permasalahan tersebut, diperlukan solusi berbasis teknologi yang mampu memberikan layanan informasi secara otomatis, cepat, akurat, dan selaras dengan prinsip syariah. Penelitian ini bertujuan merancang SIBOTAK, sebuah chatbot berbasis Natural Language Processing (NLP) yang dapat memberikan layanan informasi 24/7 sesuai dengan nilai-nilai syariah.

Penelitian ini menggunakan metodologi CRISP-DM (Cross-Industry Standard Process for Data Mining) yang terdiri dari enam tahapan: pemahaman bisnis, pemahaman data, persiapan data, pemodelan, evaluasi, dan deployment.

Pendekatan pengumpulan data bersifat hibrida dan berpusat pada pengguna (user-centric), menggabungkan:

Data berbasis aturan (rule-based): berasal dari fatwa DSN-MUI, Anggaran Dasar/Anggaran Rumah Tangga (AD/ART), serta dokumen akad syariah.
Data berbasis pengguna (user-based): diperoleh dari log percakapan anggota dan data profil anggota Koperasi Syariah AlMuhajir.
Dataset intent dibangun melalui proses text structuring, text cleaning, dan text augmentation. Model NLP dilatih menggunakan pendekatan semantic search dengan integrasi text encoding berbasis IndoBERT dan algoritma pencarian Hierarchical Navigable Small World (HNSW).

Evaluasi model dilakukan untuk mengukur akurasi, kecepatan respons, serta kemampuan memahami variasi bahasa alami, termasuk typo.

Implementasi model NLP menunjukkan performa yang sangat baik dalam hal kecepatan dan akurasi pencarian semantik. Chatbot SIBOTAK mampu memahami pertanyaan anggota meskipun mengandung kesalahan ketik atau variasi ekspresi bahasa. Prototipe SIBOTAK berhasil memberikan layanan informasi secara otomatis 24/7 dengan respons yang konsisten terhadap prinsip syariah.

Produk luaran penelitian meliputi:

Model NLP yang telah dioptimalkan,
Prototipe chatbot SIBOTAK,
Artikel ilmiah untuk publikasi di jurnal internasional bereputasi,
Hak Kekayaan Intelektual (HaKI),
Video Dokumentasi penelitian.

Penelitian ini menunjukkan bahwa penerapan AI berbasis Natural Language Processing (NLP) dapat menjadi solusi efektif untuk meningkatkan layanan informasi di koperasi, termasuk dalam kerangka Koperasi Merah Putih — sebuah program strategis bagian dari penguatan ekonomi kerakyatan berbasis gotong royong. Untuk memperkuat identitas koperasi sebagai lembaga yang adaptif terhadap transformasi digital tanpa mengorbankan nilai-nilai luhur, baik syariah maupun nasionalisme ekonomi yang menjadi fondasi Koperasi Merah Putih.

Sistem seperti SIBOTAK dapat dikembangkan lebih lanjut dengan integrasi layanan transaksional, personalisasi berbasis riwayat anggota, serta peningkatan kapasitas multilingual untuk melayani keragaman anggota di seluruh Indonesia. Dengan demikian, penelitian ini tidak hanya menjadi langkah inovatif dalam digitalisasi koperasi syariah, tetapi juga relevan sebagai penguatan infrastruktur digital dalam ekosistem Koperasi Merah Putih yang inklusif, modern, dan berkeadilan.

✨ Kebaruan Penelitian
SIBOTAK menggabungkan pendekatan hybrid user centric: data aturan dari fatwa DSN-MUI, AD/ART, dan akad syariah, serta data pengguna dari riwayat percakapan anggota. Model NLP yang dikembangkan dengan mengintegrasikan IndoBERT untuk text encoding dan algoritma Hierarchical Navigable Small World (HNSW) untuk semantic search. Ini memungkinkan chatbot memahami pertanyaan dalam bahasa alami bahkan dengan typo atau variasi kata tanpa kehilangan akurasi atau kesesuaian syariah.
