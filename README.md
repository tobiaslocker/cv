# Curriculum Vitae

[![GitHub Pages](https://img.shields.io/badge/GitHub-Pages-blue)](https://tobiaslocker.github.io/cv/)
[![PDF](https://img.shields.io/badge/PDF-Download-orange)](https://github.com/tobiaslocker/cv/releases/latest/download/cv.pdf)

This repository contains the **Markdown source** for my professional CV.  
It is designed as a **single-source document** that can be rendered as:  

- A **website** via GitHub Pages  
- A **PDF** via LaTeX  

The CV highlights my experience as a **software architect and developer**, along with my early  
background in **electrical engineering**. The workflow separates content and formatting, making  
updates simple and consistent across formats.

## Build Instructions

### HTML (GitHub Pages)
```bash
pandoc cv.md -o artifacts/cv.html --standalone --css=assets/style.css
```
