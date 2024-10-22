---
title: "Aplicacions Ofimàtiques"
subtitle: "Activitats 25 i 26"
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
1. [Activitat 25](#activitat-25)
2. [Activitat 26](#activitat-26)

## Activitat 25<a id="activitat-25"></a>

### Generació Automàtica de l'Índex de Continguts

### Objectius:
- Aprendre a generar un índex de continguts automàticament.
- Personalitzar l'aparença de l'índex.

### Desenvolupament de l’activitat:
1. Obri un document nou en **LibreOffice Writer**.
2. Escriu el següent text que conté títols de diferents nivells:

   #### Introducció (Aplicar **Títol 1**)
   En aquesta secció, discutirem la importància de l'ofimàtica en el món actual. L'ofimàtica es refereix a l'ús d'eines informàtiques per a la creació, edició i gestió de documents. Les aplicacions ofimàtiques ens permeten treballar de manera més eficient i productiva.

   #### Funcionalitats de LibreOffice (Aplicar **Títol 1**)
   LibreOffice ofereix una gamma de funcionalitats que faciliten la creació de documents professionals. Entre les principals funcionalitats, podem destacar:

   ##### Edició de Text (Aplicar **Títol 2**)
   L'edició de text a LibreOffice és intuïtiva i permet aplicar diversos estils. Podem modificar la font, la mida i el color del text, així com aplicar efectes com negreta o cursiva.

   ##### Creació de Taules (Aplicar **Títol 2**)
   La creació de taules és senzilla. Podem inserir taules per organitzar dades i presentacions. A més, podem personalitzar l'estil de la taula per fer-la més atractiva.

   #### Funcionalitats Avançades (Aplicar **Títol 1**)
   A més de les funcionalitats bàsiques, LibreOffice disposa de diverses eines avançades que poden millorar encara més la nostra productivitat.

   ##### Macros (Aplicar **Títol 2**)
   Les macros ens permeten automatitzar tasques repetitives. Podem gravar una sèrie d'accions i repetir-les amb un sol clic, estalviant temps en les nostres tasques diàries.

   #### Conclusions (Aplicar **Títol 1**)
   A través de l'ús de les eines ofimàtiques, podem millorar la nostra productivitat i eficàcia. LibreOffice és una alternativa potent i gratuïta que ens permet crear documents de qualitat professional.

3. Aplica estils de títol a les seccions:
   - Selecciona el títol **Introducció** i aplica **Estil de paràgraf** > **Títol 1**.
   - Selecciona el títol **Funcionalitats de LibreOffice** i aplica **Títol 1**.
   - Selecciona el títol **Edició de Text** i aplica **Títol 2**.
   - Selecciona el títol **Creació de Taules** i aplica **Títol 2**.
   - Selecciona el títol **Funcionalitats Avançades** i aplica **Títol 1**.
   - Selecciona el títol **Macros** i aplica **Títol 2**.
   - Selecciona el títol **Conclusions** i aplica **Títol 1**.

4. Per a inserir l'índex de continguts:
   - Ves a la ubicació on desitges inserir l'índex (normalment al principi del document).
   - Fes clic a **Insertar > Índex i Taules > Índex**.
   - Configura les opcions desitjades (com el nombre de nivells) i fes clic a **D'acord**.

5. Observa com l'índex es genera automàticament amb els títols que has creat. Cada títol estarà vinculat a la secció corresponent.

\begin{tcolorbox}[colback=customblue!5!white, colframe=customblue!80!black, title=Nota]
Guarda el document amb el nom `Act-25.odt`.
\end{tcolorbox}

---

## Activitat 26<a id="activitat-26"></a>

### Introducció a les Macros a Writer

### Objectius:
- Entendre què són les macros i com es poden utilitzar a **LibreOffice Writer**.
- Crear una macro divertida que automatitzi una tasca senzilla.

### Desenvolupament de l’activitat:
1. Obri un document nou en **LibreOffice Writer**.
2. Escriu el següent text en el document:
   
   > Introducció
Benvingut al món de les macros! Aquí és on la màgia de l'ofimàtica comença. Les macros són com petits ajudants invisibles que poden fer la teva feina més ràpida i eficient. Si alguna vegada has desitjat poder automatitzar tasques repetitives, les macros són la solució perfecta. Imagina't no haver de repetir les mateixes accions una i altra vegada; les macros ho fan per tu!

Què és una Macro?
Una macro és un conjunt d'instruccions que permet realitzar una sèrie d'accions automàticament. Amb les macros, pots gravar els passos que fas i, més tard, reproduir-los amb un sol clic. Això significa que pots dedicar menys temps a tasques monòtones i més temps a la creativitat i a projectes més importants.

3. Ara, farem una macro que canvia el color del text a un color (per exemple, blau) i aplica un estil de lletra a tot el text del document:
   - Ves a **Eines > Macros > Gravar macro**.
   - Selecciona tot el text del document (Ctrl + A).
   - Canvia el color del text a **blau**.
   - Aplica un estil de lletra **Arial, 16pt**.
   - Ves a **Eines > Macros > Aturar gravació**.
   - Dona-li un nom a la macro, per exemple, **CanviaColorText**.

4. Prova la macro:
   - Crea un nou document o torna al document anterior.
   - Ves a **Eines > Macros > Executar macro**.
   - Selecciona **CanviaColorText** i fes clic a **Executar**.
   - Observa com el text del document es transforma!

5. Modifica la macro per afegir un missatge de benvinguda cada vegada que l'executis. Per a això, editant la macro, afegeix el següent codi al principi:
   ```basic
   MsgBox "Hola! Estàs a punt de veure màgia."

\begin{tcolorbox}[colback=customblue!5!white, colframe=customblue!80!black, title=Nota] Guarda el document amb el nom Act-26.odt. \end{tcolorbox}

