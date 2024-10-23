---
title: "Aplicacions Ofimàtiques"
subtitle: "Activitats 1 - 2"
author: "Alberto Benetó"
geometry: "left=2cm, right=2cm, top=1.5cm, bottom=3cm"
header-includes:
  - \usepackage{xcolor}
  - \definecolor{customblue}{HTML}{4051B5}
  - \usepackage{fancyhdr}
  - \usepackage{graphicx}
  - \usepackage{tcolorbox}
  - \usepackage{titlesec}
  - \tcbuselibrary{listingsutf8}
  - \pagestyle{fancy}
  - \fancyhf{}
  - \fancyhead[L]{\vspace{15pt} 1r CFGM SMX}
  - \fancyhead[R]{\includegraphics[width=170pt,height=50pt]{../../../assets/fse.png}}  # Inserta el logo a la part esquerra
  - \fancyfoot[C]{\thepage}  # Numeració de pàgines al centre del peu
  - \renewcommand{\headrulewidth}{0pt}  # Elimina la línia sota la capçalera
  - \renewcommand{\footrulewidth}{0pt}  # Elimina la línia sobre el peu
  - \setlength{\headsep}{60pt}
  - \setlength{\footskip}{60pt}
  - |
    \fancypagestyle{plain}{
      \fancyhf{}
      \fancyhead[L]{\vspace{15pt} 1r CFGM SMX}
      \fancyhead[R]{\includegraphics[width=170pt,height=50pt]{../../../assets/fse.png}}
      \fancyfoot[C]{\thepage}
    }
  - |
    \titleformat{\section}{\normalfont\Large\bfseries\color{black}}{}{0em}{}
  - |
    \titleformat{\subsection}{\normalfont\large\bfseries\color{black}}{}{0em}{}
mainfont: "Arial"
output: 
  pdf_document:
    latex_engine: xelatex
---

## Índex
1. [Introducció](#introduccio)
2. [Objectius](#objectius)
3. [Activitat 1](#activitat-1)
4. [Activitat 2](#activitat-2)

## Introducció<a id="introduccio"></a>

La pràctica ens introdueix a l'ús de **presentacions multimèdia** mitjançant **LibreOffice Impress**, així com en l'aplicació de normes bàsiques de composició i disseny.

## Objectius<a id="objectius"></a>

- Creació de diapositives
- Disseny i edició de diapositives
- Inserir imatges i vídeos
- Aplicar efectes d'animació i transicions
- Utilitzar plantilles

\vfill

\begin{center}
\includegraphics[height=32pt]{../../../assets/llicencia.png}
\end{center}

\begin{center}
\footnotesize{
\textit{Apunts Aplicacions Ofimàtiques - 1SMX} by \href{https://github.com/abeneto}{Alberto Benetó} is licensed under \href{https://creativecommons.org/licenses/by-nc-sa/4.0/?ref=chooser-v1}{Creative Commons Attribution-NonCommercial-ShareAlike 4.0}
}
\end{center}

\newpage

## Activitat 1<a id="activitat-1"></a>

### Objectiu:
Crear diapositives i aplicar normes de disseny.

### Desenvolupament de l’activitat:

#### Creació de diapositives

1. Obre **LibreOffice Impress** i crea una nova presentació.
2. Dissenya almenys 3 diapositives que segueixin les normes de composició (títol, contingut, imatges).

\begin{tcolorbox}[colback=customblue!5!white, colframe=customblue!80!black, title=Nota]
Guarda el document generat com `Presentacio_1.odp`.
\end{tcolorbox}

---

## Activitat 2<a id="activitat-2"></a>

### Objectiu:
Inserir imatges i aplicar animacions.

### Desenvolupament de l’activitat:

1. Obre la presentació `Presentacio_1.odp`.
2. Afegeix una imatge a una de les diapositives.
3. Aplica una animació a la imatge inserida.
4. Afegeix efectes d'animació als diferents elements d'aquesta diapositiva.

\begin{tcolorbox}[colback=customblue!5!white, colframe=customblue!80!black, title=Nota]
Guarda els canvis en `Presentacio_1.odp`.
\end{tcolorbox}

---