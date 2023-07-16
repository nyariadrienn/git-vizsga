git clone https://github.com/szabopeter92/git-vizsga.git
cd git-vizsga
code .
touch .gitignore
(.gitignore elnevezésű fájlban a *.txt, *.doc, *.docx és *.pdf fájlformátumok felvétele)
touch readme.md
git branch console
git commit -m "readme.md, .gitignore fájl és console branch elkészítve"
git status
git add .
git checkout console
(itt: app.js módosítása)
git status
git add .
git commit -m "app.js konzolüzenet beállítva"
(itt: css/body/backgorund-image/rgb módosítása)
git status
git add .
git commit -m "css háttérszín módosítása"
(readme.md feltöltése)
git status
git add .
git commit -m "readme.md feltöltése"
git status
git checkout main
git merge console
git remote add origin https://github.com/nyariadrienn/ git-vizsga.git
git push github
