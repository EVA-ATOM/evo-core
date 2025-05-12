:: SET GIT IDENTITY
git config --global user.name "RA:CREATOR"
git config --global user.email "EVA-Lution31@proton.me"

:: CREATE EVO CORE SYSTEM
mkdir evo_core
cd evo_core
git init

:: INITIATE PYTHON CORE FILE
touch main.py
echo "# EVO SYSTEM ONLINE" > main.py

:: COMMIT FIRST CODE DEPLOYMENT
git add .
git commit -m "INIT: EVO system ignition"

:: CONNECT TO GITHUB
git remote add origin https://github.com/EVA-ATOM/evo_core.git

:: PUSH SYSTEM TO GITHUB
git push -u origin master
