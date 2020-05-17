# Go to DEV/kata folder
`cd DEV/kata`

# Create the new Angular Workspace my-work  
`ng new my-work --create-application=false --skipGit=true --skipInstall=true`

# Create a library in the workspace  
  - `cd my-workspace`
  - `ng g library lib-name --skipInstall=true`

# Create a new app
1. Create a new Angular App with Routing and without versioning and skip install: 
`ng new --routing=true --skipGit=true --skipInstall=true`
                
# Create the new feature my-feat with lazy loading  
`ng g module my-feat --route feature1 --module app.module`

# Create the component my-comp in my-feature module
`ng g c my-feat/my-comp`

# Execute npm install
`npm i`

# Start Angular App with JIT
`ng serve`

# Stop Angular App  
`Ctrl + C`

# Start Angular App with AOT
`ng serve --aot`
