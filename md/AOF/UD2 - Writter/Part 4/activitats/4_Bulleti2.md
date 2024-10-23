---
title: "Aplicacions Ofimàtiques"
subtitle: "Activitats 19 a 22"
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
3. [Activitat 19](#activitat-19)
4. [Activitat 20](#activitat-20)
5. [Activitat 21](#activitat-21)
6. [Activitat 22](#activitat-22)

## Introducció<a id="introduccio"></a>

La pràctica ens introdueix en l’ús bàsic de **LibreOffice Writer**.

## Objectius<a id="objectius"></a>

- Aplicar format de paràgrafs i de caràcters.
- Control de canvis.

## Activitat 19<a id="activitat-19"></a>

### Objectius:
- Aplicar format de paràgrafs i caràcters.

### Desenvolupament de l’activitat:
Reprodueix el document que trobaràs en `Sol_Act_19.pdf`. El document conté aspectes de format de paràgraf i de caràcter que has d'aplicar al teu document:

- **Lletra de tot el document:** Liberation Serif.
- **Primer paràgraf:** 16pt, Subratllat, Negreta.
- **Segon paràgraf:** 12pt, Subratllat, Negreta, Cursiva.
- **Tercer paràgraf:** 12pt. Sangria primer renglon: 1cm; Espaiat: 0,25 cm sobre i 0,25 cm sota.
- **Quart paràgraf:** 12pt. Sangria abans: 1cm, Després: 1cm. Espaiat: 0,25 cm sobre i 0,25 cm sota. Interlineat doble. Justificat.
- **Cinquè paràgraf:** 12pt. Sangria abans: 0,25cm, Després: 1cm. Primer renglon: 0,5cm. Espaiat: 0,25 cm sobre i 0,25 cm sota. Justificat.
- **Sisè paràgraf:** 12pt. Sangria abans: 0,25cm, Després: 0,25cm. Espaiat: 0,25 cm sobre i 0,25 cm sota. Interlineat 1,5.
- **Setè paràgraf:** 12pt. Sangria abans: 0,5cm, Després: 0,5cm. Primer renglon: 1cm. Espaiat: 0,25 cm sobre i 0,25 cm sota. Interlineat 1,5.
- **Vuitè i novè paràgraf:** 12pt. Espaiat: 0,25 cm sobre i 0,25 cm sota. Alineació dreta.

\begin{tcolorbox}[colback=customblue!5!white, colframe=customblue!80!black, title=Nota]
Guarda el document amb el nom `Act-19.odt`.
\end{tcolorbox}

---

## Activitat 20<a id="activitat-20"></a>

### Objectius:
- Inserir una taula i realitzar càlculs dins d'un document de Writer.

### Desenvolupament de l’activitat:
1. Obri un document nou en **LibreOffice Writer**.
2. Insereix una taula amb les següents característiques:
   - **Nombre de files:** 6
   - **Nombre de columnes:** 4
   - **Capçalera**: en la primera fila, introdueix els següents noms de columna:
     - Producte
     - Quantitat
     - Preu unitari (€)
     - Total (€)
3. A les files de **Producte**, escriu els següents noms de productes:
   - Llapis
   - Llibreta
   - Motxilla
   - Estoig
   - Retolador
4. A la columna **Quantitat**, introdueix les següents quantitats per a cada producte:
   - Llapis: 10
   - Llibreta: 5
   - Motxilla: 2
   - Estoig: 3
   - Retolador: 8
5. A la columna **Preu unitari (€)**, introdueix els següents preus:
   - Llapis: 0,50 €
   - Llibreta: 2,00 €
   - Motxilla: 25,00 €
   - Estoig: 4,50 €
   - Retolador: 1,20 €
6. Ara, realitza el càlcul per a la columna **Total (€)**. Utilitza la funció de càlcul de taules de Writer per calcular el total de cada producte multiplicant la **Quantitat** pel **Preu unitari (€)**.

   - Selecciona la cel·la corresponent al **Total** del primer producte.
   - Fes clic a **Taula > Fórmula** o utilitza la fórmula `= <B2>*<C2>` per multiplicar la **Quantitat** pel **Preu unitari**.
   - Repeteix aquesta operació per a cada producte.

7. Finalment, calcula el **Total General** de la columna **Total (€)**:
   - Selecciona la cel·la sota l’últim total de producte.
   - Insereix la fórmula per sumar tots els valors de la columna **Total (€)**: `=SUM <D2:D6>`.

\begin{tcolorbox}[colback=customblue!5!white, colframe=customblue!80!black, title=Nota]
Guarda el document amb el nom `Act-20.odt`.
\end{tcolorbox}


## Activitat 21<a id="activitat-21"></a>

### Objectius:
- Aplicar sangries i interlineat en un document de **LibreOffice Writer**.

### Desenvolupament de l'activitat:

1. Obri un document nou en **LibreOffice Writer**.
2. Escriu el següent text en el document:

   > "La tecnologia avança a un ritme vertiginós, i cada vegada són més les eines que ens permeten treballar de manera més eficient. Aprendre a utilitzar aquestes eines ens proporciona una gran avantatge competitiva en el mercat laboral actual."
   
   > "Les aplicacions ofimàtiques com LibreOffice ens ofereixen la possibilitat de crear documents professionals de manera senzilla i eficaç."

3. Aplica les següents modificacions de sangria i interlineat:

   - **Primer paràgraf:**
     - **Sangria de la primera línia:** 1 cm.
     - **Sangria abans del paràgraf:** 0,5 cm.
     - **Sangria després del paràgraf:** 0,5 cm.
     - **Interlineat:** 1,5.

   - **Segon paràgraf:**
     - **Sangria de la primera línia:** 0,75 cm.
     - **Sangria abans del paràgraf:** 1 cm.
     - **Sangria després del paràgraf:** 1 cm.
     - **Interlineat:** doble.

\begin{tcolorbox}[colback=customblue!5!white, colframe=customblue!80!black, title=Nota]
Guarda el document amb el nom `Exercici-Sangries.odt`.
\end{tcolorbox}

\begin{tcolorbox}[colback=customblue!5!white, colframe=customblue!80!black, title=Nota]
Assegura't que les sangries i l'interlineat estan correctament aplicats revisant el disseny del document.
\end{tcolorbox}

\newpage

## Activitat 22<a id="activitat-22"></a>

### Objectius:
- Crear i personalitzar llistes en **LibreOffice Writer**.
- Modificar l'inici de la numeració.
- Combinar diferents nivells i estils de llistes (números i vinyetes).

### Desenvolupament de l'activitat:

1. Obri un document nou en **LibreOffice Writer**.
2. Crea la següent llista numerada i amb vinyetes, seguint aquestes indicacions:

   - **Inicia la llista numerada a partir del número 2**:
   
     2. Eines ofimàtiques:
        - Llistes:
          1. Llistes numerades.
          2. Llistes amb vinyetes.
        - Documents:
          - Processadors de text.
          - Fulls de càlcul.
     3. Avantatges de l'ofimàtica:
        - Facilitat d'ús.
        - Millora de la productivitat.
          - Automatització de tasques.
          - Accés a plantilles.
          
   - Combina tant **números** com **vinyetes** per als subnivells, com es mostra en l'exemple anterior.

3. Per a configurar la llista numerada perquè comence amb el número **2**:
   - Selecciona el primer element de la llista.
   - Ves a **Format > Marcadors i Numeració**.
   - A l'apartat **Opcions**, canvia el valor inicial a 2.


\begin{tcolorbox}[colback=customblue!5!white, colframe=customblue!80!black, title=Nota]
Guarda el document amb el nom `Exercici-Llistes.odt`.
\end{tcolorbox}

\begin{tcolorbox}[colback=customblue!5!white, colframe=customblue!80!black, title=Nota]
Revisa que els nivells de la llista i la combinació de números i vinyetes s'apliquen correctament.
\end{tcolorbox}