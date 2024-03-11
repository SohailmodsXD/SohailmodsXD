
apt update -y && apt upgrade -y
pkg install git python-pip
pkg install tesseract
git clone https://github.com/SohailmodsXD XD/Zefoy
cd "Zefoy"
python -m pip install pytesseract
python -m pip install -r requirements.txt
python Run.py