membuat folder git-basics: mkdir git-basics
masuk ke folder git-basics: cd git-basics
membuat file text bernama first: touch first.txt
buat git repo: git init
menambahkan first.txt ke staging area: git add first.txt
dokumentasi perubahan di stage area dengan pesan : git commit -m "adding first.txt"
melihat semua commit pada repo: git log
membuat file text bernama second: touch second.txt
menambahkan second.txt ke staging area: git add second.txt
dokumentasi perubahan di stage area dengan pesan: git commit -m "adding second.txt"
menghapus first.txt: git rm first.txt
menambahkan semua perubahan di working directory ke staging area: git add .
dokumentasi perubahan di stage area dengan pesan: git commit -m "removing first.txt"
melihat semua commit pada repo: git log
