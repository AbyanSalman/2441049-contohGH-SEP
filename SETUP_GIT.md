# Setup Git untuk Branch Arcatory

Jalankan perintah berikut di folder repository:

```bash
git init
git add .
git commit -m "Initial commit: base repository Arcatory"

git branch analisis
git branch desain
git branch implementasi
```

Jika ingin membuat branch sesuai isi pekerjaannya, gunakan alur berikut:

```bash
git checkout analisis
# isi dokumen analisis
git add .
git commit -m "Add analysis documents"

git checkout main
git checkout -b desain
# isi dokumen desain
git add .
git commit -m "Add design documents"

git checkout main
git checkout -b implementasi
# isi dokumen implementasi
git add .
git commit -m "Add implementation documents"
```
