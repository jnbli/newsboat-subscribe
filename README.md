# Newsboat Subscribe To YouTube Channel

## Purpose
Add youtube channels to newsboat list of subscriptions through a single terminal command

## Installation
1. Install newsboat
	- on macos, run `brew install newsboat`
2. Add the **subscribe** executable to PATH
	- Add the following to your shell settings file the following: `export PATH="{path to the folder containing subscribe executable}:$PATH"`
3. Ensure the .newsboat folder contains the two files: **config** and **urls**
	- make sure the content of **config** file is `browser "open %u"` for macos
	- make sure the urls folder is blank or already containing some youtube channel subscriptions

## Usage
In terminal type `subscribe` followed by the urls of the youtube channel you want to add then hit enter. If you are confused just type `subscribe` in terminal and hit enter. The command will give you information on what to do next.