# GitHub-resources

## git-ignore

https://github.com/github/gitignore


## Practice Git Branching Commands 

https://learngitbranching.js.org/


## Git Documentation

https://git-scm.com/doc


## username.github.io

https://coleoguy.github.io/git-pages.tutorial.pdf


## React app Deployment

make new directory <br>
npm init react-app Folder_Name <br>
cd Folder_Name <br>
check : npm start <br> Do changes  <br>
npm install gh-pages --save-dev <br>

Inside <ins> package.json : </ins> <br>
{ <br>
"homepage":"http://saivivek321.github.io/Project_Name" ,<br>
... <br>
} <br>
scripts:{ <br>
"predeploy": "npm run build", <br>
"deploy": "gh-pages -d build" <br>
... <br>
} <br>
<br>

git init  <br>
git remote add origin git_https <br>
git add . <br>
git commit -m "Initial Commit" <br>
npm run deploy <br>
git push -u origin master <br>

