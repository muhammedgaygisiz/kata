# Go to DEV/kata folder
`cd DEV/kata`

# Create the new Angular Workspace `my-work`  
`ng new my-work --create-application=false --skipInstall=true`

# Change into the workspace my-work
`cd my-workspace`
  
# Create the library `my-lib` in the workspace  
`ng generate library my-lib --skipInstall=true`

# Create the application my-app in the workspace
`ng generate application my-app --routing=true --skipInstall=true`
                
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
