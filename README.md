…or create a new repository on the command line
<p>
echo "# hello-world" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/michaelblankenship/hello-world.git
git push -u origin main
</p>

…or push an existing repository from the command line

git remote add origin https://github.com/michaelblankenship/hello-world.git
git branch -M main
git push -u origin main
