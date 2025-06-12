# Project Setup Guide

## 1. Install Anaconda
Download & install: https://www.anaconda.com/
Verify:
conda --version

## 2. Install Android Studio & SDK
Download & install: https://developer.android.com/studio
Set environment variables:
ANDROID_HOME=C:\Users\YourUsername\AppData\Local\Android\Sdk
PATH=%ANDROID_HOME%\platform-tools;%ANDROID_HOME%\emulator;%ANDROID_HOME%\tools;%ANDROID_HOME%\tools\bin;%PATH%
Verify:
adb version

## 3. Install Visual Studio
Download & install: https://visualstudio.microsoft.com/
Select **Desktop development with C++**

## 4. Set Up Python Virtual Environment
Activate existing environment:
source venv/bin/activate  # macOS/Linux
venv\Scripts\activate    # Windows
python app.py

Create & install dependencies if needed:
conda create --name myenv python=3.9
conda activate myenv
pip install -r requirements.txt
python app.py

## 5. Install Node.js
Download & install: https://nodejs.org/
Verify:
node -v
npm -v

## 6. Run the Frontend
npx expo start