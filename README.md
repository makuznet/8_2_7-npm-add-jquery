# jQuery installation

> This repo show artifacts appearing after installation of jQuery library via Node.js Packet Manager — NPM (npm).   

## What is happening
NVM (nvm) — Node.js Version Manager is installed.  
Then Node.js (JavaScript interpreter) itself and NPM (npm) — Node.js Packet Manager are installed.  
Then follows the `npm init` command generating a `package.json` file.   
Then jQuery library is installed via npm.

## Usage 
```shell
cd ~/myproject
git init
git remote -v
git remote add origin https://github.com/makuznet/8_2_7-npm-add-jquery.git 
touch README.md
git add .
git commit -m 'Initial commit'
git push origin --all
npm init
npm install jquery
git add .
git status --porcelain
git commit -m 'NPM initiated and jQuery installed'
git push origin --all
```
## Installation  
jQuery requires Node.js to work.  
NVM (Node Version Manager) gets Node.js installed.  
Node.js has got its NPM (Node Packet Manager), which gets jQuery installed.  

### NVM installation
```bash
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.38.0/install.sh | bash
```
### Node.js installation
```bash
nvm install v14.16.1
```
### jQuery installation
```bash
npm install -g jQuery
npm list
```
## Acknowledgments
This repo was inspired by [skillfactory.ru](https://skillfactory.ru/devops#syllabus) team

## See Also
- [Installing Node.js with nvm](https://gist.github.com/d2s/372b5943bce17b964a79)
- [NPM Docs](https://docs.npmjs.com/)
- []()

## License
Follow all licenses terms and conditions.