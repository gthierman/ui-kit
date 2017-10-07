# Clio UI kit
The Clio UI Kit

## Dependencies
* Sketch app
* Git - [Installing gitbooks](https://www.atlassian.com/git/tutorials/install-git)
* Gitbook - run `npm install gitbook-cli -g` from the command line
* npm - [Installing npm](https://www.npmjs.com/get-npm)

Sketch is required to open the .sketch file. Git, gitbook, and npm are required if you want to manage the UI kit via the command line.

#### Install with command line
This assumes you are setup on git.

Clone the repo into your sketch templates folder.
```
cd ~/Library/Application\ Support/com.bohemiancoding.sketch3/Templates/ && git clone git@github.com:gthierman/ui-kit.git && cd ui-kit
```
Open sketch and create a document using "New from template".

#### Download the source

Click the download zip link.


## Run the kit with 2 commands
1. `npm run docs` Gets the latest version of the UI kit
2. `npm run sketch` runs the documentation
2. `npm run update` Updates to the latest version

<!-- #### `ui-kit-update`
1. Open the console
2. Enter the command "ui-kit"
3. Enter the command "git pull"
4. Open a "New from template" in sketch. The file should reflect the latest. -->

#### `ui-kit-docs`
1. Install gitbooks with `npm install gitbook-cli -g`
1. Open the console.
2. In new console tab or window, enter the command "ui-kit-docs"
3. Wait for the docs to boot up and visit http://localhost:4000

## Plugins
Links to essential plugins will go here.
#### Essential
* Relabel button

#### Useful
* Symbol organizer

## Symbol overrides
![Symbol overrides](images/symbol-overrides.png)
