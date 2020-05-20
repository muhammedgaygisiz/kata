# Go to DEV/kata folder
`cd DEV/kata`

# Create the new Angular Workspace `my-work`  
`ng new my-work --create-application=false --skipInstall`

# Change into the workspace my-work
`cd my-workspace`
  
# Create the library `my-lib` in the workspace  
`ng generate library my-lib --skipInstall`

# Create the application `my-app` in the workspace
`ng generate application my-app --routing=true --style=scss --skipInstall`

# Create the new feature `my-feat1` with lazy loading in my-app 
`ng g module my-app/my-feat1 --route feature1 --project my-app --module app.module`

# Create the component `my-comp` in my-feat1 module
`ng g c my-feat/my-comp`

# Create a second app `my-app2` in the workspace
`ng generate application my-app2 --routing=true --style=scss --skipInstall`

# Create a second application `my-feat2` with lazy loading in my-app2
`ng generate module my-feat2 --routing feature2 --project my-app2 --module app.module`

# Create a component `my-comp2`in my-feat2 module
`ng generate component my-feat2/my-comp2`

# Execute npm install
`npm i`

# Start my-app with JIT
`ng serve`

# Stop Angular App  
`Ctrl + C`

# Start my-app2 with AOT
`ng serve --aot`
