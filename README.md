echo "# group1" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/paigesteffan/group1.git
git push -u origin main
git commit -m "update the README.md with link to contributing guide"
