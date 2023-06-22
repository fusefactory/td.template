# fuse* - Touchdesigner template

Simple template to start any Touchdesigner project.

## Description

The project consists in a folder hierarchy and a template .toe file.
The standard project should be organized as follows:
- data: should contain all data, from images to audio files or fonts.
- scripts: general purpose scripts, often related to general behavior (what to do on program start) or scripts running on another Python instance.
- toxlib: use the externalization process described below.
    - each module should have a folder containing the .tox file and the scripts used inside it.

## Getting Started

### Dependencies

* Tested and created on Windows 11 using Touchdesigner 2022.24200
* Conda environment tested using [Miniconda3](https://docs.conda.io/en/latest/miniconda.html).

### Externalization process
Inspired by [this guide](https://matthewragan.com/2018/11/28/touchdesigner-save-external/) by Matthew Ragan.

* When you create a module, start from a Base component.
* Navigate inside it and press CTRL+W to save it. Locate it inside the ./toxlib folder.
* When you create a script (.py, .glsl etc...), right click on it and save inside the module folder ./toxlib/YourModel. Remember to sync the DAT with the file so that any chances made inside TD will be reflected on the file and vice versa.
* If you create an [Extension](https://derivative.ca/UserGuide/Extensions), save the corresponding .py file as yourClassEXT.py. 

## Version History

* 0.1
    * Initial Release


## Acknowledgments

Inspiration, code snippets, etc.
* [Matthew Ragan resources](https://matthewragan.com/teaching-resources/touchdesigner/)
* [Official Derivative Youtube](https://www.youtube.com/@TouchDesignerOfficial)
* ...
