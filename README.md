# Clio UI kit
The Clio UI Kit is a sketch file containing all the assets used to design product at Clio. It also contains documentation and design guidelines, and comes with commands for running and maintaining the files.

<img src="images/ui-kit-banner.png" width="888">

**Features**
* Symbol overrides
* Layer styles

## Command Quick Reference
1. `npm run docs` Runs documentation in a web browser
2. `npm run sketch` Opens the original source .sketch file
2. `npm run update` Updates to the latest version

## Dependencies
* Sketch app
* Git - [Installing Git](https://www.atlassian.com/git/tutorials/install-git)
* npm - [Installing npm](https://www.npmjs.com/get-npm)

## Installing
There are two ways to start using the UI kit. Installing via the command line is recommended - it will install directly into your sketch templates folder.

### Install as a sketch template (recommended)

Clone the repo into your sketch templates folder.
```
cd ~/Library/Application\ Support/com.bohemiancoding.sketch3/Templates/ && git clone git@github.com:gthierman/ui-kit.git && cd ui-kit
```
Open sketch and create a document using "New from template" or run
```
npm run sketch
```
### Install to any directory
In a directory of your choice, run
```
git clone git@github.com:gthierman/ui-kit.git && cd ui-kit
```
Run `npm run new` to open a new untitled file saved to your desktop.

### Download the source

Download the source in the "Clone or download" menu.
Open the file in sketch and save it as a template.<br>
Now create documents using "New from template".

## Updating
Switch to the project directory and run
```
alias ui-kit = "~/Library/Application\ Support/com.bohemiancoding.sketch3/Templates/ui-kit"
cd ui-kit
npm run update
```

## Run the docs
The docs contain design guidelines and other instructions on how to use the UI kit.

 run
```
cd ui-kit
npm run docs
```
A browser window will open and the docs will appear after a few seconds.

<!-- ## Symbol overrides
<img src="images/symbol-overrides.png" width="808"> -->
