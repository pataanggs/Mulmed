# Sistem Teknologi Multimedia - Audio Processing

**Nama:** Fathan Andi Kartagama  
**NIM:** 122140055  
**Mata Kuliah:** Sistem Teknologi Multimedia  
**Repository:** [Mulmed](https://github.com/pataanggs/Mulmed)

---

## 📋 Deskripsi

Repository ini berisi pengerjaan tugas untuk mata kuliah Sistem Teknologi Multimedia. Proyek mencakup berbagai teknik pemrosesan audio digital, termasuk:

---

## 📁 Struktur Repository

```
Sistem-Teknologi-Multimedia/
├── README.md                          # Dokumentasi utama
├── multimedia-uv/                     # Virtual environment Python
│   ├── Scripts/                       # Executable dan aktivasi venv
│   └── Lib/site-packages/            # Package Python terinstall
│
├── Worksheet-1/                       # Tugas minggu 1
│   ├── worksheet1.pdf                # Laporan PDF
│   ├── test_libs.py                  # Test library
│   └── Figure/                       # Gambar dan visualisasi
│
├── Worksheet-2/                       # Tugas minggu 2
│   ├── 122140055-Worksheet2.pdf     # Laporan PDF
│   ├── 3_exercise_loading_media.ipynb
│   └── data/                         # File media (video, audio, gambar)
│
├── Worksheet-3/                       # Tugas minggu 3 (Audio Processing)
│   ├── main.ipynb                    # Notebook utama (ALL-IN-ONE)
│   └── audio/                        # File audio hasil processing
│       ├── Berita.wav                # Soal 1: Rekaman multi-level
│       ├── 1015.wav                  # Soal 2: Audio dengan noise
│       ├── Adele.wav                 # Soal 5: Song 1 untuk remix
│       ├── PharrelW.wav              # Soal 5: Song 2 untuk remix
│       └── [hasil processing...]     # File output dari setiap soal
│
└── Testing/                          # Folder testing eksperimen
    ├── main.ipynb
    └── [audio files...]
```

---

## 🛠️ Teknologi dan Library

### Requirements
- **Python:** 3.10+
- **Jupyter Notebook** atau **VS Code** dengan extension Python & Jupyter

### Python Libraries
```
numpy>=1.24.0
matplotlib>=3.7.0
librosa>=0.10.1
soundfile>=0.12.1
scipy>=1.10.0
pydub>=0.25.1
pyloudnorm>=0.1.1
soxr>=0.3.0
```

---

## 🚀 Cara Menjalankan

### 1. Clone Repository
```bash
git clone https://github.com/pataanggs/Mulmed.git
cd Sistem-Teknologi-Multimedia
```

### 2. Setup Virtual Environment

#### Windows (PowerShell):
```powershell
# Aktivasi virtual environment yang sudah ada
.\multimedia-uv\Scripts\activate

# Atau buat virtual environment baru
python -m venv multimedia-uv
.\multimedia-uv\Scripts\activate
```

#### Linux/MacOS:
```bash
# Aktivasi virtual environment
source multimedia-uv/bin/activate

# Atau buat virtual environment baru
python3 -m venv multimedia-uv
source multimedia-uv/bin/activate
```

### 3. Install Dependencies
```bash
pip install -r requirements.txt
```

Atau install manual:
```bash
pip install numpy matplotlib librosa soundfile scipy pydub pyloudnorm soxr
```

### 4. Install FFmpeg (Required untuk pydub)

#### Windows:
```powershell
# Menggunakan Chocolatey
choco install ffmpeg

# Atau download manual dari: https://ffmpeg.org/download.html
```

#### Linux (Ubuntu/Debian):
```bash
sudo apt update
sudo apt install ffmpeg
```

#### MacOS:
```bash
brew install ffmpeg
```

### 5. Jalankan Jupyter Notebook
```bash
# Navigasi ke folder Worksheet-3
cd Worksheet-3

# Launch Jupyter Notebook
jupyter notebook main.ipynb

# Atau gunakan Jupyter Lab
jupyter lab
```

#### Menggunakan VS Code:
1. Buka folder `Sistem-Teknologi-Multimedia` di VS Code
2. Install extension: **Python** dan **Jupyter**
3. Pilih kernel: `multimedia-uv` (Python 3.10)
4. Buka `Worksheet-3/main.ipynb`
5. Klik **Run All** atau jalankan cell per cell

---
