Repo de Angel

Para crear  un nuevo repositorio

pasos:

mkdir repo1
cd repo1
echo "mi primer archico, este es el README.md" >> README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin git@github.com:[username]/repo1
git push -u origin master
