# Tobias Locker – CV

[![GitHub Pages](https://img.shields.io/badge/GitHub-Pages-blue)](https://yourusername.github.io/cv/)
[![PDF](https://img.shields.io/badge/PDF-Download-orange)](artifacts/cv.pdf)

This repository contains the **Markdown source** for my professional CV.  
It is designed as a **single-source document** that can be rendered as:  

- A **website** via GitHub Pages  
- A **PDF** via LaTeX  

The CV highlights my experience as a **software architect and developer**, along with my early  
background in **electrical engineering**. The workflow separates content and formatting, making  
updates simple and consistent across formats.

---

## Table of Contents

1. [Build Instructions](#build-instructions)  
2. [Repository Structure](#repository-structure)  
3. [License](#license)  

---

## Build Instructions

### HTML (GitHub Pages)
```bash
pandoc cv.md -o artifacts/cv.html --standalone --css=assets/style.css
