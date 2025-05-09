# Setting up a new github and local repo


echo "# msse642-2025summer" >> README.md
git init
git add README.md


git config --local user.email "rgranier@regis.edu"
git config --local user.name "Randall Granier"


git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/granierregis/msse642-2025summer.git
git push -u origin main

