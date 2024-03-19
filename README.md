VS code extension - 

“Extension that makes a google search of the text selected”

Steps:   
### Flow test
- [x] Add a new command - hello world pop up (https://www.freecodecamp.org/news/making-vscode-extension/ )  
- [x] Add that command to the editor context menu. ([link](https://stackoverflow.com/questions/76615668/how-do-i-make-my-extension-add-a-menu-item-to-a-context-menu-in-vs-code))  

### New command  
- [x] Add a new command in the editor context menu to save the text selected ([link](https://stackoverflow.com/questions/73043106/how-to-get-highlighted-text-from-vscode-extension-api))   
- [x] Use that saved text to display that text in pop up  
- [x] Add a new command in the editor context menu to open google.com with query parameter (e.g. https://www.google.com/search?q=sfd )
([link](https://github.com/Microsoft/vscode/issues/11848#issuecomment-246197007))  
- [x] Provide the selected (and saved if needed) text to this google search
- [x] install locally by creating a vsix file - ([link](https://code.visualstudio.com/api/working-with-extensions/publishing-extension))  
- [ ] Publish the extension for reuse  
- [ ] Add setting to add prefixed search queries like site:stackoverflow  
