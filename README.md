Daftar tugas / branch
 1. Tugas-git
 2. Tugas-html
 3. Tugas-css
 4. Tugas-js
 5. Tugas-midProject
 6. Tugas-php
 7. Tugas-finalProject
 Daftar perintah GiT
$ git checkout -b Tugas-git
Switched to a new branch 'Tugas-git'

Lenovo@LAPTOP-UQUNMNRF MINGW64 /c/tugaspw/belajarGIT (Tugas-git)
$ touch Tugas-git.txt

Lenovo@LAPTOP-UQUNMNRF MINGW64 /c/tugaspw/belajarGIT (Tugas-git)
$ echo "Hari ini aku belajar github" > Tugas-git.txt

Lenovo@LAPTOP-UQUNMNRF MINGW64 /c/tugaspw/belajarGIT (Tugas-git)
$ git status
On branch Tugas-git
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        Tugas-git.txt

nothing added to commit but untracked files present (use "git add" to track)

Lenovo@LAPTOP-UQUNMNRF MINGW64 /c/tugaspw/belajarGIT (Tugas-git)
$ git add Tugas-git.txt
warning: in the working copy of 'Tugas-git.txt', LF will be replaced by CRLF the next time Git touches it

Lenovo@LAPTOP-UQUNMNRF MINGW64 /c/tugaspw/belajarGIT (Tugas-git)
$ git status
On branch Tugas-git
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   Tugas-git.txt


Lenovo@LAPTOP-UQUNMNRF MINGW64 /c/tugaspw/belajarGIT (Tugas-git)
$ git commit -m "Menambahkan dan mengubah Tugas-git.txt"
Author identity unknown

*** Please tell me who you are.

Run

  git config --global user.email "you@example.com"
  git config --global user.name "Your Name"

to set your account's default identity.
Omit --global to set the identity only in this repository.

fatal: unable to auto-detect email address (got 'Lenovo@LAPTOP-UQUNMNRF.(none)')

Lenovo@LAPTOP-UQUNMNRF MINGW64 /c/tugaspw/belajarGIT (Tugas-git)
$ git config --global user.email "akbarmokogintaaaa@gmail.com"

Lenovo@LAPTOP-UQUNMNRF MINGW64 /c/tugaspw/belajarGIT (Tugas-git)
$ git config --global user.name "akbarmokoginta"

Lenovo@LAPTOP-UQUNMNRF MINGW64 /c/tugaspw/belajarGIT (Tugas-git)
$ git commit -m "Menambahkan dan mengubah Tugas-git.txt"
[Tugas-git 5486a3b] Menambahkan dan mengubah Tugas-git.txt
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-git.txt

Lenovo@LAPTOP-UQUNMNRF MINGW64 /c/tugaspw/belajarGIT (Tugas-git)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

Lenovo@LAPTOP-UQUNMNRF MINGW64 /c/tugaspw/belajarGIT (main)
$ git merge Tugas-git
Updating 7d3d53f..5486a3b
Fast-forward
 Tugas-git.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-git.txt

Lenovo@LAPTOP-UQUNMNRF MINGW64 /c/tugaspw/belajarGIT (main)
$ git push origin main

fatal: User cancelled dialog.
git push origin main
error: unable to read askpass response from 'C:/Program Files/Git/mingw64/bin/git-askpass.exe'
Username for 'https://github.com': error: unable to read askpass response from 'C:/Program Files/Git/mingw64/bin/git-askpass.exe'
Password for 'https://github.com':
remote: No anonymous write access.
fatal: Authentication failed for 'https://github.com/akbarmokoginta/belajarGIT.git/'

Lenovo@LAPTOP-UQUNMNRF MINGW64 /c/tugaspw/belajarGIT (main)
$ git push origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 12 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 331 bytes | 331.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/akbarmokoginta/belajarGIT.git
   7d3d53f..5486a3b  main -> main

Lenovo@LAPTOP-UQUNMNRF MINGW64 /c/tugaspw/belajarGIT (main)
$ git checkout -b Tugas-html
Switched to a new branch 'Tugas-html'

Lenovo@LAPTOP-UQUNMNRF MINGW64 /c/tugaspw/belajarGIT (Tugas-html)
$ touch Tugas-html.txt

Lenovo@LAPTOP-UQUNMNRF MINGW64 /c/tugaspw/belajarGIT (Tugas-html)
$ echo "Hari ini aku belajar github" > Tugas-html.txt

Lenovo@LAPTOP-UQUNMNRF MINGW64 /c/tugaspw/belajarGIT (Tugas-html)
$ git add Tugas-html.txt
warning: in the working copy of 'Tugas-html.txt', LF will be replaced by CRLF the next time Git touches it

Lenovo@LAPTOP-UQUNMNRF MINGW64 /c/tugaspw/belajarGIT (Tugas-html)
$ git status
On branch Tugas-html
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   Tugas-html.txt


Lenovo@LAPTOP-UQUNMNRF MINGW64 /c/tugaspw/belajarGIT (Tugas-html)
$ git commit -m "Menambahkan dan mengubah Tugas-html.txt"
[Tugas-html e738427] Menambahkan dan mengubah Tugas-html.txt
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-html.txt

Lenovo@LAPTOP-UQUNMNRF MINGW64 /c/tugaspw/belajarGIT (Tugas-html)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

Lenovo@LAPTOP-UQUNMNRF MINGW64 /c/tugaspw/belajarGIT (main)
$ git merge Tugas-html
Updating 5486a3b..e738427
Fast-forward
 Tugas-html.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-html.txt

Lenovo@LAPTOP-UQUNMNRF MINGW64 /c/tugaspw/belajarGIT (main)
$ git push origin main
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Delta compression using up to 12 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (2/2), 303 bytes | 303.00 KiB/s, done.
Total 2 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/akbarmokoginta/belajarGIT.git
   5486a3b..e738427  main -> main

Lenovo@LAPTOP-UQUNMNRF MINGW64 /c/tugaspw/belajarGIT (main)
$ git checkout -b Tugas-css
Switched to a new branch 'Tugas-css'

Lenovo@LAPTOP-UQUNMNRF MINGW64 /c/tugaspw/belajarGIT (Tugas-css)
$ touch Tugas-css.txt

Lenovo@LAPTOP-UQUNMNRF MINGW64 /c/tugaspw/belajarGIT (Tugas-css)
$ echo "Hari ini aku belajar github" > Tugas-css.txt

Lenovo@LAPTOP-UQUNMNRF MINGW64 /c/tugaspw/belajarGIT (Tugas-css)
$ git add Tugas-css.txt
warning: in the working copy of 'Tugas-css.txt', LF will be replaced by CRLF the next time Git touches it

Lenovo@LAPTOP-UQUNMNRF MINGW64 /c/tugaspw/belajarGIT (Tugas-css)
$ git status
On branch Tugas-css
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   Tugas-css.txt


Lenovo@LAPTOP-UQUNMNRF MINGW64 /c/tugaspw/belajarGIT (Tugas-css)
$ git commit -m "Menambahkan dan mengubah Tugas-css.txt"
[Tugas-css bc966d9] Menambahkan dan mengubah Tugas-css.txt
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-css.txt

Lenovo@LAPTOP-UQUNMNRF MINGW64 /c/tugaspw/belajarGIT (Tugas-css)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

Lenovo@LAPTOP-UQUNMNRF MINGW64 /c/tugaspw/belajarGIT (main)
$ git merge Tugas-css
Updating e738427..bc966d9
Fast-forward
 Tugas-css.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-css.txt

Lenovo@LAPTOP-UQUNMNRF MINGW64 /c/tugaspw/belajarGIT (main)
$ git push origin main
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Delta compression using up to 12 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (2/2), 255 bytes | 255.00 KiB/s, done.
Total 2 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/akbarmokoginta/belajarGIT.git
   e738427..bc966d9  main -> main

Lenovo@LAPTOP-UQUNMNRF MINGW64 /c/tugaspw/belajarGIT (main)
$ git checkout -b Tugas-js
Switched to a new branch 'Tugas-js'

Lenovo@LAPTOP-UQUNMNRF MINGW64 /c/tugaspw/belajarGIT (Tugas-js)
$ touch Tugas-js.txt

Lenovo@LAPTOP-UQUNMNRF MINGW64 /c/tugaspw/belajarGIT (Tugas-js)
$ echo "Hari ini aku belajar github" > Tugas-js.txt

Lenovo@LAPTOP-UQUNMNRF MINGW64 /c/tugaspw/belajarGIT (Tugas-js)
$ git add Tugas-js.txt
warning: in the working copy of 'Tugas-js.txt', LF will be replaced by CRLF the next time Git touches it

Lenovo@LAPTOP-UQUNMNRF MINGW64 /c/tugaspw/belajarGIT (Tugas-js)
$ git status
On branch Tugas-js
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   Tugas-js.txt


Lenovo@LAPTOP-UQUNMNRF MINGW64 /c/tugaspw/belajarGIT (Tugas-js)
$ git commit -m "Menambahkan dan mengubah Tugas-js.txt"
[Tugas-js af58bc4] Menambahkan dan mengubah Tugas-js.txt
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-js.txt

Lenovo@LAPTOP-UQUNMNRF MINGW64 /c/tugaspw/belajarGIT (Tugas-js)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

Lenovo@LAPTOP-UQUNMNRF MINGW64 /c/tugaspw/belajarGIT (main)
$ git merge Tugas-js
Updating bc966d9..af58bc4
Fast-forward
 Tugas-js.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-js.txt

Lenovo@LAPTOP-UQUNMNRF MINGW64 /c/tugaspw/belajarGIT (main)
$ git push origin main
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Delta compression using up to 12 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (2/2), 251 bytes | 251.00 KiB/s, done.
Total 2 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/akbarmokoginta/belajarGIT.git
   bc966d9..af58bc4  main -> main

Lenovo@LAPTOP-UQUNMNRF MINGW64 /c/tugaspw/belajarGIT (main)
$ git checkout -b Tugas-midProject
Switched to a new branch 'Tugas-midProject'

Lenovo@LAPTOP-UQUNMNRF MINGW64 /c/tugaspw/belajarGIT (Tugas-midProject)
$ touch Tugas-midProject.txt

Lenovo@LAPTOP-UQUNMNRF MINGW64 /c/tugaspw/belajarGIT (Tugas-midProject)
$ echo "Hari ini aku belajar github" > Tugas-midProject.txt

Lenovo@LAPTOP-UQUNMNRF MINGW64 /c/tugaspw/belajarGIT (Tugas-midProject)
$ git add Tugas-midProject.txt
warning: in the working copy of 'Tugas-midProject.txt', LF will be replaced by CRLF the next time Git touches it

Lenovo@LAPTOP-UQUNMNRF MINGW64 /c/tugaspw/belajarGIT (Tugas-midProject)
$ git status
On branch Tugas-midProject
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   Tugas-midProject.txt


Lenovo@LAPTOP-UQUNMNRF MINGW64 /c/tugaspw/belajarGIT (Tugas-midProject)
$ git commit -m "Menambahkan dan mengubah Tugas-midProject.txt"
[Tugas-midProject ddf66fc] Menambahkan dan mengubah Tugas-midProject.txt
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-midProject.txt

Lenovo@LAPTOP-UQUNMNRF MINGW64 /c/tugaspw/belajarGIT (Tugas-midProject)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

Lenovo@LAPTOP-UQUNMNRF MINGW64 /c/tugaspw/belajarGIT (main)
$ git merge Tugas-midProject
Updating af58bc4..ddf66fc
Fast-forward
 Tugas-midProject.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-midProject.txt

Lenovo@LAPTOP-UQUNMNRF MINGW64 /c/tugaspw/belajarGIT (main)
$ git push origin main
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Delta compression using up to 12 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (2/2), 270 bytes | 270.00 KiB/s, done.
Total 2 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/akbarmokoginta/belajarGIT.git
   af58bc4..ddf66fc  main -> main

Lenovo@LAPTOP-UQUNMNRF MINGW64 /c/tugaspw/belajarGIT (main)
$ git checkout -b Tugas-php
Switched to a new branch 'Tugas-php'

Lenovo@LAPTOP-UQUNMNRF MINGW64 /c/tugaspw/belajarGIT (Tugas-php)
$ touch Tugas-php.txt

Lenovo@LAPTOP-UQUNMNRF MINGW64 /c/tugaspw/belajarGIT (Tugas-php)
$ echo "Hari ini aku belajar github" > Tugas-php.txt

Lenovo@LAPTOP-UQUNMNRF MINGW64 /c/tugaspw/belajarGIT (Tugas-php)
$ git add Tugas-php.txt
warning: in the working copy of 'Tugas-php.txt', LF will be replaced by CRLF the next time Git touches it

Lenovo@LAPTOP-UQUNMNRF MINGW64 /c/tugaspw/belajarGIT (Tugas-php)
$ git status
On branch Tugas-php
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   Tugas-php.txt


Lenovo@LAPTOP-UQUNMNRF MINGW64 /c/tugaspw/belajarGIT (Tugas-php)
$ git commit -m "Menambahkan dan mengubah Tugas-php.txt"
[Tugas-php 0a93a5e] Menambahkan dan mengubah Tugas-php.txt
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-php.txt

Lenovo@LAPTOP-UQUNMNRF MINGW64 /c/tugaspw/belajarGIT (Tugas-php)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

Lenovo@LAPTOP-UQUNMNRF MINGW64 /c/tugaspw/belajarGIT (main)
$ git merge Tugas-php
Updating ddf66fc..0a93a5e
Fast-forward
 Tugas-php.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-php.txt

Lenovo@LAPTOP-UQUNMNRF MINGW64 /c/tugaspw/belajarGIT (main)
$ git push origin main
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Delta compression using up to 12 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (2/2), 254 bytes | 254.00 KiB/s, done.
Total 2 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/akbarmokoginta/belajarGIT.git
   ddf66fc..0a93a5e  main -> main

Lenovo@LAPTOP-UQUNMNRF MINGW64 /c/tugaspw/belajarGIT (main)
$ git checkout -b Tugas-finalProject
Switched to a new branch 'Tugas-finalProject'

Lenovo@LAPTOP-UQUNMNRF MINGW64 /c/tugaspw/belajarGIT (Tugas-finalProject)
$ touch Tugas-finalProject.txt

Lenovo@LAPTOP-UQUNMNRF MINGW64 /c/tugaspw/belajarGIT (Tugas-finalProject)
$ echo "Hari ini aku belajar github" > Tugas-finalProject.txt

Lenovo@LAPTOP-UQUNMNRF MINGW64 /c/tugaspw/belajarGIT (Tugas-finalProject)
$ git add Tugas-finalProject.txt
warning: in the working copy of 'Tugas-finalProject.txt', LF will be replaced by CRLF the next time Git touches it

Lenovo@LAPTOP-UQUNMNRF MINGW64 /c/tugaspw/belajarGIT (Tugas-finalProject)
$ git status
On branch Tugas-finalProject
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   Tugas-finalProject.txt


Lenovo@LAPTOP-UQUNMNRF MINGW64 /c/tugaspw/belajarGIT (Tugas-finalProject)
$ git commit -m "Menambahkan dan mengubah Tugas-finalProject.txt"
[Tugas-finalProject 79ea5ed] Menambahkan dan mengubah Tugas-finalProject.txt
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-finalProject.txt

Lenovo@LAPTOP-UQUNMNRF MINGW64 /c/tugaspw/belajarGIT (Tugas-finalProject)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

Lenovo@LAPTOP-UQUNMNRF MINGW64 /c/tugaspw/belajarGIT (main)
$ git merge Tugas-finalProject
Updating 0a93a5e..79ea5ed
Fast-forward
 Tugas-finalProject.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-finalProject.txt

Lenovo@LAPTOP-UQUNMNRF MINGW64 /c/tugaspw/belajarGIT (main)
$ git push origin main
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Delta compression using up to 12 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (2/2), 272 bytes | 272.00 KiB/s, done.
Total 2 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/akbarmokoginta/belajarGIT.git
   0a93a5e..79ea5ed  main -> main

Lenovo@LAPTOP-UQUNMNRF MINGW64 /c/tugaspw/belajarGIT (main)
$ git merge README.md
merge: README.md - not something we can merge

Lenovo@LAPTOP-UQUNMNRF MINGW64 /c/tugaspw/belajarGIT (main)
