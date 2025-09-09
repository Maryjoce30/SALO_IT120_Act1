git init
git branch -M main
git add .
git commit -m "Initial files with basic info"

git checkout -b SALO_B1
git add Profile.txt
git commit -m "Added extra profile info"
git push -u origin SALO_B1

git checkout -b SALO_B2
git add Education.txt
git commit -m "Added extra education info"
git push -u origin SALO_B2

git checkout -b SALO_B3
git add Background.txt
git rm Test.py
git commit -m "Added background info and removed Test.py"
git push -u origin SALO_B3

git checkout -b SALO_B4
git add Readme.txt
git rm Test.py
git commit -m "Added Git commands in Readme and removed Test.py"
git push -u origin SALO_B4


