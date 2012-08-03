diplLatex
=========


## Download

Per Git

```bash
$ git clone https://github.com/Dignifiedquire/diplLatex.git
```
oder einfach [Zip Download](https://github.com/Dignifiedquire/diplLatex/zipball/master)


## Verwendung

BibTex ausführen

```bash
$ bibtex main
```

Kompilieren `tex` nach `dvi` nach `ps` nach `pdf`

```bash
$ latex main.tex && dvips -Ppdf main.dvi -o && ps2pdf main.ps
```

