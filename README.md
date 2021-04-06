#### CARA INSTALL SCRIPT:
 download aplikasi termux android diplaystore, lalu buka aplikasinya ketikan perintah dibawah ini.
 ```
pkg update && pkg upgrade
pkg install python git
pip install requests bs4 futures
rm -rf locked
git clone https://github.com/CrackerSilent67/locked
cd locked
cythonize -i lock.c && rm -rf lock.c
python run.py
 ```
