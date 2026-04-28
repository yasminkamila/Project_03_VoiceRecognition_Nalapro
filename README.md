# NaLaPro Project 03 - Bootcamp - Voice Recognition

## Anggota Tim NLP - B - NaLaPro
- Wahid Setio Darmadi
- M. Dhimas Agung Sugiharto
- Yasmin Kamila
- Eko Erwis Wandoko
- Muh.idris

## File Presentasi
- Terdapat di folder Document/NalaPro/

## Data
- Dataset menggunakan MINDS-14 : https://huggingface.co/datasets/PolyAI/minds14
- Dataset yang digunakan sebanyak train 563 data dengan pembagian Train: 80%, dev:10%, dan test :10%.
- Dataset dilakukan preprocessing dan augmentation, setelah di proses dataset diletakan di kaggle url : https://www.kaggle.com/datasets/nalaprogroup/data-nalapro-project03
- Tujuan diletakan di kagle agar dataset tidak bergerak sehingga proses training dilakukan dengan dataset yang sama

## Data Test - External
- Merupakan data suara yang berasal dari luar MINDS-14 dataset, bisa saja milik anggota ataupun diluar anggota
- Lokasi Folder : Script/data/test

# Model
- Wav2Vec2-Base
- Wishper-Base
- whisper-small
- whisper-small LoRA fine tuning
- wav2vec base960h

# Struktur Folder
## Document
Berisi Dokumen bukan script yang digunakan atau bermanfaat atau mendukung project ini baik sebagai landasan, tutorial, panduan, dan lain sebagainya

- Folder NalaPro
    Berisi Dokumen yang berasal dari anggota NaLaPro

- Folder Indonesia AI
    Berisi dokumen yang berasal dari materi bootcamp baik dari website resmi atau dari mentor


## Script
Berisi segala sesuatu yang berkaitan dengan script untuk membuat project-03 Voice Recognition
- Folder Data
    Berisi Data yang digunakan untuk script membangun project-03 Voice Recognition

- Folder models
    Berisi model-model yang akan digunakan atau dibentuk untuk kepentingan project-03 Voice Recognition

- Folder notebooks_colabs
    Berisi script yang berasal dari google colabs atau jupyter notebook atau yang berformat .ipynb

- Folder src
    Berisi script dengan format .py atau file pyton

- Folder venv (optional jika ada)
    Berisi resource dari virtual environment