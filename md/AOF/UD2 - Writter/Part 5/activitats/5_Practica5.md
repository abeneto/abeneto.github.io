---
title: "Aplicacions Ofimàtiques"
subtitle: "Pràctica 5"
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
- [Índex](#índex)
- [Introducció](#introducció)
- [Objectius](#objectius)
- [Pràctica 5](#pràctica-5)

## Introducció<a id="introduccio"></a>

La pràctica ens introdueix en l’ús avançat de **LibreOffice**, amb un enfocament especial en les macros i l'edició de documents.

## Objectius<a id="objectius"></a>

L’objectiu d’aquesta pràctica és comprovar si l’alumnat ha interioritzat els següents conceptes pràctics i sap dur-los a terme:

- Creació i execució de macros.
- Inserció de notes al peu.
- Creació de referències creuades.
- Edició i formatatge de documents.
- Índex automàtic.

\newpage

## Pràctica 5<a id="practica-5"></a>

1. **Copia el següent text en un document en blanc:**

¿Resuelto el misterio del Oumuamua? Un nuevo estudio asegura que procede de otro sistema solar

¿Tecnología extraterrestre? ¿Una nave espacial averiada? Un nuevo estudio podría haber resuelto el misterio del Oumuamua: el objeto estelar alargado detectado en 2017 prodece de un planeta similar a Plutón, pero de otro sistema solar. 

Así lo afirman los astrónomos de la investigación publicada el pasado 16 de marzo por la Advancing Earth and Space Science (AGU): "sugerimos que el Oumuamua salió probablemente despedido desde un sistema estelar joven hace unos 500 millones de años", escriben. 

Para los investigadores, esto explicaría sus peculiares catacterísticas que han generado un gran debate científico en los últimos años: "era pequeño, aproximadamente la mitad de largo que una manzana y tan grueso solo como un edificio de tres pisos, pero era muy brillante". 

Su brillo es similar al de las superficies de Plutón y Tritón, que están cubiertas de hielo de nitrógeno, añaden. 

En la recreación que propone este nuevo estudio, el Oumuamua ya no se representa como una forma estirada símile a la de un puro, sino que recuerda más a una galleta o una tortita, es plano y redondeado. 

Alan Jackson, astrónomo e investigador planetario de la Universidad Estatal de Arizona y coautor de la nueva investigación, cree que probablemente que el Oumuamua es producto de una colisión lejos de nuestro sistema solar hace millones de años que resultó en la expulsión de un fragmento que se fue moldeando durante su largo viaje intergaláctico. 

"No era plano cuando entró en nuestro sistema solar, sino que se fundió en una astilla cuando se acercó al Sol, perdiendo más del 95% de su masa en el proceso", apunta. 

"El hecho de que esté hecho de nitrógeno congelado también explica la forma inusual de Oumuamua. A medida que las capas externas del hielo de nitrógeno se evaporaron, la forma del cuerpo se aplanó, como una barra de jabón cuando las capas externas se frotan con su uso".

¿Un trozo de un planeta muy lejano o una nave espacial alienígena? 

Los investigadores señalan que este hallazgo podría permitirles ver de qué están hechas las superficies de un tipo de exoplaneta hasta ahora desconocido, los exo-Plutónes o planetas fuera del sistema solar parecidos a nuestro gélido Plutón. "Oumuamua puede ser la primera pieza de un exoplaneta que nos llega", señalan. 

Pero hay científicos que llevan años hipotetizando que podría tratarse de algo mucho más revelador: una prueba de la existencia de vida inteligente en otros planetas. 

El prestigioso físico de la Universidad de Harvard Abraham 'Avi' Loeb insistía hace unos meses que el Oumuamua podría ser un artilugio fabricado por una civilización tecnológica extraterrestre. 

Loeb ya había defendido esta controvertida teoría en un artículo científico publicado en 2018 en el que sugería que la forma inusual de Oumuamua y su sorprendente aceleración indicaban que podría tratarse de una "vela de luz", o nave espacial impulsada por la luz del sol, hecha por extraterrestres. 

Tanto entonces como en su nuevo trabajo, “Extraterrestre: La humanidad ante el primer signo de vida inteligente más allá de la Tierra”, Loeb no afirma que sea una nave alienígena, pero incide en que es la mejor explicación a su misterioso origen y que los científicos deberían considerar la posibilidad. 

"Cuando tienes un martillo todo parecen clavos. Sobre todo cuando nunca has visto un clavo", el investigador científico Héctor Socas-Navarro del Instituto de Astrofísica de Canarias, explicaba a Euronews la fijación de Loeb con la teoría alienígena. 

Socas-Navarro apuntaba más a la hipótesis de que se tratase de un cometa asteroide y no descartaba una posible procedencia extrasolar: "la composición de un objeto de fuera del sistema solar puede ser diferente de un cometa del sistema solar". 

Ahora este nuevo estudio señala que el Oumuamua es como un cometa, pero no exactamente uno.

Hielo detrás de las incógnitas 

El objeto adquirió un ligero impulso para alejarse del Sol, un "efecto cohete" común en los cometas cuando la luz solar vaporiza los hielos de los que están hechos, pero el empuje fue más fuerte de lo que podía explicarse, indica el estudio de AGU. 

Además el Oumuamua carecía de un escape de gas detectable, que suele estar representado visiblemente por la cola de un cometa. 

"El Oumuamua se asemejaba a un cometa, pero era lo suficientemente peculiar en varios aspectos como para que el misterio rodeara su naturaleza, y las especulaciones sobre lo que era se dispararon", dijo Steven Desch, astrofísico de la Universidad Estatal de Arizona y coautor del nuevo estudio. 

Desch y Jackson plantearon la hipótesis de que el objeto estaba formado por diferentes hielos y calcularon la rapidez con la que estos hielos pasarían del estado sólido al gaseoso al acercarse al sol. 

"Ese fue un momento emocionante para nosotros", dijo Desch. "Nos dimos cuenta de que un trozo de hielo sería mucho más reflectante de lo que la gente suponía, lo que significaba que podía ser más pequeño". 

Este efecto habría proporcionado entoncces al Oumuamua un impulso más potente, "mayor del que suelen experimentar los cometas". 

Estos últimos hallazgos no le restan ni un ápice de romanticismo galáctico al misterio del Oumuamua, o "mensajero de un pasado lejano" como su nombre se traduce (más o menos) del hawaiano: "hasta ahora no sabíamos si había planetas similares a Plutón en otros sistemas solares, pero ahora hemos visto un pedazo de uno que vuela más allá de la Tierra".

Conclusiones

“Como solía decir Carl Sagan, ‘afirmaciones extraordinarias requieren de evidencias extraordinarias’, y no creo que este artículo las presente”, concluye Marco Micheli. La misma frase la han citado Karen Meech y Josep Maria Trigo al ser interrogados sobre las especulaciones de Bialy y Loeb.


2. **Deuràs crear una macro que, al executar-la, convertisca el text seleccionat en un tipus de lletra Arial 22 i justifica el text.** 

- Per fer-ho, accedeix a `Eines` > `Macros` > `Registrar macro`. 
- Assigna un nom a la macro i prem `Iniciar registre`.
- Selecciona tot el text (Ctrl + A) i aplica el tipus de lletra Arial, la mida 22 i justifica el text (Ctrl + J).
- Detén el registre de la macro (Eines > Macros > Parar registre).
- Assegura’t d’anotar el nom de la macro.
- La combinació de tecles que li asignes deu ser Ctrl+T

3. **Executa la macro en el primer paràgraf**

4. **Inserir notes al peu de pàgina.** 

- Inserta dos notes al peu de pàgina. Una per a la paraula Euronews i altra per a la paraula Tritón, de forma que quede com la solució indicada el Sol_Prac_5.pdf

5. **Fes referències creuades.**

-  Crea tres referències creuades en el document:
a) ¿Un trozo de un planeta muy lejano o una nave espacial alienígena?
b) Hielo detrás de las incógnitas
c) Conclusiones

6. **Abans de tot el text, crea una taula d’una columna i 4 files:**

a) En la primera cel.la escriu “Referències”
b) En la resta de files inserta la resta de referencies que has creat anteriorment

7. **Inserta la imatge que trobaràs en recursos en la posició indicada en el fitxer Sol_Prac_5.pdf**

8. **Realitza una correcció ortogràfica**

9. **Fes una captura de la macro generada i pegala al final del document.**

10. **Reprodueix el format indicat a Sol_Prac_5.pdf**

\begin{tcolorbox}[colback=customblue!5!white, colframe=customblue!80!black, title=Nota]
GUARDA EL DOCUMENT AMB EL NOM: \texttt{practica5\_1.odt} i puja els documents a la plataforma.
\end{tcolorbox}


11.  **Ara, aplica l'estil Título 1 a:**
- ¿Resuelto el misterio del Oumuamua? Un nuevo estudio asegura que procede de otro sistema solar
- ¿Un trozo de un planeta muy lejano o una nave espacial alienígena?
- Hielo detrás de las incógnitas
- Conclusiones

**i genera un índex automàtic al final del document**

\begin{tcolorbox}[colback=customblue!5!white, colframe=customblue!80!black, title=Nota]
GUARDA EL DOCUMENT AMB EL NOM: \texttt{practica5\_2.odt} i puja els documents a la plataforma.
\end{tcolorbox}