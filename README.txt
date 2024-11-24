1. Put your project specific component tsx files in src/components

2. Create new project from template:
cp -pr templateProject actualNewProject
cd actualNewProject
rm -rf .git README.txt
npm install
git init
git add .
git commit -a -m "first commit"
git branch -M main
git remote add origin https://github.com/ja2z/YOURREPOHERE.git
git push -u origin main

3. Start vite server
npm run dev

4. _gitignore directory will be ignored by git. Put scratch working stuff here like prompt files, test stuff, screenshots...
