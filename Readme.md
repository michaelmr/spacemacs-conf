# Installation Steps to fulfill Major Mode dependencies a.k.a layers


## TypeScript  layer

Requires packages: ___yarn__

Install the following packages:

`yarn global add tslint typescript typescript-formatter`

Url for TypeScript layer. See [TS layer](https://github.com/syl20bnr/spacemacs/tree/master/layers/%2Blang/typescript "TypeScriptLayer")

## JavaScript layer

Requires packages: __yarn__

Install the following packages:

`yarn global add tern js-beautify eslint`

Url for JavaScript layer. See [JS layer](https://github.com/syl20bnr/spacemacs/tree/master/layers/%2Blang/javascript "JavaScriptLayer")

# Installation Packages


## nvm installation - Mac OS X

Requires brew package manager. See [Homebrew](https://brew.sh/ "Homesite for Homebrew package manager") 

Execute command:

`brew update && brew install nvm`

Url for nvm project. See [NVM](https://github.com/creationix/nvm "Homesite for nvm node version manager") 

## node and npm installation using nvm

Requires packages: __nvm - node version manager__

Execute command:

`nvm install v6.10.3` for specific version or `nvm install node` for latest version 

Then execute this command to set installed version as default:

`nvm alias default node`

## yarn installation - Max OS X

Requires packages: __nvm - node version manager__

Execute command:

`brew install yarn --without node` in order to use nvm's installed version of node.

Url for yarn project: See [Yarn](https://yarnpkg.com/en/ "Homesite for Yarn package deps manager")

