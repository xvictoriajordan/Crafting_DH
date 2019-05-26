    1  mkdir wget-activehistory
    2  cd wget-activehistory
    3  wget http://activehistory.ca/papers/
    4  wget -r --no-parent -w 2 --limit-rate=20k http://activehistory.ca/papers/
    5  wget -m -w 2 --limit-rate=20k http://activehistory.ca
    6  history > exercise-2.1.md
    7  pwd
    8  home
    9  clear
   10  cd
   11  mkdir war-diary
   12  cd war-diary
   13  pwd
   14  cd~
   15  cd ~
   16  cd war-diary
   17  nano urls.py
   18  python urls.py
   19  ls
   20  nano urls.txt
   21  wget -i urls.txt -r --no-parent -nd -w 2 --limit-rate=100k
   22  cd
   23  history > war-diary-commands.md
