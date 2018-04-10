# vs2017-Angluar-Template-with-mdc-web
VS2017 .NET Core with Angular Templated and angular-mdc/web

This repository is related to the following stackoverflow question:
https://stackoverflow.com/questions/49720843/how-to-implement-angular-mdc-web-in-net-core-angular-vs2017-template

Pre requirements:
* vs2017 community edition 15.6.5
* npm 5.8.0
* vs2017 menu Tools\Options...\Projects and Solutions\Web Package Management
  * set `$(PATH)`entry to the top of the list (use the arrows on the top right corner)

HowTo:

1. Clone this repo with vs2017
2. close vs2017
3. open node.js command promt
4. go to the repo directory
5. `rmdir /Q /S node_modules (repeat until no messages comming up)
6. `npm install`
7. `npm run build:vd`
8. open vs2017
9. wait until all package resores are finished
7. hit F5 vs2017 to start the project

If its not working try to start again with step 4.

### This repo is for reproducing something strange with mdc-buttons -> so, don't expect everything works correctly

## There is only one button with angular-mdc/web. The rest of the project you have to do it by yourself :)