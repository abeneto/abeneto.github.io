---
title: "Aplicacions Ofimàtiques"
subtitle: "Activitats 14 - 15"
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
  - \fancyhead[R]{\includegraphics[width=170pt,height=50pt]{../../../assets/fse.png}}
  - \fancyfoot[C]{\thepage}
  - \renewcommand{\headrulewidth}{0pt}
  - \renewcommand{\footrulewidth}{0pt}
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
3. [Activitat 14](#activitat-14)
4. [Activitat 15](#activitat-15)

## Introducció<a id="introduccio"></a>

La pràctica ens introdueix en l'ús dels gràfics i taules en **Writer**.

## Objectius<a id="objectius"></a>

- Gràfics estadístics
- Introducció a les taules
- Crear taules
- Formatar taules
- Convertir text en taula

\vfill

\begin{center}
\includegraphics[height=32pt]{../../../assets/llicencia.png}
\end{center}

\begin{center}
\footnotesize{
\textit{Apunts Aplicacions Ofimàtiques - 1SMX} by \href{https://github.com/abeneto}{Luis García} is licensed under \href{https://creativecommons.org/licenses/by-nc-sa/4.0/?ref=chooser-v1}{Creative Commons Attribution-NonCommercial-ShareAlike 4.0}
}
\end{center}

\newpage

## Activitat 14<a id="activitat-14"></a>

### Objectiu:
Formatar taules

### Desenvolupament de l’activitat:

#### Creació de la taula i introducció de dades

1. Crea un document en blanc.
2. Dona un format horitzontal a la pàgina.
3. Crea una taula de 6 columnes i 28 files.
4. Escriu el contingut que es troba en el document `Personal.odt`.
5. Dona-li format de text a la columna CP.
6. Ajusta l'ample de les columnes amb ajuda del ratolí.
7. Dona una altura a les files de 1.10 cm.
8. Alinea horitzontalment les dades de les cel·les segons el model.
9. Alinea verticalment centrat les dades de les cel·les.

#### Repetició de l'encapçalament

10. Observa com a la segona pàgina no està la primera fila dels títols.
11. Activa la repetició de l'encapçalament.
12. Observa com ja apareix la primera fila de títols en la segona pàgina.

#### Ordenació de les dades

Ordena els empleats per ordre alfabètic de la població i el cognom:

13. Selecciona les dades que vols ordenar, que corresponen a tota la taula.
14. Ordena'ls.
15. Observa el resultat.

#### Inserció d'una fila

16. Situa't en la primera cel·la de la fila de l'empleada de Barcelona, **MÓNICA RODRÍGUEZ CALDERÓN**.
17. Inserta una fila per damunt.
18. Introdueix les seues dades com a empleada.

#### Inserció d'una columna

19. Situa't en la primera cel·la de la primera columna.
20. Inserta una columna davant.
21. Introdueix els codis de personal que desitges.
22. Dona una grandària de lletra de 8 als codis introduïts.
23. Aplica una alineació vertical superior amb la barra d’eines de la taula.
24. Ajusta l'ample de les columnes amb ajuda del ratolí.

#### Divisió de la taula

25. Situa't en el primer empleat de Vilanova i la Geltrú.
26. Divideix la taula copiant l'encapçalament.
27. Inserta un salt de pàgina per a deixar aquesta taula en una pàgina nova.

#### Format automàtic

28. Utilitza el format automàtic per deixar les taules com es mostra al fitxer `Sol_Act_14.pdf`.

\begin{tcolorbox}[colback=customblue!5!white, colframe=customblue!80!black, title=Nota]
Guarda el document generat com \texttt{Act-14.odt}.
\end{tcolorbox}

---

## Activitat 15<a id="activitat-15"></a>

### Objectiu:
Convertir text en taula

### Desenvolupament de l’activitat:

1. Obri el document `Facturas_Texto.odt`
