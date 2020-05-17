# Change to the directory for your training  
`cd /DEV/kata/`

# Create directory  
`mkdir kata-1`

# Change into the directory  
`cd kata-1`

# Let you show where in the directory system you are  
`pwd`

# Install TypeScript Compiler globally  
`npm install -g typescript`

# Initialize a TypeScript Project  
`tsc --init`

# Search for the string `outDir` in the file `tsconfig.json`, then in the directory  
`grep "outDir" tsconfig.json`, `grep -r "outDir" .`

# Open the tsconfig.json in vi  
`vi tsconfig.json`

# Change to insert mode  
`i`

# Enable and change output folder in the configuration  
`outDir: "dist"`

# Exit insert mode in vi  
`Esc`

# Save the file and exit vi  
`:wq` -> `Enter`

# Search for the string `sourceMap` in the directory with lines  
`grep -nr "sourceMap" .`

# Open the file again with vi  

# Go to the line where you found `sourceMap`  
`:15` (e.g.)

# Change the value of the property to true  
`sourceMap: true`

# Create a git repository  
`git init`

# Add and commit the folder to the git repository  
`git add .` -> `git commit -m "Initial commit"`

# Add a remote server to the git repository  
`git remote add origin www.some-remote-origin.com`

# List remote server of git repository  
`git remote -v`

# Push git repository and branch initially to remote server  
`git push -u origin master` (Command will fail since it is a fake remote server)

# Create a new file `index.ts`  
`touch index.ts`

# Add the following function into the file via vi and save it  
```typescript
const world = 'World';

export const hello = (word: string): string => `Hello ${world}`;
```

# Compile the TypeScript file  
`tsc`

# List all the files in the folder, then list it one line a file, and then with also the hidden files  
`ls`, `ls -l`, `ls -al`

# Let you show the content of the file `dist/index.js`
`less dist/index.js`

# Navigate to the next page in the content
Arrow right button

# Exit the presentation mode
q

# Rename the file `index.ts`to `index-backup.ts`  
`mv index.ts index-backup.ts`

# Remove the file `index-backup.ts` and go one directory up  
`rm index-backup.ts`, `cd ..`

# Remove the directory `kata-1`  
`rm -rf kata-1` (recursively and force)
