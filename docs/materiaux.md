# HCHN : matériaux

## Sommaire

<!-- MarkdownTOC autolink="true" autoanchor="true" -->

- [Ressources générales](#ressources-g%C3%A9n%C3%A9rales)
    - [Ressources du séminaire](#ressources-du-s%C3%A9minaire)
    - [Forum : quelques bonnes habitudes](#forum--quelques-bonnes-habitudes)
    - [Quelques noms de symboles utiles](#quelques-noms-de-symboles-utiles)
    - [Nommer un fichier ou un objet](#nommer-un-fichier-ou-un-objet)
    - [Écrire grec en Unicode](#%C3%89crire-grec-en-unicode)
    - [Polices de caractères pour le grec *et* le latin](#polices-de-caract%C3%A8res-pour-le-grec-et-le-latin)
    - [Dictionnaires](#dictionnaires)
    - [Digital Classics : sites d'information](#digital-classics--sites-dinformation)
    - [Bibliographie et Zotero](#bibliographie-et-zotero)
    - [Bibliothèques en ligne](#biblioth%C3%A8ques-en-ligne)
    - [Droit et licences](#droit-et-licences)
    - [Données, images et cartographie](#donn%C3%A9es-images-et-cartographie)
    - [Ressources diverses](#ressources-diverses)
- [Outils et langages](#outils-et-langages)
    - [Éditeur de texte : Atom](#%C3%89diteur-de-texte--atom)
    - [Markdown](#markdown)
    - [GitHub](#github)
    - [Terminal Unix](#terminal-unix)
    - [Pandoc](#pandoc)
    - [Regex](#regex)
    - [HTML](#html)
    - [XML et TEI](#xml-et-tei)
    - [Voyant Tools](#voyant-tools)
    - [R et RStudio](#r-et-rstudio)
    - [LaTeX](#latex)
    - [OCR : Tesseract](#ocr--tesseract)
    - [Open Refine](#open-refine)
    - [CLTK](#cltk)
    - [Stopwords](#stopwords)
    - [Lemmatisation](#lemmatisation)
    - [Expositions virtuelles](#expositions-virtuelles)

<!-- /MarkdownTOC -->

<a id="ressources-g%C3%A9n%C3%A9rales"></a>
## Ressources générales

<a id="ressources-du-s%C3%A9minaire"></a>
### Ressources du séminaire
* Carnet [Classiques et numériques](https://classnum.hypotheses.org/)
* Bibliothèque partagée Zotero : groupe Classnum (sur invitation)
* [Framapad](https://framapad.org/)
    * [Pad HN1](https://annuel.framapad.org/p/hn1)
    * [Pad HN3](https://annuel.framapad.org/p/hn3)
* [Dropbox](https://www.dropbox.com/)
* [HN1 : questionnaire de début de S1](https://goo.gl/forms/L9E0tsOzvw3U3Xwu2)

<a id="forum--quelques-bonnes-habitudes"></a>
### Forum : quelques bonnes habitudes

* Si vous écrivez vos messages sur le forum en Markdown, comme je vous le suggère, utilisez lorsque c'est utile des apostrophes inversées pour baliser le code :

Ceci est une `expression` affichée comme du code au sein d'un texte (*inline*), car notée ainsi : \`expression\`.

```
Ceci est un paragraphe de code (affiché comme *blockquote*),
```

car précédé et suivi d'une ligne contenant trois *backticks* :

\`\`\`
Ceci est un paragraphe de code (affiché comme *blockquote*),
\`\`\`

* Cependant, dès qu'il s'agit d'une citation un peu longue (d'un extrait d'encodage en HN1 ou de code en HN3), partagez un fichier de code : le texte du forum n'est pas exécutable et ne dit rien de votre environnement de travail.
* Or, le but d'une demande d'aide est d'isoler le problème en le rendant reproductible. La plupart du temps, cela implique de :
    * mentionner votre système et sa configuration – dans le cadre de nos cours, cela revient avant tout à indiquer votre système d'exploitation et sa version
    * préciser ce que vous essayez de faire
    * fournir un *minimal working example* ou [*minimal reproducible example*](https://stackoverflow.com/help/minimal-reproducible-example) – et vous constaterez qu'en réduisant le problème aux données pertinentes, et en l'expliquant, il arrive fréquemment qu'on en trouve la solution
* Des captures d'écran valent souvent plus qu'un long discours.
* Des liens sont généralement utiles. Les URL citées doivent être actives pour éviter les copier-coller à vos lecteurs.
* Lorsque vous avez réussi à résoudre votre problème, indiquez brièvement la solution sur le forum : toute personne qui vous a répondu sera intéressée et d'autres personnes peuvent à l'avenir rencontrer le même problème et trouver ainsi une solution.

<a id="quelques-noms-de-symboles-utiles"></a>
### Quelques noms de symboles utiles

| Symbole |            Nom en français (*name in English*)             |
|---------|------------------------------------------------------------|
| [ ]     | crochets (*square brackets*)                               |
| { }     | accolades (*curly braces*, *curly brackets*)               |
| < >     | chevrons, crochets obliques (*angle brackets*, *chevrons*) |
| \|      | barre droite (*pipe*)                                      |
| /       | barre oblique (*slash*, *forward slash*)                   |
| \       | barre oblique inversée (*antislash*, *back slash*)         |
| _       | tiret bas (*underscore*)                                   |
| `       | apostrophe inversée (*backtick*, *backquote*)              |
| #       | croisillon (*octothorpe*, *hashtag*)                       |

<a id="nommer-un-fichier-ou-un-objet"></a>
### Nommer un fichier ou un objet

* Éviter de faire figurer dans un nom de fichier ou de dossier des espaces, des caractères accentués, voire des majuscules.
* Un bon nom de fichier est distinct, et même unique. S'il doit être partagé, il identifie la personne qui l'a créé et, au besoin, mentionne un numéro de version.
* Parmi les diverses conventions possibles, je recommande l'usage du *snake_case* pour nos fichiers partagés et, en M2, pour les objets créés dans R :
    * i_use_snake_case.txt
    * otherPeopleUseCamelCase.txt
    * some.people.use.periods.txt
    * And_aFew.People_RENOUNCEconvention.txt

<a id="%C3%89crire-grec-en-unicode"></a>
### Écrire grec en Unicode
* Écrire en grec ancien (grec polytonique) avec un clavier Unicode
    * [Page ENS](https://antiquite.ens.psl.eu/ressources/outils-logiciels/article/pilotes-de-clavier-unicode)
    * Autre possibilité : [Windows](https://michaellanglois.fr/fr/it/greek-with-french-keyboard-12-windows_grec-avec-clavier-francais-12-windows), [Mac](https://michaellanglois.fr/fr/it/clavier-grec-azerty-1-2-mac), [Linux](https://gitlab.com/outils-pour-le-grec/clavier-grec-ancien-azerty)
* [Learn to Type Polytonic Greek in 30 Short Chapters](https://greektyping.com/)

<a id="polices-de-caract%C3%A8res-pour-le-grec-et-le-latin"></a>
### Polices de caractères pour le grec *et* le latin
* [Libertinus Serif](https://fontlibrary.org/en/font/libertinus-serif) (ou Linux Libertine O)
* [Gentium Plus](https://fontlibrary.org/en/font/gentium-plus)
* [GFS Didot](https://fontlibrary.org/en/font/gfs-didot)
* [GFS Elpis](https://fontlibrary.org/en/font/gfs-elpis)
* Times (et non Times New Roman)
* Palatino Linotype
* [Asea](https://fontlibrary.org/en/font/asea-textfonts)
* [Lato](https://fontlibrary.org/en/font/lato) (sans empattements, *sans serif*)
* Bonus culturel : [Sacrés caractères !](https://www.franceculture.fr/litterature/sacres-caracteres-une-webserie-de-12-films-courts-sur-des-polices-qui-ont-du-caractere), websérie de 12 films courts sur des polices de caractères historiquement importantes

<a id="dictionnaires"></a>
### Dictionnaires
* Pour consulter les dictionnaires (en particulier le LSJ et le Gaffiot, mais bientôt aussi le Bailly) sous un format numérique, je vous recommande la plateforme [Logeion](https://logeion.uchicago.edu/).
* Logeion intègre les versions numérisées des dictionnaires usuels
    * [Gaffiot 2016](http://gerardgreco.free.fr/spip.php?article43)
    * [Bailly 2020](http://gerardgreco.free.fr/spip.php?article52)

<a id="digital-classics--sites-dinformation"></a>
### Digital Classics : sites d'information
* [Stoa Consortium](https://www.stoa.org/)
* [Digital Classicist](https://wiki.digitalclassicist.org/)

<a id="bibliographie-et-zotero"></a>
### Bibliographie et Zotero
* [Zotero](https://www.zotero.org/)
    * Un très complet [tutoriel](https://www.boiteaoutils.info/2012/06/introduction-zotero-30-nouveau-tutoriel/) (également accessible [ici](https://issuu.com/emilienruiz/docs/zotero_19-06-2012))
    * [Les styles de citation](https://www.zotero.org/support/fr/styles)
        * [Citation Styles Library](https://citationstyles.org/)
            * CSL [specifications](https://docs.citationstyles.org/en/stable/specification.html)
        * [Zotero Style Repository](https://www.zotero.org/styles)        
            * styles français : cherchez sur la page le mot « French »
            * voir aussi [csl-france](https://trello.com/b/ACMPVFQf/csl-france)
    * Groupes Zotero
        * [Doing Digital Humanities - A DARIAH Bibliography](https://www.zotero.org/groups/doing_digital_humanities_-_a_dariah_bibliography)
        * [Digital Classics](https://www.zotero.org/groups/digitalclassics)
* [WorldCat](https://www.worldcat.org/)
* [Catalogue collectif de France](https://ccfr.bnf.fr/)
* [Google Scholar](https://scholar.google.com/)
* [L'Année philologique](https://fr.wikipedia.org/wiki/L'Ann%C3%A9e_philologique) (à consulter par le portail de la BU)
* [Ancient World Open Bibliographies](https://ancientbiblio.wordpress.com/)

<a id="biblioth%C3%A8ques-en-ligne"></a>
### Bibliothèques en ligne
* [Project Gutenberg](https://www.gutenberg.org/)
* [TLG](https://stephanus.tlg.uci.edu/) (sur abonnement : à consulter à partir du [portail de la BU](http://bu.parisnanterre.fr/))
* [Perseus Digital Library](https://www.perseus.tufts.edu/hopper/)
    * À consulter sur le [Scaife Viewer](https://scaife.perseus.org/) lorsque les textes y sont disponibles
    * Entrepôts de données du projet Perseus : [bibliothèque grecque](https://github.com/PerseusDL/canonical-greekLit) et [bibliothèque latine](https://github.com/PerseusDL/canonical-latinLit).
* [PHI Classical Latin Texts](https://latin.packhum.org)
* [Diogenes](https://d.iogen.es) (Desktop et Web)

<a id="droit-et-licences"></a>
### Droit et licences
* Licences [Creative Commons](https://creativecommons.org/licenses/)
* Peter Suber, [*Open Access*](https://mitpress.mit.edu/books/open-access), 2012
* Calimaq [Lionel Maurel], [S.I.Lex. Carnet de veille et de réflexion d'un juriste et bibliothécaire](https://scinfolex.com/)
* [Paywall: The Business of Scholarship](https://paywallthemovie.com/paywall) (film documentaire), 2018

<a id="donn%C3%A9es-images-et-cartographie"></a>
### Données, images et cartographie
* [Classical Works Knowledge Base](https://www.cwkb.org)
* [Web des données](https://fr.wikipedia.org/wiki/Web_des_données)
    * [Linking Open Data cloud diagram](https://lod-cloud.net/)
* Prosopographie
    * [Standards for Networking Ancient Prosopographies. Data and Relations in Greco-Roman Names](https://snapdrgn.net/)
* Données spatiales et systèmes d'information géographique (SIG)
    * [Rome Reborn](https://www.romereborn.org/)
    * [Orbis](https://orbis.stanford.edu)
    * [Projet Bretez](https://sites.google.com/site/louisbretez/home)
    * [Virtual St Paul’s Cathedral Project](https://vpcp.chass.ncsu.edu/)
    * [Pelagios](https://pelagios.org/) et [Recogito](https://recogito.pelagios.org/)
    * [Pleiades](https://pleiades.stoa.org/)
    * [Google Ancient Places](https://googleancientplaces.wordpress.com/about/)
    * [Hestia](https://hestia.open.ac.uk/)

<a id="ressources-diverses"></a>
### Ressources diverses
* [Format de données](https://fr.wikipedia.org/wiki/Format_de_donnees)
* Moteurs de recherche : [DuckDuckGo](https://duckduckgo.com/), [Qwant](https://www.qwant.com/)
* [A History of the Internet and Computing in 71 Seconds](https://www.youtube.com/watch?v=QCw8f3-cIzU)
* [How the Internet works](https://arstechnica.com/information-technology/2016/05/how-the-internet-works-submarine-cables-data-centres-last-mile/)

<a id="outils-et-langages"></a>
## Outils et langages

<a id="%C3%89diteur-de-texte--atom"></a>
### Éditeur de texte : Atom
* [Atom](https://atom.io) est l'éditeur que nous utilisons ensemble, disponible pour tout système d'exploitation
    * [Guide](https://flight-manual.atom.io/getting-started/sections/atom-basics/)
    * Packages à installer depuis les préférences d'Atom
        * Language Markdown
        * Markdown Preview Plus
        * Linter Autocomplete Jing
        * TEI Framework
    * À l'installation d'un package, si vous recevez un message d'erreur mentionnant le langage Java, contrôlez qu'il est installé sur votre machine : voici le [lien de téléchargement](https://www.oracle.com/java/technologies/javase-downloads.html) (installez la version "Standard Edition", Java SE, si vous n'avez pas besoin de la version "Standard Edition Development Kit", JDK, destinée aux développeurs et que certains logiciels nécessitent).
* Autres éditeurs gratuits
    * Mac : [Sublime Text](https://www.sublimetext.com/)
    * Linux : Gedit (installé par défaut)
    * Windows : [Notepad++](https://notepad-plus-plus.org/)

<a id="markdown"></a>
### Markdown
* [Tutoriel d'introduction](https://commonmark.org/help/)
* [Markdown](https://daringfireball.net/projects/markdown/)
    * Le [bac à sable](https://daringfireball.net/projects/markdown/dingus) permet de faire des essais.
* [MultiMarkdown](https://fletcherpenney.net/multimarkdown/)
    * Le Multimarkdown est une extension du Markdown qui inclut des fonctions essentielles pour nous : notes, citations, marques de révision, tableaux, images, etc.
    * [MultiMarkdown Guide](https://rawgit.com/fletcher/human-markdown-reference/master/index.html)
* [CriticMarkup](http://criticmarkup.com/)
    * Le Multimarkdown inclut la syntaxe CriticMarkup pour ses fonctions de révision.
* [Sustainable Authorship in Plain Text using Pandoc and Markdown](https://programminghistorian.org/lessons/sustainable-authorship-in-plain-text-using-pandoc-and-markdown) (tutoriel)

<a id="github"></a>
### GitHub
* [GitHub](https://github.com/)
    * Sunoikisis Digital Classics, "Open Source software, command line and Git", 2020 : [présentation de Git](https://www.youtube.com/watch?v=1FDY28DRgso&amp;t=3177), puis [présentation de GitHub](https://www.youtube.com/watch?v=1FDY28DRgso&amp;t=3599)
    * Tutoriel [Hello World](https://guides.github.com/activities/hello-world/) : principes généraux et utilisation de GitHub sur le Web
    * [GitHub Desktop](https://desktop.github.com/) : interface graphique
* Entrepôt de données [Classnum sur GitHub](https://github.com/classnum)

<a id="terminal-unix"></a>
### Terminal Unix
* Pour vous familiariser avec le terminal Unix (également appelé ligne de commande, *shell* et, en l'occurence, *Bash*), suivez ce tutoriel de la plateforme *Programming Historian* : [Introduction to the Bash Command Line](https://programminghistorian.org/lessons/intro-to-bash).
* Sous Windows et sous Mac ou Linux, les commandes varient légèrement. Voici une liste des commandes les plus courantes, extraite d'un [tableau plus complet](https://gist.github.com/carlessanagustin/266171818584b3880f72a625dfa2513b) :

|     Unix     |       Windows       |                                                                      Notes                                                                       |
|--------------|---------------------|--------------------------------------------------------------------------------------------------------------------------------------------------|
| chown, chmod | attrib              | Sets ownership on files and directories                                                                                                          |
| cd           | cd                  | On Windows, cd alone prints the current directory, but on Unix cd alone returns the user to his home directory.                                  |
| pwd          | cd                  | On Windows, cd alone prints the current directory.                                                                                               |
| clear        | cls                 | Clear the terminal screen                                                                                                                        |
| cp           | copy                |                                                                                                                                                  |
| date         | datetime            | Date on Unix prints the current date and time. Date and time on Windows print the date and time respectively, and prompt for a new date or time. |
| rm           | del                 | ¡ATTENTION!                                                                                                                                      |
| rm -r        | deltree             | ¡ATTENTION! Recursively deletes entire directory tree                                                                                            |
| ls           | dir                 | "dir" also works on some versions of Unix.                                                                                                       |
| diff         | fc                  |                                                                                                                                                  |
| grep         | find                |                                                                                                                                                  |
| man          | help                | "help" by itself prints all the commands                                                                                                         |
| mkdir        | mkdir               |                                                                                                                                                  |
| more, less   | more                |                                                                                                                                                  |
| mv           | move                |                                                                                                                                                  |
| shutdown -r  | Reboot, shutdown -r |                                                                                                                                                  |
| rmdir        | rmdir               | ¡ATTENTION!                                                                                                                                      |
| rm -r        | rmdir /s            | ¡ATTENTION! Windows has a y/n prompt. To get the prompt with Unix, use rm -i. The i means "interactive".                                         |
| shutdown -h  | shutdown -s         | Also need -f option to Windows if logged in remotely                                                                                             |
| sort         | sort                |                                                                                                                                                  |
| cat          | type                |                                                                                                                                                  |



<a id="pandoc"></a>
### Pandoc
* [Pandoc](https://pandoc.org) convertit les fichiers d'un format dans un autre.

<a id="regex"></a>
### Regex
* Expressions rationnelles (ou régulières, d'où l'abréviation « regex »), pour réaliser requêtes et transformations avancées
* `?regex`
* Rappels très clairs et adaptés à RStudio
    * [Work with Strings Cheat Sheet](https://www.rstudio.com/resources/cheatsheets/), page 2 (*cheat sheet* du package `stringr`, utile même si vous n'utilisez pas ce package)
    * [RegExCheatsheet](https://www.rstudio.com/wp-content/uploads/2016/09/RegExCheatsheet.pdf)
* [R et les expressions régulières](https://thinkr.fr/r-les-expressions-regulieres/)
* Exercices interactifs : [Regexone](https://regexone.com/)
* Apprendre et tester en ligne : [Regex101](https://regex101.com/)

<a id="html"></a>
### HTML
* Pour information
    * [HTML - Wikipedia (EN)](https://en.wikipedia.org/wiki/HTML), [HTML - Wikipedia (FR)](https://fr.wikipedia.org/wiki/Hypertext_Markup_Language)
    * Les documents officiels (*specifications*) qui décrivent [HTML 4.01](https://www.w3.org/TR/html401/) et [HTML 5 (en cours d'élaboration)](https://html.spec.whatwg.org/). Sachez que le XHTML a été une étape d'évolution du HTML.
* Tutoriels
    * À propos du HTML dans les blogs WordPress, dont notre carnet : [Beginning HTML](https://wordpress.com/support/beginning-html/) et [Advanced HTML](https://wordpress.com/support/advanced-html/)
    * W3C : [HTML Tutorial](https://www.w3schools.com/html/) (en anglais)
    * Mozilla : [Apprendre le Web > HTML](https://developer.mozilla.org/fr/Apprendre/HTML) (chaque page peut être affichée dans diverses langues)
    * En français, sur OpenClassrooms : [Apprenez à créer votre site web avec HTML5 et CSS3](https://openclassrooms.com/courses/apprenez-a-creer-votre-site-web-avec-html5-et-css3)
    * Exemples plus ou moins spectaculaires de styles CSS différents : [CSS Zen Garden](http://www.csszengarden.com)

<a id="xml-et-tei"></a>
### XML et TEI
* [TEI Consortium](https://tei-c.org/)
    * [TEI Guidelines](https://www.tei-c.org/release/doc/tei-p5-doc/en/html/index.html) (site de référence)
    * Liste de discussion de la TEI : [TEI-L](https://listserv.brown.edu/archives/cgi-bin/wa?A0=TEI-L)
* [TEI by Example](https://teibyexample.org/TBE.htm) (tutoriel, exercices et exemples)
    * Module 0 : [Introduction to Text Encoding and the TEI](https://teibyexample.org/tutorials/TBED00v00.htm)
    * Module 7 : [Critical Editing](https://teibyexample.org/tutorials/TBED07v00.htm)
    * [TBE validation service](https://teibyexample.org/tools/TBEvalidator.htm)
* Marjorie Burghart et Elena Pierazzo, [Digital Scholarly Editions: Manuscripts, Texts and TEI Encoding](https://teach.dariah.eu/course/view.php?id=32) (vidéos)
* Marjorie Burghart, [Éditer des sources historiques en ligne grâce à XML](http://mutec.huma-num.fr/?q=guides-Mutec) (guide)
* Marjorie Burghart, [TEI Critical Apparatus Toolbox](http://teicat.huma-num.fr/) (outil de visualisation)
    * Voir l'article [The TEI Critical Apparatus Toolbox: Empowering Textual Scholars through Display, Control, and Comparison Features](https://journals.openedition.org/jtei/1520)
* [Guidelines of the Digital Latin Library](https://digitallatin.github.io/guidelines/LDLT-Guidelines.html) (conventions en cours de développement pour les apparats critiques, même complexes)

<a id="voyant-tools"></a>
### Voyant Tools
* [Site canadien](https://voyant-tools.org/), [site français](http://voyant.tools.huma-num.fr/)
* Aurélien Berra, [Introduction à Voyant Tools](https://github.com/aurelberra/voyant_tools/blob/master/tutorial/voyant_tools_intro_fr.md)

<a id="r-et-rstudio"></a>
### R et RStudio
* [R](https://cran.r-project.org/)
* [RStudio](https://www.rstudio.com/products/rstudio/)
* [RStudio cheatsheets](https://www.rstudio.com/resources/cheatsheets/)
    * Tour détaillé de l'environnement de travail de RStudio : [en anglais](https://github.com/rstudio/cheatsheets/raw/master/rstudio-ide.pdf) et [en français](https://github.com/rstudio/cheatsheets/raw/master/translations/french/rstudio-ide_fr.pdf)
* Trouver des réponses, poser des questions
    * Copier un message d'erreur ou un nom de commande dans un moteur de recherche (à choisir, [DuckDuckGo](https://duckduckgo.com/) plutôt que Google) permet le plus souvent de mieux comprendre un problème assez vite.
    * Forum [StackOverflow, recherche limitée aux discussions concernant R](https://stackoverflow.com/questions/tagged/r)
    * [RSeek.org](https://rseek.org/) (moteur de recherche spécifique)
    * Recommandations du package [Reprex](https://reprex.tidyverse.org/articles/reprex-dos-and-donts.html) – que je ne vous demande pas d'utiliser, mais qui fait le point et donne des liens sur la question du *minimal reproducible example* abordée dans la rubrique <a id="forum--quelques-bonnes-habitudes">Forum : quelques bonnes habitudes</a> du présent document
    * [R Debugging Bingo](https://docs.google.com/presentation/d/1iRUa51RQila_vRYdarFt7MhgH-emmKYQqylK0kgjr3Q/)
* Packages du Tidyverse : [documentation](https://www.tidyverse.org/packages/)
* Site de référence du package de représentation graphique [ggplot2](https://ggplot2.tidyverse.org/)
    * Cédric Scherer, tutoriel « [A Ggplot2 Tutorial for Beautiful Plotting in R](https://cedricscherer.netlify.app/2019/08/05/a-ggplot2-tutorial-for-beautiful-plotting-in-r/) »
    * Yannick Rochat, « [Introduction à ggplot2](https://yrochat.github.io/ggplot2_tuto/ggplot2.nb.html) »
* Hadley Wickham, [*The tidyverse style guide*](https://style.tidyverse.org/)
* [R for Data Science](https://r4ds.had.co.nz) : [modèle d'un projet d'analyse de données](https://r4ds.had.co.nz/introduction.html)
* [Reproducible Research and the Wonders of RMarkdown](https://alycerussell.github.io/ReproducibleResearchOct2019/#1), en particulier [What is this wizardry?!](https://alycerussell.github.io/ReproducibleResearchOct2019/#44) et [What is RMarkdown?](https://alycerussell.github.io/ReproducibleResearchOct2019/#46)
* Kieran Healy, [Data Visualization](https://socviz.co/) (version préliminaire en ligne de Healy Kieran, *Data Visualization: A Practical Introduction*, Princeton, Princeton University Press, 2019)
    * [« How to read an R help page »](https://socviz.co/appendix.html)
* [Initiation au langage et objets de R](https://www.math.univ-toulouse.fr/~besse/Wikistat/pdf/st-tutor2-R-init.pdf)
* [Tutoriel du package `tm`](https://edutechwiki.unige.ch/fr/Tutoriel_tm_text_mining_package)

<a id="latex"></a>
### LaTeX
* Pour produire des PDF avec Pandoc, notamment
* Pour installer LaTeX, suivre les [instructions du site de Pandoc](https://pandoc.org/installing.html)
* [(Xe)LaTeX appliqué aux sciences humaines](https://geekographie.maieul.net/95) (introduction pertinente et francophone, à télécharger librement)

<a id="ocr--tesseract"></a>
### OCR : Tesseract
* [Tesseract](https://tesseract-ocr.github.io/tessdoc/)

<a id="open-refine"></a>
### Open Refine
* [Google Refine/Open Refine](https://openrefine.org)

<a id="cltk"></a>
### CLTK
* The Classical Language Toolkit (en Python) : [CLTK](http://cltk.org/)

<a id="stopwords"></a>
### Stopwords
* [Principes](https://github.com/aurelberra/stopwords/blob/master/rationale.md) des listes utilisées

<a id="lemmatisation"></a>
### Lemmatisation
* [Pyrrha](https://dh.chartes.psl.eu/pyrrha/), environnement de "post-correction" intégrant le service Web [Deucalion](https://dh.chartes.psl.eu/deucalion/)

<a id="expositions-virtuelles"></a>
### Expositions virtuelles
* [Omeka](https://omeka.org/classic/) (publication de métadonnées et de documents)
