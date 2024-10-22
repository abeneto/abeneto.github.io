---
title: "Aplicacions Ofimàtiques"
subtitle: "Activitats 16 a 18"
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
3. [Activitat 16](#activitat-16)
4. [Activitat 17](#activitat-17)
5. [Activitat 18](#activitat-18)


## Introducció<a id="introduccio"></a>

La pràctica ens introdueix en l'ús bàsic de **LibreOffice Writer**.

## Objectius<a id="objectius"></a>

- Copiar i desplaçar part d'una taula
- Taules de càlcul
- Organització de documents de gran volum

## Activitat 16<a id="activitat-16"></a>

### Objectius:
- Seleccionar parts d'una taula.
- Copiar i desplaçar parts d'una taula.
- Copiar o desplaçar una taula.

### Desenvolupament de l’activitat:
1. Recupera el document `Clientes.odt` i guarda-ho en la teua carpeta de treball.
2. Obri l'arxiu guardat.

#### Desplaçament de columnes
1. Mou la columna **Cognom** al primer lloc.
2. Mou la columna **NIF** al final de tot.
3. Ajusta l'ample de les columnes amb ajuda del ratolí.

#### Desplaçament de files
1. Mou la posició de la primera fila:
   - Selecciona la fila corresponent al primer client. Fes "Cortar" (Ctrl + X).
   - Selecciona les tres files següents i desplaça-les cap amunt una posició.
   - Situa't en la quarta fila, que estarà buida, i pega el contingut que tenies en la memòria (Ctrl + V).

El document ha de quedar com a mostra en el fitxer `Sol_Act_16.pdf`.

\begin{tcolorbox}[colback=customblue!5!white, colframe=customblue!80!black, title=Nota]
Guarda el document generat com `Act-16.odt`.
\end{tcolorbox}

---

## Activitat 17<a id="activitat-17"></a>

### Objectius:
- Realitzar operacions de càlcul en una taula.
- Utilitzar funcions de càlcul en una taula.
- Aplicar formats numèrics als valors d'una taula.
- Inserir un full de càlcul.
- Utilitzar l'editor d'equacions científiques i matemàtiques.


### Càlculs en una taula
Una taula també es pot comportar com un full de càlcul i les cel·les es nomenen com A1, A2, B1,B2, etc. La lletra representa la columna i el número representa la fila. 

|     | A  | B  | C  | 
|-----|----|----|----|
|  1  | A1 | B1 | C1 |
|  2  | A2 | B2 | C3 |
|  3  | A3 | B3 | C3 |

### Desenvolupament de l’activitat:
Aquesta activitat es pot fer creant una taula o inserint un full de càlcul. Es tracta de crear una taula amb les següents dades:

| Préstamo      | Capital  | Anualidad | Interés | Años |
|---------------|----------|-----------|---------|------|
| Préstamo 1    | 10000    | 1.806,74  | 9,00%   | 8    |
| Préstamo 2    | 215000   | 34.990,26 | 10,00%  | 10   |
| Préstamo 3    | 6000     | 1.459,35  | 12,00%  | 6    |
| Préstamo 4    | 135000   | 17.913,83 | 8,00%   | 12   |
| Préstamo 5    | 85000    | 20.178,69 | 6,00%   | 5    |

\begin{tcolorbox}[colback=customblue!5!white, colframe=customblue!80!black, title=Nota]
Guarda el document generat com `Act-17.odt`.
\end{tcolorbox}

---

## Activitat 18<a id="activitat-18"></a>

### Objectius: 
- Crear els apartats d'un document de gran volum.
- Utilitzar el navegador per a desplaçar-se en un document de gran volum.
- Reorganitzar un document de gran volum amb el navegador.

### Desenvolupament de l’activitat:
#### Creació de l'esquelet i navegació d'un document
A continuació tens una llista amb els diferents títols que ha de tindre el teu document. Al costat, entre parèntesi, està l'estil que se li ha d'aplicar.

- Portada (Estilo predeterminado) 
- Índex (Estilo predeterminado) 
- Glosario (Título 1) 
- Introducción (Título 1) 
- Capítulo primero (Título 1) 
- Apartado 1 (Título 2) 
- Subapartado 1.1 (Título 3) 
- Subapartado 1.2 (Título 3) 
- Subapartado 1.3 (Título 3) 
- Apartado 2 (Título 2) 
- Apartado 3 (Título 2) 
- Capítulo segundo (Título 1) 
- Apartado 1 (Título 2) 
- Apartado 2 (Título 2)
- Capítulo tercero (Título 1) 
- Apartado 1 (Título 2) 
- Apartado 2 (Título 2) 
- Conclusiones (Título 1) 
- Anexos (Título 1) 
- Anexo A (Título 2) 
- Anexo B (Título 2) 
- Anexo C (Título 2)


1. Comença creant un nou document de text.
2. Escriu els títols de la llista (sense els textos que hi ha entre parèntesi).
3. Aplica a cada títol l'estil que hi ha entre parèntesi (això és important!).
4. Observa com canvia el format del text al aplicar els diferents estils.
5. Fes visible el navegador fent clic en la icona del Navegador, prement F5 o pel menú **Veure \ Navegador**.
6. Selecciona **Títols** i fes clic en la icona **Visualització del contingut**. T'apareixeran només els estils de les categories de Títols.
7. Fes un doble clic en el nom d'un capítol, apartat o subapartat, i observa com vas directament a aqueixa localització.
8. Guarda l'arxiu amb el nom `Act-18.odt`.

#### Reorganització d'un document
1. Recupera el document `Memoria.odt`.
2. Obre-ho com abans i fes aparèixer el Navegador en la seua pantalla de l'ordinador.
3. Selecciona els Títols i canvia a Vista de navegació de contingut.
4. Fes proves canviant l'ordre dels capítols ÀREA D'ORGANITZACIÓ I PLANIFICACIÓ DE RECURSOS / ÀREA ECONÒMIC / RECURSOS HUMANS / COMPRES CORPORATIVES.
5. En el navegador, fes doble clic sobre l'Annex. Observa com et porta a l'Annex del text.
6. Veus als diferents apartats del document amb el navegador.
7. Tanca el document descartant guardar els canvis i eixir de LibreOffice Writer.

\begin{tcolorbox}[colback=customblue!5!white, colframe=customblue!80!black, title=Nota]
Guarda el document generat com `Act-18.odt`.
\end{tcolorbox}
