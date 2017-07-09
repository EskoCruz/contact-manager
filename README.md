### Install Yarn
####Homebrew

You can install Yarn through the Homebrew package manager. This will also install Node.js if it is not already installed.

`brew install yarn`  

If you use nvm you should exclude installing Node.js so that nvm’s version of Node.js is used.

`brew install yarn --ignore-dependencies`

Test that Yarn is installed by running:

`yarn --version`


### Install Angular Material

`yarn add angular angular-material angular-animate angular-aria`

https://yarnpkg.com/en/package/angular-material


Add others

`yarn add angular`

### Packages

Add to devDependencies, peerDependencies, and optionalDependencies respectively:

    yarn add [package] --dev
    yarn add [package] --peer 
    yarn add [package] --optional
    
    
    
### Validation 

Add Angular Validation

`yarn add angular-messages`


Create Yarn file

no`.yarnrc`

Change Directory of node_modules into app directory

`yarn install --modules-folder ./app/node_modules`
