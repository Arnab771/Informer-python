# Informer-python

## Requirements
* Python 3
* Selenium
* Firefox Browser
* Geckodriver

---

## Usage
```bash
git clone https://github.com/Arnab771/Informer-python.git
cd Informer-python
sudo python3 -m pip install -r requirements.txt
```
For windows replace third line with `pip install -r requirements.txt`

Download geckodriver from [here](https://github.com/mozilla/geckodriver/releases)

Add the geckodriver to path. This will depend on the what terminal your using on OS X and Linux (e.g. zsh or bash). After that open the config.py file and put the path of your audio with `audio = 'path/to/audio.mp3'`.

Once done, head to the Informer-python directory and run `python3 informer.py` and for windows, `python informer.py`.

Enter the name of the person and press enter, a Firefox browser window will open with URL https://web.whatsapp.com. Scan the QR code with your whatsapp app on your phone. Open the Chat of the person to track. __DO NOT CHNAGE IT!__ Now you may minimize the window(**This is recommended as Whatsapp will show you offline**). This script will play the audio whenever the person goes online. The entire data is saved to informer.db. You may use the sqlite3 command line tool or download sqlitebrowser from [here](https://sqlitebrowser.org/). For Debian or Ubuntu derivatives use `sudo apt install sqlitebrowser`.
