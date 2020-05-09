# Create a new library
- Create new Angular Workspace  
`ng new my-workspace --create-application=false --skipGit=true --skipInstall=true`

- Create a library in the workspace  
  - `cd my-workspace`
  - `ng g library lib-name`

# Create a new app
1. Create a new Angular App with Routing and without versioning and skip install: 
`ng new --routing=true --skipGit=true --skipInstall=true`

                
3. Create a new feature with lazy loading  
`ng g module feature1 --route feature1 --module app.module`

5. Execute npm install
`npm i`

6. Start Angular App  
`ng serve`

7. Stop Angular App  
`Ctrl + C`

8. Start Angular App with AOT
`ng serve --aot`
