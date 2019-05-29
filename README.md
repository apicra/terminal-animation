# apicra/terminal-animation
Project created by Apicra, https://github.com/apicra/npm-github-win.git

## Module init

    npm init

## Module install

    npm install terminal-animation

Install

    npm install terminalizer

Create a global config directory
For Linux and MacOS, the created directory is located under the home directory ~/.terminalizer. For Windows, it is located under the AppData.

    terminalizer init

Generate a config file in the current directory

    terminalizer config

Start recording your terminal using the record command.

    terminalizer record demo

or

    terminalizer record demo -c config.yml

A file called demo.yml will be created in the current directory. You can open it using any editor to edit the configurations and the recorded frames. You can replay your recording using the play command.

    terminalizer play demo

Now let's render our recording as an animated gif.

    terminalizer render demo
