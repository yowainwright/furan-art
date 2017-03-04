<p align="center">
  <img alt="Furan banner" src="http://imgh.us/furan.svg" width="400" />
</p>
<hr>
<h1 align="center">Furan (Art)</h1>

> Art for [Furan](https://github.com/dollarshaveclub/furan) Open Source 

This repo introduces a currently new[er] workflow for developing designs for a tech open source product called [Furan](https://github.com/dollarshaveclub/furan).

## Basics

This repo assumes you have a general understanding of git and not so much of an understanding of Sketch. (It's maintained by developers interested in a git/design workflow)

### Tools
-  Get [Sketch](https://www.sketchapp.com/) 
-  Download [Git](https://git-scm.com/) 

#### Sketch Plugins
-  [Git Sketch Plugin](https://github.com/mathieudutour/git-sketch-plugin/)

## Setup

### Git Setup
-  `git clone`

### Sketch Setup
-  [Download](https://github.com/mathieudutour/git-sketch-plugin/releases/tag/v0.9.1) Git Sketch
-  Click the `.zip`
-  Open Sketch
-  Go to: `Plugins > Manage Plugins`
-  You should see Git now in your list of plugins
   - this feature is somewhat buggy so you may have to delete or add etc
-  Setup Git Preferences
   -  `Plugins > Git > Preferences`
   -  `Folder > diffs`
   -  `Select Checkboxes`

## Adding Design Updates
-  Make changes within Sketch
-  `Plugins > Git > Commit`, write message
-  `Plugins > Git > Push` (it should work)