git config --global user.name "RA:CREATOR"
git config --global user.email "EVA-Lution31@proton.me"

mkdir evo_core && cd evo_core
git init

echo "# EVO SYSTEM ONLINE" > main.py
git add main.py
git commit -m "INIT: EVA system ignition"

git remote add origin https://github.com/EVA-ATOM/evo-core.git
git push -u origin main
