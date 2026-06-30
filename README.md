# 🚀 KhayServer - Web Deployment Project

![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge\&logo=docker\&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge\&logo=github-actions\&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge\&logo=html5\&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=for-the-badge\&logo=nginx\&logoColor=white)

## 📌 Tentang Project

**KhayServer** merupakan website company profile yang dikembangkan sebagai bagian dari tugas Ujian Akhir Semester (UAS) mata kuliah Web Deployment.

Website ini menampilkan informasi mengenai layanan server, hosting, dan solusi infrastruktur digital yang dikemas dalam tampilan modern dan responsif.

Website dapat diakses melalui:

🌐 https://www.khayserver.my.id/

---

## 🎯 Tujuan Project

Project ini dibuat untuk memenuhi tugas UAS sekaligus mengimplementasikan konsep:

* Deployment website menggunakan Docker.
* Containerization aplikasi web.
* Implementasi CI/CD menggunakan GitHub Actions.
* Otomatisasi deployment ke server.
* Pengelolaan source code menggunakan GitHub.

---

## ✨ Fitur Website

* Landing page modern dan responsif.
* Informasi layanan server dan hosting.
* Tampilan user-friendly.
* Desain responsif untuk desktop maupun mobile.
* Deploy otomatis menggunakan GitHub Actions.
* Containerized menggunakan Docker.

---

## 🛠️ Teknologi yang Digunakan

| Teknologi      | Keterangan                          |
| -------------- | ----------------------------------- |
| HTML5          | Struktur halaman web                |
| CSS3           | Styling website                     |
| JavaScript     | Interaktivitas website              |
| Docker         | Containerization                    |
| Docker Compose | Manajemen container                 |
| GitHub Actions | Continuous Integration & Deployment |
| Nginx          | Web Server                          |

---

## 📂 Struktur Repository

```bash
.
├── .github/
│   └── workflows/
│       └── deploy.yml
├── html/
│   ├── index.html
├── docker-compose.yml
└── README.md
```

---

## 🐳 Deployment Menggunakan Docker

### Clone Repository

```bash
git clone https://github.com/zahrotulm-s/uas-pak-endy-2-matkul.git
```

### Masuk ke Direktori Project

```bash
cd uas-pak-endy-2-matkul
```

### Menjalankan Container

```bash
docker compose up -d
```

### Melihat Status Container

```bash
docker ps
```

### Menghentikan Container

```bash
docker compose down
```

---

## 🔄 Implementasi CI/CD

Repository ini menggunakan **GitHub Actions** untuk mengotomatisasi proses deployment.

### Workflow CI/CD

```text
Developer
    ↓
Push Source Code
    ↓
GitHub Repository
    ↓
GitHub Actions
    ↓
Build & Deploy
    ↓
Web Server
    ↓
Website Updated
```

Setiap perubahan yang di-push ke branch utama akan memicu workflow deployment secara otomatis.

---

## 🌐 Hasil Deployment

Website berhasil dideploy dan dapat diakses melalui:

https://www.khayserver.my.id/

---

## 📚 Materi yang Dipelajari

Selama pengerjaan project ini, beberapa materi yang dipelajari antara lain:

* Docker Container
* Docker Compose
* Web Server Nginx
* Git dan GitHub
* GitHub Actions
* Continuous Integration
* Continuous Deployment
* Deployment Website

---

## 👩‍💻 Author

**Zahrotul Mufidah Salim**

Mahasiswi Teknik Informatika

Semester 1

---

## 📄 License

Project ini dibuat untuk keperluan akademik dan pembelajaran.
