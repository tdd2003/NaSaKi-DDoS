# NaSaKi-DDoS
DDoS Attack Panel includes CloudFlare Bypass (UAM, CAPTCHA, BFM, etc..)(It works intermittently. Working on it)

Don't attack any websites you don't own it
This was created for educational purposes
All responsibilities and disadvantages of using this program is for the user.

Usage on Linux : 
git clone https://github.com/tdd2006/NaSaKi-DDoS.git

Install Python3 modules
 - pip3 install -r requirements.txt  or  pip install -r requirements.txt
Install Chrome (or update it lastest version)
 - wget https://dl.google.com/linux/direct/google-chrome-stable_current_amd64.deb
 - apt-get install ./google-chrome-stable_current_amd64.deb

OR
 - python3 setup.py

 - python3 NaSaKiLinux.py


Usage on Windows :

Install python - https://www.python.org
Install Git - https://gitforwindows.org (instruction in telegram-channel. contact @AuraNetz or @CyberEducational or @MiraiLove )

git clone https://github.com/tdd2006/NaSaKi-DDoS/
cd Nasaki
python3 setup.py / py setup.py

python3 nasaki.py / py nasaki.py

Usage on Termux :

pkg install x11-repo
pkg install unstable-repo
pkg update
pkg upgrade
pkg install python3
pkg install git
pkg install wget
pkg install rust
pip install supertools wheel
pip install shutup
git clone https://github.com/tdd2006/NaSaKi-DDoS/
cd Nasaki
export CARGO_BUILD_TARGET=aarch64-linux-android && python3 -m pip install cryptography
export CARGO_BUILD_TARGET==aarch64-linux-android && python3 -m pip install -r requirements.txt
python3 -m pip install httpx[http2]
python3 setup.py
python3 Nasaki.py
