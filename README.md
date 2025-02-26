
   git --version
   mkdir git-demo
   cd git-demo
   git init
   echo "# Git Demo Project" > README.md
   git add README.md
   git commit -m "Initial commit: Added README.md"
     git remote add origin https://github.com/your-username/git-demo.git
     git branch -M main
     git push -u origin main
   git branch feature-branch
   git checkout feature-branch
   echo "## Additional Details" >> README.md
   git add README.md
   git commit -m "Updated README with additional details"
   git push -u origin feature-branch
   git checkout main
   git merge feature-branch
   git push origin main
 

