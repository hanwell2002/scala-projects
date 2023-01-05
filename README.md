echo "# scala-projects" >> README.md
git init
git config --global --add safe.directory E:/bootcamps/scala-projects
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin git@github.com:hanwell2002/scala-projects.git
git push -u origin main