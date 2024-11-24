1. Put your project specific component tsx files in src/components
2. Create new project from template:
cp -pr templateProject actualNewProject
cd actualNewProject
rm -rf .git README.txt
git init
npm install
3. Start vite server
npm run dev
4. _gitignore directory will be ignored by git. Put scratch working stuff here like prompt files, test stuff, screenshots...
