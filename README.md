# cppcode

This is a simple extension for competitive programmers who enjoy coding using C++ and VS code.

The aim of this extension is reducing your code and debugging period and thus increasing your pace in solving problems.

## Usage

Open a file with `.cpp` extension and type "cppcode" or even shorter and type "enter" or "tab".

Node :- You can always edit the snippet according to your requirements and the edited snippet will also start with the same name "cppcode"

![Seems like the preview is not working click here to see the preview: https://github.com/Ajitesh13/cppcode/raw/master/presentation/2-c.gif](/presentation/2-c.gif)

## Features

* Code snippet in equipped with basic structure of cpp code you would like to use while solving a problem in a competitve programming contest to make your coding fast and efficient.

* All the debugging flags useful for a competitve programmer is also added in a comment in the code snippet. So no need to waste time on debugging silly mistakes in your code (You can directly use the command provided there to compile your cpp file and avoid silly errors, mainly runtime). :p

* For more information on the provided g++ flags, please have a look [here](https://codeforces.com/blog/entry/15547)

## Requirements

No additonal requirements apart from Visual Studio Code. [Click Here](https://code.visualstudio.com/download) to download.

## Install your extension

1. To start using your extension with Visual Studio Code first clone the repo with the command:

```bash
        git clone https://github.com/Ajitesh13/cppcode.git
```

2. copy it into the `<user home>/.vscode/extensions` folder and restart Code (For Linux and Mac users, for windows search for `.vscode/extensions` and paste it there).

   * For linux user, if cloned into `home` directory use the command to copy the cloned repo:

```bash
         cp -r cppcode .vscode/extensions

```

1. This extension is applied to publish on [VS Code Extension Marketplace](https://marketplace.visualstudio.com/vscode). So very soon you are going to find this extension there and can  directly download it.  

## Edit your extension

* You can always edit this extension according to your convinience and needs. Follow the following steps after installing the extension:

1. go to <user home>/.vscode/extensions/cppcode/snippets/snippets.json
2. It contains the required code snippet in json format, make all the editing in that json file and restart vs code to see the changes

## Contribution to this project

* Feel free to give a PR to improve this project, have a look over [CONTRIBUTING.md](CONTRIBUTING.md) for understanding this project anatomy.
* Open a issue if you could discover a problem in the extension or for any new idea.  

**Happy Coding!!!**
