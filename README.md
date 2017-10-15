# FireSpoof
Automate spoofing phone calls using the FireRTC service. You must have an account registered with https://firertc.com to use. Signing up is free, no worries!

# Description 
Will allow you to spoof bogus phone calls on the fly, and when the call ends it will automatically close the window for you. This program uses selenium in order to do most of the heavy lifting, I just wrote the script. 

I made this for Social-Engineering engagements (Note: I was given permission to legally test in all engagements) in which I needed to dial up a ton of people up pretty fast, sometimes with different numbers. 

# Dependencies 
This program uses Python 3, and will not work with Python 2.7. Some minor changes will be made in the future to support python 2.7.
## Python Installs: 
pip install selenium

### Selenium GeckoDriver Linux Install:

1. wget https://github.com/mozilla/geckodriver/releases/download/v0.18.0/geckodriver-v0.18.0-linux64.tar.gz
2. tar -xvzf geckodriver*
3. chmod +x geckodriver
4. sudo mv geckodriver /usr/local/bin/

# Usage

python phoneSpoofer.py <PhoneToSpoof> <PhoneToCall> <Username for FireRTC> <Password for FireRTC>
  
# Warning

I'm NOT responsible for improper conduct using this code, and neither is FireRTC. Please only use this program under legal pretenses, and make good decisions. 

Cheers!


