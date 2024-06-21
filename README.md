Berikut adalah file README untuk proyek "UPN Sehat":

---

# UPN Sehat

UPN Sehat adalah aplikasi yang dirancang untuk mendukung gaya hidup sehat. Proyek ini terdiri dari dua bagian utama: backend dan frontend.

## Prasyarat

Pastikan Anda telah menginstall perangkat lunak berikut di sistem Anda:

1. Docker
2. Node.js
3. Docker Compose

## Langkah-langkah Menjalankan Proyek

Ikuti langkah-langkah di bawah ini untuk menjalankan proyek UPN Sehat:

### 1. Clone Proyek

Clone repository ini ke lokal mesin Anda:

```bash
git clone https://github.com/username/UPNSehat.git
cd UPNSehat
```

### 2. Build Backend

Masuk ke direktori backend dan build image Docker:

```bash
cd backend
docker build -t backend-app .
```

### 3. Build Frontend

Masuk ke direktori frontend dan build image Docker:

```bash
cd frontend
docker build -t frontend-app .
```

### 4. Jalankan Docker Compose

Kembali ke direktori root dan jalankan Docker Compose:

```bash
cd ..
docker-compose up
```

### 5. Akses Aplikasi

Setelah Docker Compose berhasil menjalankan kontainer, akses aplikasi melalui URL berikut:

- **Frontend**: [http://localhost:3001](http://localhost:3001)
- **Backend**: [http://localhost:3000](http://localhost:3000)

## Struktur Proyek

```
UPNSehat/
│
├── backend/
│   ├── Dockerfile
│   ├── src/
│   └── ...
│
├── frontend/
│   ├── Dockerfile
│   ├── src/
│   └── ...
│
├── docker-compose.yml
└── README.md
```

## Teknologi yang Digunakan

- **Backend**: Node.js, Express.js
- **Frontend**: React.js
- **Containerization**: Docker, Docker Compose


Selamat menggunakan UPN Sehat! Jika Anda mengalami masalah atau memiliki pertanyaan, jangan ragu untuk menghubungi kami melalui issue di repository ini.
