#Mon Projet Netmiko
mkdir amal-mabrouk-netmiko
cd amal-mabrouk-netmiko
git inti
echo "#Mon Projet Netmiko" > README.md
git add README.md
 git commit -m "Ajout du fichier README"
nano main.py
git add main.py
 git commit -m "Ajout du script python principal"
git log --oneline
git checkout -b feature/netmiko
pip install netmiko
git chekout
 git remote add origin https://github.com/amalmuk/amal-mabrouk-netmiko.git
git branch -M main
git push -u origin main

