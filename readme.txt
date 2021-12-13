Memasang Git disebuah folder
-> Git Init
folder(master)

Config Git :
git config --global username.name'<nama>'
git config --global username.email<email>

Change deffault(VIM) editor GIT :
git config --global core.editor "code --wait" (VScode) 
git config --global core.editor "atom --wait" (Atom) 

GIT Area
1. Working Tree | git add.
2. Staging Area (Perubahan file akan menjadi history ketika di commit) | git add 'namafile'
3. History (File yg dicommiot tersimpan oleh GIT)/checkpoint | git commit -m "text"

New file -> 1Working Tree1 -> Staging -> 2Staging Area2 -> commit -> 3History3

git log --online
output : hash - master(branch) - isi

git push -> upload github
repository -> folder dalam git

bridge - remote
git remote add 'nama' link github
git remote -v
upload git push -> nama remote -> master (git push remote-github master)
git push --set-upstream origin master

Download---------------------------
Local - Online = git remote
1. Link 
2. git remote add 'nama' link
3. git pull 'nama' master

Modify | Update--------------------
1. git add namefile / .
2. git commit -m 'text'
3. git push 

Checkout---------------------------
Kembali ke versi sblmnya
git checkout 'hash'
