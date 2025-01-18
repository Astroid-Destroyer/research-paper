# Guidelines And Help
Welcome to the project guidelines. This document provides a comprehensive overview of the formatting and content requirements for your project synopsis. Please follow these guidelines to ensure consistency and professionalism in your documentation.

# Table of Content
1. [Formatting Instructions](#formatting-instructions)
2. [Paragraphs and Spacing](#paragraphs-and-spacing)
3. [Paper Synopsis Content](#paper-synopsis-content)
4. [Tools Installation](#installation-help)
5. [Cloning the Repository](#cloning-the-repository)

## Formatting Instructions

Ensure that your document adheres to the following formatting standards to maintain uniformity across all submissions.

## Paragraphs and Spacing

1. **Font:** Times New Roman
2. **Size:** 12pt
3. **Heading:** 14pt (*bold*)
4. **Subheading:** 12pt (*bold*)
5. **Paper Size:** A4
6. **Alignment:** Justified

## Paper Synopsis Content

1. Overview of Project
2. Literature Review
3. System Block Diagram
4. Project Methodology
5. Technical Platform
6. Expected Result
7. Scope of Further Improvements
8. References

## Installation Help

To set up your environment for working on this project, follow these steps:

1. **Install Scoop Package Manager**

    Scoop is a command-line installer for Windows. To install Scoop, open PowerShell and run the following command:

    ```powershell
    iwr -useb get.scoop.sh | iex
    ```
    `or`
    manually install **Scoop Package Manager**

2. **Install MikTeX**

    MikTeX is a distribution of the TeX/LaTeX typesetting system. Use Scoop to install MikTeX by running:

    ```powershell
    scoop bucket add main
    scoop install main/miktex
    ```

3. **Install LaTeX Workshop Extension**

    **LaTeX Workshop** is a popular extension for Visual Studio Code that provides rich support for LaTeX. To install it:

    - Open Visual Studio Code
    - Go to the Extensions view by clicking on the Extensions icon in the Activity Bar on the side of the window or by pressing `Ctrl+Shift+X`
    - Search for "LaTeX Workshop" by James Yu and click Install

4. **Create and Edit .tex Files**

    Once you have installed the necessary tools, you can start creating and editing `.tex` files. Open Visual Studio Code, create a new file with a `.tex` extension, and start writing your LaTeX document.

5. **(Optional) Setup formatter**
    Setting up the Latex Workshop is very easy.

    - Goto Visual Studio code Settings.
    - Search for `latex-workshop formatting:latex` and select `latexindent` as formatter.
    - More customization options can be found like tab size and auto compile.

## Cloning the Repository

To clone the repository, use the following command:

```bash
git clone https://github.com/Astroid-Destroyer/research-paper.git
```
