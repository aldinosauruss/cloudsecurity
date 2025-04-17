# Perbandingan Alat Monitoring Keamanan Runtime Berbasis eBPF pada Kubernetes

Repositori ini merupakan bagian dari tugas akhir yang berfokus pada evaluasi efektivitas dan efisiensi alat monitoring keamanan runtime berbasis eBPF dalam mendeteksi serangan terhadap klaster Kubernetes.

## 🧠 Abstrak

Transformasi digital modern telah mendorong adopsi teknologi cloud native yang memungkinkan organisasi meningkatkan efisiensi operasional dan kecepatan inovasi. Namun, peningkatan penggunaan Kubernetes sebagai platform orkestrasi kontainer juga membawa tantangan baru dalam aspek keamanan, khususnya pada fase runtime.

Penelitian ini membandingkan tiga alat monitoring keamanan runtime berbasis eBPF: **Falco**, **Tetragon**, dan **Tracee**. Eksperimen dilakukan pada klaster Kubernetes yang dikelola melalui Digital Ocean Kubernetes (DOKS), dengan simulasi serangan dari daftar **OWASP Kubernetes Top 10**. Evaluasi mencakup metrik seperti:

- Mean Time to Detect (MTTD)
- Detection Rate
- False Positive Rate
- False Negative Rate
- Latensi sistem
- Memory dan CPU Utilization

Tujuan dari penelitian ini adalah untuk mengidentifikasi kekuatan dan kelemahan masing-masing alat dalam mendeteksi aktivitas mencurigakan secara real-time, serta memberikan rekomendasi konfigurasi optimal berdasarkan jenis serangan.

## 🔧 Tools dan Teknologi

- **Kubernetes (DOKS)**
- **Falco** – Runtime security tool berbasis eBPF
- **Cilium Tetragon** – Observability dan enforcement tool berbasis eBPF
- **Aqua Tracee** – eBPF-based runtime security dan threat detection
- **Prometheus & Grafana** – Monitoring dan visualisasi performa
- **Attack Simulators** – Skrip serangan OWASP K8s Top 10

## 📁 Struktur Repositori

