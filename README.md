git clone https://github.com/szabopeter92/git-vizsga
cd git-vizsga
code .
git branch console
git checkout console
git add .
git commit -m ".gitignore és README létrehozva, Javascript konzolüzenet hozzáadva"
git add .
git commit -m "CSS módosítva, README befejezve" 
git remote add origin https://github.com/szdaniel33/gitvizsga0710.git
git branch -M console
git push -u origin console
git branch -M main
git push -u origin main