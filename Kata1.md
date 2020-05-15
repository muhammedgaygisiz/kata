- Change to the directory for your training
`cd /DEV/kata/`

- Create directory
`mkdir kata-1`

- Change into the directory
`cd kata-1`

- Let you show where in the directory system you are
`pwd`

- Install TypeScript Compiler globally
`npm install -g typescript`

- Initialize a TypeScript Project
`tsc --init`

- Open the tsconfig.json in vi
`vi tsconfig.json`

- Change to insert mode in vi
`i`

- Add output folder and source map to configuration
`
outDir: "dist,
sourceMap: true
`

- Exit insert mode in vi
`Esc`

- Save the file and exit vi
`:wq` -> `Enter`

- Create a git repository
`git init`

- Add and commit the folder to the git repository
`git add .` -> `git commit -m "Initial commit"`

- Add a remote server to the git repository
`git remote add origin www.some-remote-origin.com`

- List remote server of git repository
`git remote -v`

- Push git repository and branch initially to remote server
`git push -u origin master` (Command will fail since it is a fake remote server)

- Create a new file `index.ts`
`touch index.ts`

- Add the following function into the file via vi and save it
```typescript
const world = 'World';

export hello = (word: string): string => `Hello ${world}`;
```

- Compile the TypeScript file
`tsc`

- List all the files in the folder, then list it one line a file, and then with also the hidden files
`ls`, `ls -l`, `ls -al`

- Rename the file `index.ts`to `index-backup.ts`
`mv index.ts index-backup.ts`

- Search for the string `hello` in the file `index-backup.ts`, then in the directory, then with the lines where it is found
`grep "hello" index-backup.ts`, `grep -r "hello" .`, `grep -nr "hello" .`

- Remove the file `index-backup.ts` and go one directory up
`rm index-backup.ts`, `cd ..`

- Remove the directory `kata-1`
`rmdir kata-1`
