## vscode-js-console-utils

Secondary development based on  [@whtouche](https://twitter.com/whtouche) project

![Video_20230711_093230_316.gif](https://s2.loli.net/2023/07/11/P2obIBT1SGs3kQj.gif)

## Installing

This extension is available for free in the [Visual Studio Code Marketplace]

## Usage

With selection:
* Highlight a variable (or really any text)

* Press Cmd+Shift+L or  Ctrl+Shift+L

* The output (on a new line) will be: 

* ```js
  console.log(  `%c *variable* ` ,'background: #3b8eea; line-height: 22px;border-radius:4px;font-weight: 600',variable);
  
  ```

Without selection:
* Press Cmd+Shift+L
* The output (on the same line) will be: console.log();

To remove console.logs:
* Press Cmd+Shift+D
* This will delete all console.log statements in the current document

Config output template:

![image-20230711213727444](https://s2.loli.net/2023/07/11/EPgHbipdKMoTrkf.png)

## License
[MIT License](LICENSE)