---
title: "Aplicacions Ofimàtiques"
subtitle: "Activitats 6 - 8"
#author: "Alberto Benetó"
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
3. [Activitat 6](#activitat-6)
4. [Activitat 7](#activitat-7)
5. [Activitat 8](#activitat-8)


## Introducció<a id="introduccio"></a>

Aquesta pràctica introdueix l’ús bàsic de LibreOffice, centrant-se en les seves funcions clau com la gestió de marcs, Fontwork i l’aplicació d’estils.


## Objectius<a id="objectius"></a>

- Utilitzar marcs.
- Aplicar Fontwork.
- Crear i modificar estils.
- Treballar amb plantilles de documents.
- Utilitzar els assistents de LibreOffice.

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

## Activitat 6<a id="activitat-6"></a>

### Objectiu:
Aprendre a crear i modificar marcs, així com utilitzar el Fontwork.

### Desenvolupament de l’activitat:

1. Obri el document `Produccion.odt`.
2. Retalla el text del títol i els dos primers paràgrafs, crea un **marc** i enganxa la selecció dins d'aquest.
3. Crea **tres nous marcs** i distribueix-los al llarg del document, centrats horitzontalment. Cada marc tindrà una amplada de 5,60 cm, i la longitud dependrà del contingut. Incorpora els següents textos en els respectius marcs:
    - **Marc 1**: "La globalización es un cambio social basado en el incremento de la interconexión entre diferentes sociedades."
    - **Marc 2**: "El liberalismo está a favor de estos cambios y sostiene que el comercio mundial favorece toda la Humanidad a largo plazo."
    - **Marc 3**: "Los grupos antiglobalizadores sostienen que es una fuente de injusticia en el ámbito internacional, y que no promueve un aprovechamiento sostenible de los recursos naturales."
4. Formata tot el document perquè sigui com el del fitxer `Sol_Act_06.pdf`.

### Fontwork

- Crea una portada similar a la del fitxer `Sol_Act_06.pdf`.

\begin{tcolorbox}[colback=customblue!5!white, colframe=customblue!80!black, title=Nota]
Guarda el document generat com `Act-6.odt`.
\end{tcolorbox}
---

## Activitat 7<a id="activitat-7"></a>

### Objectiu:
Aprendre a aplicar estils per donar format al document segons una estructura predefinida.

### Desenvolupament de l’activitat:

1. Aplica estils per crear un document similar al del fitxer `Sol_Act_07.pdf`.

\begin{tcolorbox}[colback=customblue!5!white, colframe=customblue!80!black, title=Nota]
Guarda el document generat com `Act-7.odt`.
\end{tcolorbox}

---

## Activitat 8<a id="activitat-8"></a>

### Objectius:
- Crear estils.
- Modificar estils.
- Eliminar estils.
- Definir estils de pàgina.
- Aplicar estils d'encapçalament.

### Desenvolupament de l’activitat:

1. Obri el document `informe.odt` i crea els següents estils:
   - **Títol Portada**
   - **Subtítol Portada**
   - **Autor**
   
#### Creació d'estils de pàgina:

1. Amb el document anterior, crea els estils:
   - **Portada**
   - **Document**

#### Aplicació d'estils de pàgina:

1. Situa’t a l'inici del document.
2. Assigna l'estil de pàgina **Portada** a aquesta pàgina.
3. Situa’t després de la cinquena línia de text, entre el càrrec de l’autor i el començament del text.
4. Inserta un **Salt manual** amb l’estil **Document** creat anteriorment.

#### Aplicació d'estils amb el teclat:

1. Situa’t a la segona pàgina i fes clic dins el requadre de la capçalera.
2. Escriu: _Departament de publicitat_.
3. Aplica l'estil de paràgraf **Títol 1**.
4. A la següent pàgina, observa que comparteix la mateixa capçalera que l'anterior.
5. Situa’t al requadre del peu de pàgina (de la segona o tercera pàgina) i insereix el número de pàgina.
6. Alinea el número de pàgina a l'esquerra.
7. Situa’t al final del document.
8. Inserta un **Salt de pàgina**, però aquesta vegada selecciona l’estil de pàgina **Predeterminat** per a aquesta nova pàgina.

\begin{tcolorbox}[colback=customblue!5!white, colframe=customblue!80!black, title=Nota]
Guarda el document generat com `Act-8.odt`.
\end{tcolorbox}

---

