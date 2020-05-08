# Kata
- Create new Angular Workspace  
`ng new my-workspace --create-application=false`

- Create a library in the workspace  
  - `cd my-workspace`
  - `ng g library lib-name`

1. Create a new Angular App with Routing and without versioning and skip install: 
`ng new --routing=true --skipGit=true --skipInstall=true`

2. Checkout, add and commit to new repository  
  a. `git init`  
  b. `git add .`
  c. `git commit -m "first commit"`  
  d. `git remote add origin https://github.com/muhammedgaygisiz/dummy.git`  
  e. `git push -u origin master`  
                
3. Create a new feature with lazy loading  
`ng g module feature1 --route feature1 --module app.module`

4. Commit Changes  
`git add .`
`git commit -m "Add lazy feature modules"`
`git push`

5. Execute npm install
`npm i`

6. Start Angular App  
`ng serve`

7. Stop Angular App  
`Ctrl + C`

8. Start Angular App with AOT
`ng serve --aot`

9. Stop Angular Module and remove versioning  
  a. `Ctrl + C`  
  b. `git remote rm origin`

10. Check remotes
`git remote -v`

11. Delete Repository on Github via Webinterface
