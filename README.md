# This guide help to setup vscode.

* Intall VS Code
* Update Java Home Path : "java.home":"C:\\Program Files\\Java\\jdk1.8.0_111"
* Setting > Editor > Font Size : 14
* Setting > Editor > Tab Size : 4
* Setting > Editor > Word Wrap : off
* Setting > Editor > Format On Save : true
* Setting > Editor > Format On Mode : file/modifications
* Setting > Workbench > Editor > Pinned Tab sizing : normal
* Setting > Explorer > Open Editors > Sort Order : alphabetical
* Setting > Editor > Word Based Suggestions : true
* Setting > Editor > Word Based Suggestions Mode : allDocuments
* Setting > Workbench > Editor > Wrap Tabs : true
* Setting > Editor > Suggest : Preview : true
* Setting > Editor > Bracket Pair Colorization : true
* Setting > Editor > Guide : Bracket Pair : true
* Setting > Editor > Enable Preview : false

## Extensions
  1. Salesforce Extendion Pack
  2. Auto Close Tag
  3. Auto Rename Tag
  4. ES Lint
  5. Indent-Rainbow
  6. JavaScript ES6 code snippets
  7. Prettier Code Formatter
  8. Salesforce Documenter
  9. VSCode-Icons
  10. Git Graph
  11. Git Lens
  12. Bracket Pair Colorizer 2 - (Only if "Setting > Editor > Bracket Pair Colorization" not available in your VSCode version)

## Prettier Extensions Setting 
** Add below in setting JSON file **

  "editor.defaultFormatter": "esbenp.prettier-vscode",
  
  "[javascript]": {
      "editor.defaultFormatter": "esbenp.prettier-vscode"
  }

## Install Sfdx Diff Check
   sfdx plugins:install @salesforce/sfdx-diff
   
## Install Prettier Apex Plugin
  [https://github.com/dangmai/prettier-plugin-apex](https://github.com/dangmai/prettier-plugin-apex)
  
  [https://developer.salesforce.com/tools/vscode/en/user-guide/prettier](https://developer.salesforce.com/tools/vscode/en/user-guide/prettier)
    
