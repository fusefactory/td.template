<p align="center">
  <a href="" rel="noopener">
  <!---img width=200px height=200px src="https://i.imgur.com/6wj0hh6.jpg" alt="Project logo" --->
  </a>
</p>

<h3 align="center">fuse* | Touchdesigner template</h3>


---

<p align="center"> 
Simple template to start any Touchdesigner project.

<br> 
</p>

## 📝 Table of Contents
- [About](#about)
- [Getting Started](#getting_started)
- [Deployment](#deployment)
- [Usage](#usage)
- [TODO](#TODO.md)
- [Acknowledgments](#ack)

## 🧐 About <a name = "about"></a>
The project consists in a folder hierarchy and a template .toe file.
The standard project should be organized as follows:
- data: should contain all data, from images to audio files or fonts.
- scripts: general purpose scripts, often related to general behavior (what to do on program start) or scripts running on another Python instance.
- toxlib: use the externalization process described below.
    - each module should have a folder containing the .tox file and the scripts used inside it.

## 🏁 Getting Started <a name = "getting_started"></a>

### Prerequisites

* Tested and created on Windows 11 using Touchdesigner 2022.24200
* Conda environment tested using [Miniconda3](https://docs.conda.io/en/latest/miniconda.html).

<br>

## 🚀 Deployment <a name = "deployment"></a>
<br>
<br>

## 🎈 Usage <a name="usage"></a>
### Externalization process
Inspired by [this guide](https://matthewragan.com/2018/11/28/touchdesigner-save-external/) by Matthew Ragan.

* When you create a module, start creating a Base component.
* Navigate inside it and press CTRL+W to save. Locate it inside the ./toxlib folder.
* When you create a script (.py, .glsl etc...), right click on it and save it inside the module folder ./toxlib/YourModel. Remember to sync the DAT with the file so that any changes made inside TD will be reflected on the file and vice versa.
* If you create an [Extension](https://derivative.ca/UserGuide/Extensions), save the corresponding .py file as yourClassEXT.py. 

<br>

## 🔨 Version History <a name="versioning"></a>

* 0.1
    * Initial Release

<br>

## Acknowledgments <a name="ack"></a>

Inspiration, code snippets, etc.
* [Matthew Ragan resources](https://matthewragan.com/teaching-resources/touchdesigner/)
* [Official Derivative Youtube](https://www.youtube.com/@TouchDesignerOfficial)
* ...

<br>

## ✏️ TODO <a name="todo"></a>