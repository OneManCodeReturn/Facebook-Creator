⚙️ Installation Steps

```bash
pkg update && pkg upgrade -y
pkg install python git -y
pkg install espeak
rm -rf Facebook-Creator
git clone --depth=1 https://github.com/OneManCodeReturn/Facebook-Creator
cd Facebook-Creator
pip install -r requirements.txt
termux-setup-storage
python Creator.py
