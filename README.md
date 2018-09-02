# auto-rap
*auto-rap* is a CPython application using Natural Language Processing (Spacy) and Machine Learning (TBD) to auto-generate dope rap lyrics.

## Recommended Software
Python 3.7  
Pycharm 2018.2.2  
Spacy 2.0.12  
cURL 7.61.0  

### How to Setup 
#### Python
1. Navigate to https://www.python.org/
2. Under the *Downloads* tab, select version 3.7
3. Follow the installation steps, take note to tick the box to add the Python location to the %PATH% variable

#### Pycharm
1. Navigate to https://www.jetbrains.com/pycharm/
2. Download Pycharm community edition
3. Follow the installation steps
4. Once installed select *Check out from Version Control* and click *Git*
5. Enter *https://github.com/JosephYork/auto-rap.git* in the URL field, select whatever directory you want

#### Spacy
1. Open a Command Prompt window
2. Enter `pip install spacy`  
3. Note: If you get a command not found error, confirm your Python directory has been added to your PATH by typing `echo %PATH%` and looking for an entry similar to Python\Python37-32\Scripts  
4. Note: If you get an error for Microsoft Visual C++ 14.0 required, navigate to the following link https://visualstudio.microsoft.com/visual-cpp-build-tools/ and download/install the build tools. Make sure to tick the box for Visual C++ build tools when installing. If this doesn't resolve the issue, run the command `pip install --upgrade setuptools` then try and pip install spacy again.  
  
#### cURL
1. Navigate to https://curl.haxx.se/download.html
2. Download cURL and extract it to a convenient location (eg. `C:\cURL`)
3. Update your %PATH% variable to include the `..\cURL\bin` directory

#### bs4 (BeautifulSoup)
1. Open a command prompt window
2. Enter `pip install bs4`
