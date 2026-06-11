# Indobert_Dataset
Dataset repository for indobert

## Sumber Data
- `Teknik Pemuliaan Tanaman.pdf`: Buku pemuliaan tanaman yang belum di modifikasi
- `Teknik Pemuliaan Tanaman_ocr.pdf`: Buku pemuliaan tanaman yang di OCR (searchable)
- `final_dataset_90_with_new_feedback_lor_fixed.csv`: Contoh struktur .csv

## Folder Yang Terkait
- `/claude`: hasil generasi claude.ai per agent
- `/grok`: hasil generasi Grok (free tier)
- `/teknik-pemuliaan-tanaman-split-bab`: Hasil split pdf sumber data per BAB
- `/teknik-pemuliaan-tanaman-split-bab-ocr-read`: Hasil OCR pdf, dibagi per BAB
    - `/merge-by3`: Hasil OCR di merge (digabung) per 3 BAB

## File Pembantu
- `prompt.txt`: text prompt yang dijalankan ke AI
- `Notes.txt`: Detail tambahan
- `master.xlsx`: File Gabungan Dataset dalam bentuk excel (semua bab included)
- `master.csv`:  File Gabungan Dataset

## Penjelasan Tiap Kolom
- `bab`: labelling bab untuk setiap pertanyaan
- `question`: Pertanyaan yang di generate
- `answer_key`: Kunci jawaban dari `question`
- `student_answer`: Jawaban siswa yang di generate
- `label`: benar/salah tergantung jawaban siswa
- `score`: 0-5 tergantung kualitas jawaban `student_answer`
- `adaptive_feedback`: masukkan terhadap `student_answer` yang di generate