# LCode

<p align="center">
  <img src="proj/docs/Cover_Image.png" width="700"/>
</p>

![Project Grade](https://img.shields.io/badge/Project_Grade-20%2F20-1E90FF?style=for-the-badge&labelColor=21262d)
![Course](https://img.shields.io/badge/Course-LCOM-1E90FF?style=for-the-badge&labelColor=21262d)
![Course Grade](https://img.shields.io/badge/Course_Grade-19%2F20-1E90FF?style=for-the-badge&labelColor=21262d)
![Year](https://img.shields.io/badge/Year-2025%2F26-1E90FF?style=for-the-badge&labelColor=21262d)

## Project Description

LCode is a code editor built for Minix from scratch on top of a custom driver framework:
- RTC - Lab 1;
- Timer - Lab 2; 
- Keyboard - Lab 3; 
- Mouse - Lab 4; 
- Video Graphics - Lab 5; 
- Serial Port. 

It provides an interactive code editor environment with a file tree, mouse and keyboard text editing (selection, copy/paste, syntax highlighting), and a status bar — all built directly based on our drivers framework.

This was a 4-person team project (myself (up202405484@edu.fe.up.pt), Luís Costa (up202404078@edu.fe.up.pt), Pedro Teixeira (up202404987@edu.fe.up.pt) and Rafael Silva (up202406334@edu.fe.up.pt)) for the Laboratório de Computadores (LCOM) course unit, FEUP, 2025/26.

The full delivered README — features, keyboard shortcuts, environment setup, and the AI-use declaration as submitted to the teacher — is kept intact in [`Delivered_Readme.md`](./Delivered_Readme.md).

> This repository is a personal copy (with full commit history preserved) of the original group submission on FEUP's GitLab.

## My Contribution

I worked mainly on the editor core: 
- model/view/controller for text editing;
- dynamic memory management for the text buffer;
- text selection and copy/paste, 
- file tree;
- line numbering;
- syntax/text-color highlighting

## Environment

To run the project:
```sh
./run.sh proj
```

To test a single driver from the framework:
```sh
./run.sh fw <driver>
```
