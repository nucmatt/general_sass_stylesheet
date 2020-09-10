# Project Name

General Sass Stylesheet

## Table of contents

- [General info](#general-info)
- [Technologies](#technologies)
- [Setup](#setup)
- [Features](#features)
- [Status](#status)
- [Inspiration](#inspiration)
- [Contact](#contact)

## General info

This is intended to be a generalized stylesheet to be used with most any project, big or small. I plan to add interesting styles I come across or create during projects as my programming experience increases. It is also a way to practice using Sass!

## Technologies

- Sass 1.26.10 with dart2js 2.8.4. This is the initial version I wrote the stylesheet with.
- I use VisualStudioCode as my editor and node/npm as my package manager.

## Setup

To use this scss stylesheet in a project:

- Install sass to your project folder using npm install -g sass. Installing globally gives you access to the sass command, used in step 3.
- Copy the scss folder into your project where you want the files to be held.
- Enter the following command to compile the scss into a usable css file: sass --watch sassfilelocation.scss cssfileoutputlocation. (For example, if your file structure is project_folder/css and project_folder/scss/style.scss the command is sass --watch scss/style.scss css/style.css) Now sass will watch the style.scss folder for changes and automatically output this to a style.css in your css folder. (note this command will create the style.css file itself in the css folder you created. This style.css file is NOT destroyed once you stop the watch command.) -OR-
- With VSCode extension Live Sass Compiler installed simply edit the settings for format and map. Set map to false if you don't want to use a source map. There are various formats you can use in the format setting. Primarily you will be interested in the "savePath": setting. This is where you will enter the path you want the regular css file to be saved to by the extension. (Note: The file path is relative to the root folder where sass was installed, generally the project folder).

## Features

- This stylesheet is intended to be used similar to the way Bootstrap is used by combining and extending classes.

To-do list:

- Nothing specific at the moment.
- If you have an idea/feedback please use the the Github issues page for this project or make a pull request.

## Status

Project is: _in progress_.
I intend to continue adding to this project as I become more experienced.

## Inspiration

Brad Traversy of [Traversy Media](https://www.traversymedia.com/) was a big inspiration for this project and I use a lot of his styling conventions.

## Contact

Created by [Matthew Wessel](https://matthew-a-wessel.dev/) - feel free to contact me!
