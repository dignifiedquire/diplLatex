diplLatex
=========

Dies ist meine Vorlage für eine Diplomarbeit in Mathematik mit LaTex. 
Der Kompilierungsprozess ist relativ aufwendig ermöglicht einem aber dadurch direkt inline 
Grafiken mit `pstricks` zu erzeugen. 

## Download

Per Git

```bash
$ git clone https://github.com/Dignifiedquire/diplLatex.git
```
oder einfach als [Zip Download](https://github.com/Dignifiedquire/diplLatex/zipball/master).


## Verwendung

BibTex ausführen

```bash
$ bibtex main
```

Kompilieren `tex` nach `dvi` nach `ps` nach `pdf`

```bash
$ latex main.tex && dvips -Ppdf main.dvi -o && ps2pdf main.ps
```

## Todo
* Beispiele einfügen