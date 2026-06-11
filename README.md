# Indobert_Dataset
Dataset repository for indobert

## Sumber Data
`Teknik Pemuliaan Tanaman.pdf`: Buku pemuliaan tanaman yang belum di modifikasi
`Teknik Pemuliaan Tanaman_ocr.pdf`: Buku pemuliaan tanaman yang di OCR (searchable)
`final_dataset_90_with_new_feedback_lor_fixed.csv`: Contoh struktur .csv

## Folder Yang Terkait
- `/claude`: hasil generasi claude.ai per agent
- `/grok`: hasil generasi Grok (free tier)
- `/teknik-pemuliaan-tanaman-split-bab`: Hasil split pdf sumber data per BAB
- `/teknik-pemuliaan-tanaman-split-bab-ocr-read`: Hasil OCR pdf, dibagi per BAB
    - `/merge-by3`: Hasil OCR di merge (digabung) per 3 BAB

## File Pembantu
- `prompt.txt`: text prompt yang dijalankan ke AI
- `Notes.txt`: Detail tambahan