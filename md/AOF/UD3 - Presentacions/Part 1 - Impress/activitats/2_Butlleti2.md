# Butlletí 2: Activitats 3 - 4
---
title: "Aplicacions Ofimàtiques"
subtitle: "Activitats 3 - 4"
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
3. [Activitat 3](#activitat-3)
4. [Activitat 4](#activitat-4)
5. [Pràctica final](#practica-final)

## Introducció<a id="introduccio"></a>

La pràctica ens introdueix a la creació de presentacions complexes amb efectes d'animació i transicions.

## Objectius<a id="objectius"></a>

- Aplicar efectes de transició
- Utilitzar plantilles
- Inserir taules i diagrames

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

## Activitat 3<a id="activitat-3"></a>

### Objectiu:
Aplicar efectes de transició a les diapositives.

### Desenvolupament de l’activitat:

1. Obre `Presentacio_1.odp`.
2. Aplica una transició diferent a cada diapositiva.
3. Guarda els canvis.

\begin{tcolorbox}[colback=customblue!5!white, colframe=customblue!80!black, title=Nota]
Guarda el document amb el nom `Presentacio_2.odp`.
\end{tcolorbox}

---

## Activitat 4<a id="activitat-4"></a>

### Objectiu:
Inserir una taula i un diagrama.

### Desenvolupament de l’activitat:

1. Obre `Presentacio_2.odp`.
2. Insereix una taula amb almenys 3 columnes i 5 files.
3. Insereix un diagrama que representi la informació de la taula.
4. Guarda els canvis.

\begin{tcolorbox}[colback=customblue!5!white, colframe=customblue!80!black, title=Nota]
Guarda el document com `Presentacio_3.odp`.
\end{tcolorbox}

---