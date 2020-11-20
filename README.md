# bornhohe_analyys

Selles kaustas on Pythoni skriptid, millega eraldada EstNLTK teekide abil kohanimed, nende lähikontekstid ja omadussõnalised kollokaadid tekstist "Vürst Gabriel ehk Pirita kloostri viimsed päevad".

Vajaliku juhendi programmide ja pakettide installeerimiseks leiab Tartu Ülikooli kursuse ["Eesti keele töötlus Pythonis"](https://github.com/d009/EstNLP) õppevahenditest.

Lühike versioon juhendist on järgmine:

## Anaconda ja EstNLTK installeerimine
- Laadi alla Anaconda installimise fail ja installi programm.
- Käivita programm Anaconda Prompt.
- Loo avanenud aknas uus keskkond, kuhu installid Pythoni versiooni 3.6: `conda create --name keelanalyys python=3.6` (kui vahepeal midagi küsitakse, trüki `y`).
- Aktiveeri keskkond: `conda activate keeleanalyys` (keskkonna desaktiveerimiseks trüki `conda deactivate`).  
- Kontrolli, millised teegid on keskkonda installitud: `conda list`.  
- Installi keskkonda EstNLTK 1.6: `conda install -c estnltk -c conda-forge estnltk=1.6.7b`.  

## Jupyteri installimine
- Anaconda Promptis trüki `conda install jupyter` (vaja teha 1 kord).  
- Liigu terminaliaknas kausta, kus on selle repositooriumi failid nt Windowsis trükkides `cd C:\Users\kasutaja1\Desktop\bornhohe_analyys`.
- Käivita Anaconda Propmtis Jupyter: trüki `jupyter notebook`. 
- Käivita avanenud aknas skriptiga märkmikud.  

## Jupyteri kasutamine
- Enter: tee lahter muutmiseks aktiivseks
- Esc: liigu muutmisrežiimilt välja
- Shift+Enter: jooksutab lahtri ja liigub järgmise juurde
- Ctrl+Enter: jooksutab lahtri ja väljub muutmisrežiimist
- a: tee uus lahter üles
- b: tee uus lahter alla
- dd: kustuta lahter
- Space: viib märkmiku lõppu
