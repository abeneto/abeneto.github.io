---
title: "Aplicacions Ofimàtiques"
subtitle: "Activitats 23 i 24"
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
1. [Activitat 23](#activitat-23)
2. [Activitat 24](#activitat-24)

## Activitat 23<a id="activitat-23"></a>

### Notes a peu de pàgina i final de document

### Objectius:
- Insertar notes al peu de la pàgina.
- Insertar notes al final del document.

### Desenvolupament de l’activitat:
1. Recupera el document `Normas.odt` i guarda-ho en la teua carpeta de treball.
2. Obri-ho i trasllada les explicacions dels tipus de lletra al peu de pàgina com a notes.
3. Guarda el document amb el nom `Notas_Pagina.odt` però no el tanque.
4. En el document `Notas_Pagina.odt`, modifica la posició de les notes en cada pàgina i converteix-les en notes al final del document.
5. Guarda el document modificat amb el nom `Notas_Documento.odt`.
6. **NOTA:** Guarda el document generat com `Act-23.odt`.

---

## Activitat 24<a id="activitat-24"></a>

### Referències creuades

### Objectius:
- Definir referències creuades.
- Insertar referències creuades en el text.

### Desenvolupament de l’activitat:
1. Recupera el document `Cuentas.odt` i guarda’l en la teua carpeta de treball.
2. Obri el fitxer guardat.

#### Definició de les referències
3. Selecciona el títol **Concepto y características** i inserida una referència creuada amb el nom del marcador **Art_1**.
4. Repeteix el procés per als altres títols del text:
   - **Contenido de las cuentas anuales**: Marcador **Art_2**.
   - **Plazo para formular las cuentas anuales**: Marcador **Art_3**.
   - **Cuentas anuales abreviadas**: Marcador **Art_4**.
   - **1. El balance**: Marcador **Ap_1**.
   - **2. La cuenta de pérdidas y ganancias**: Marcador **Ap_2**.
   - **3. La memoria**: Marcador **Ap_3**.

#### Aplicacions Ofimàtiques - Taula de referències
1. Damunt del títol **Concepto y características**, crea una taula d'una columna i huit files.
2. En la primera cel·la, escriu el text **Articulado**.
3. En la segona cel·la, inserida la referència creuada **Art_1**.
4. Inserta la resta de referències en les cel·les de la taula, en el mateix ordre del text.
5. Observa el text que apareix en les cel·les de la taula i intenta fer clic sobre ell.

#### Inserció de les referències en el text
6. Per a aconseguir desplaçar el cursor a l'inici del document, marca la paraula **Articulado** com **Inicio** afegint una referència creuada.
7. En el text, en la mateixa línia dels títols, inserida una tabulació dreta al límit dret del document:
   - Selecciona **Formato > Párrafo > pestanya Tabuladors**.
   - Fixa una tabulació **Dreta** en la posició 15 cm i accepta.
8. En la posició de la tabulació, inserta la referència creuada **Inicio**.
9. Repeteix el procés per a la resta d’articles.
10. Guarda el document amb el nom `Cuentas_Anuales.odt`.
11. **NOTA:** Guarda el document generat com `Act-24.odt`.

