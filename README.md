# This guide help to setup vscode.

* Intall VS Code
* Setting > Editor > Font Size : 14
* Setting > Editor > Tab Size : 4
* Setting > Editor > Word Wrap : on
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


## Prettier Extension Setting 
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
    
