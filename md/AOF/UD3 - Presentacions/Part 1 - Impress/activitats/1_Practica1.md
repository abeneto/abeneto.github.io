---
title: "Aplicacions Ofimàtiques"
subtitle: "Pràctica 1"
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


## Pràctica final<a id="practica-final"></a>

### Objectiu:
Crear una presentació completa integrant tots els coneixements adquirits, incloent la creació de diapositives, inserció d'imatges, taules, diagrames, animacions, transicions i aplicació de patrons de diapositives.

### Tema de la Presentació:
**Les Tendències Actuals en Tecnologia**

### Desenvolupament de l’activitat:

1. **Creació de la presentació:**
   - Obre **LibreOffice Impress** i crea una nova presentació en blanc.
   - Selecciona una plantilla que t'agradi per al disseny de la presentació.

2. **Patró de diapositives:**
   - Accedeix al **patró de diapositives** mitjançant la pestanya "Visualització" i seleccionant "Patró de diapositives".
   - Dissenya un patró de diapositives que inclogui:
     - Un títol i un subtítol (que apareixeran en cada diapositiva).
     - Un fons atractiu i coherent amb el tema de la presentació.
     - Espais reservats per a text, imatges i gràfics.
   - Tanca la visualització del patró de diapositives un cop hagis acabat.

3. **Diapositiva de títol:**
   - Afegeix una diapositiva de títol amb el títol "Les Tendències Actuals en Tecnologia" i el teu nom, utilitzant el patró que has creat.
   - Aplica una animació d'entrada al títol.

4. **Diapositives de contingut:**
   - Crea almenys 5 diapositives addicionals amb el següent contingut, utilitzant el patró dissenyat:
     - **Diapositiva 2:** Introducció a les tendències tecnològiques actuals (ex: intel·ligència artificial, Internet de les coses, etc.).
     - **Diapositiva 3:** Intel·ligència Artificial: Explica què és i com s'està utilitzant en diversos sectors.
     - **Diapositiva 4:** Internet de les Coses (IoT): Definició i exemples d'aplicacions.
     - **Diapositiva 5:** Computació en el núvol: Avantatges i desavantatges.
     - **Diapositiva 6:** Futur de la tecnologia: Quines tendències poden aparèixer en els propers anys.

5. **Animacions i transicions:**
   - Aplica animacions als diferents elements de cada diapositiva (text, imatges, taules).
   - Selecciona i aplica una transició diferent per a cada diapositiva. Assegura't que les transicions siguin coherents amb el tema de la presentació.

6. **Fons i estil:**
   - Revisa que el fons del patró de diapositives sigui atractiu i complementi el contingut.
   - Assegura't que el contrast entre el fons i el text sigui adequat per a una lectura fàcil.

7. **Revisió i ajustos finals:**
   - Revisa la presentació per assegurar-te que tot el contingut és coherent i que no hi ha errors d'ortografia.
   - Ajusta les animacions i transicions per garantir que no siguin massa ràpides o lentes.

8. **Exportació i entrega:**
   - Guarda el document amb el nom `Presentacio_Final.odp`.
   - Exporta la presentació a format PDF per facilitar la seva revisió.
   - Presenta la teua presentació davant dels companys de classe, utilitzant les animacions i transicions que has creat.

\begin{tcolorbox}[colback=customblue!5!white, colframe=customblue!80!black, title=Nota]
Recorda que la presentació ha de ser clara, concisa i atractiva per a l'audiència. Fes servir imatges i gràfics per a fer-la més visual.
\end{tcolorbox}
