Pour que les commandes « gh » fonctionnent, il faudra au préalable télécharger l’outils CLI GitHub depuis google.  
Une fois le CLI téléchargé et installé :
gh auth login 
mkdir GitHocine
cd ./GitHocine
gh repo create  
resultat : 
? Repository name GitHocine
? Description testfabio
? Visibility Public
? Would you like to add a README file? Yes
? Would you like to add a .gitignore? Yes
? Choose a .gitignore template Actionscript
? Would you like to add a license? No
? This will create 
GitHocine as a public repository on GitHub. Continue? Yes
✓ Created repository hocine699/GitHocine on GitHub
? Clone the new repository locally? Yes
Puis cd pour aller dans le repo
echo dochocine.mf > .\README.md
git add .\README.md
git commit -m version1
git push https://github.com/hocine699/GitHocine
