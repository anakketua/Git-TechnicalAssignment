membuat folder nama: mkdir chandra; cd chandra

membuat file readme.md dan mengisinya: touch readme.md ; echo ""Halo perkenalkan aku halaman utama" > readme.md

insialisasi folder tersebut dengan Git, kemudian dokumentasikan menggunakan commit dengan pesan: git init; git add .; git commit -m "Inisialisasi Git Repository"

buat branch baru dengan nama cv: git branch cv

pindah branch kedalam cv, kemudian buat file dengan nama cv.txt dan isi file tersebut dengan kalimat: git checkout cv; touch cv.txt; echo "Ini adalah file CV" > cv.txt

dokumentasikan menggunakan commit dengan pesan: git add; git commit -m "Inisialisasi CV" 

tambahkan 3 perusahaan yang akan kamu lamar, dan setiap menuliskan 1 nama perusahaan kamu harus melakukan dokumentasi menggunakan commit: echo "Tokopedia" > cv.txt; commit -m "Tokopedia" echo "Microsoft" > cv.txt; commit -m "Microsoft" echo "Facebook" > cv.txt; commit -m "Facebook"

kembali ke branch master: git checkout master


ubah file README.md dan dokumentasi dengan commit: echo $'Halo perkenalkan aku halaman utama \nIni adalah update pertama pada branch master' ; git commit -m "update master pertama"

gabungkan branch cv kedalam branch master menggunakan perintah git merge: git merge cv

unggah Git Repository tersebut kedalam GitHub: git add . git commit -m "upload to github" git push origin --all
