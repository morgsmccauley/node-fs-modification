# File system modification tools

Node library exposing two functions:
1. `getFiles(dir, includedExt)` - get files in `dir` recursively including only extensions specified in `includedExt`
2. `removeFileOrDirectory(path)` - remove the file/dir specfied by `path`

`./App` contains dummy data to test on, `index.js` contains library.

Code was written as an exercise to practice functional programming and ES7 async/await. More for reading rather than running.
