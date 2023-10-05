---
autoEqnLabels: false
autoSectionLabels: false
ccsDelim: ", "
ccsLabelSep: " --- "
ccsTemplate: $$i$$$$ccsLabelSep$$$$t$$
chapDelim: .
chapters: false
chaptersDepth: 1
codeBlockCaptions: false
cref: false
crossrefYaml: pandoc-crossref.yaml
crossrefYaml : "
  {/Users/jlebovits/Dropbox/4-Administratif_Affectation_impots/Pyxis/PyxiScience/GitHub_PyxiScience/PyxiScience/5-Scripts/2-Python/Scripts_conversion_jinja_to_Markdown_to_HTML/Perso_Filt.yaml}"
eqLabels: arabic
eqnBlockInlineMath: false
eqnBlockTemplate: |
  +:-------------------------------------------------------------:+-----:+
  | $$t$$                                                         | `    |
  |                                                               | ``{= |
  |                                                               | open |
  |                                                               | xml} |
  |                                                               | <w:  |
  |                                                               | tcPr |
  |                                                               | ><w: |
  |                                                               | vAli |
  |                                                               | gn w |
  |                                                               | :val |
  |                                                               | ="ce |
  |                                                               | nter |
  |                                                               | "/>< |
  |                                                               | /w:t |
  |                                                               | cPr> |
  |                                                               | ```  |
  |                                                               | $    |
  |                                                               | $i$$ |
  +---------------------------------------------------------------+------+
eqnIndexTemplate: ($$i$$)
eqnInlineTemplate: $$e$$$$equationNumberTeX$${$$i$$}
eqnPrefix:
- eq.
- eqns.
eqnPrefixTemplate: $$p$$ $$i$$
equationNumberTeX: \\qquad
figLabels: arabic
figPrefix:
- fig.
- figs.
figPrefixTemplate: $$p$$ $$i$$
figureTemplate: $$figureTitle$$ $$i$$$$titleDelim$$ $$t$$
figureTitle: Figure
lastDelim: ", "
linkReferences: false
listings: false
listingTemplate: $$listingTitle$$ $$i$$$$titleDelim$$ $$t$$
listingTitle: Listing
listItemTitleDelim: .
lofItemTemplate: |
  $$lofItemTitle$$$$i$$$$listItemTitleDelim$$ $$t$$\
lofTitle: |
  # List of Figures
lolItemTemplate: |
  $$lolItemTitle$$$$i$$$$listItemTitleDelim$$ $$t$$\
lolTitle: |
  # List of Listings
lotItemTemplate: |
  $$lotItemTitle$$$$i$$$$listItemTitleDelim$$ $$t$$\
lotTitle: |
  # List of Tables
lstLabels: arabic
lstPrefix:
- lst.
- lsts.
lstPrefixTemplate: $$p$$ $$i$$
nameInLink: false
numberSections: false
pairDelim: ", "
rangeDelim: "-"
refDelim: ", "
refIndexTemplate: $$i$$$$suf$$
secHeaderDelim: 
secHeaderTemplate: $$i$$$$secHeaderDelim[n]$$$$t$$
secLabels: arabic
secPrefix:
- sec.
- secs.
secPrefixTemplate: $$p$$ $$i$$
sectionsDepth: 0
subfigGrid: false
subfigLabels: alpha a
subfigureChildTemplate: $$i$$
subfigureRefIndexTemplate: $$i$$$$suf$$ ($$s$$)
subfigureTemplate: $$figureTitle$$ $$i$$$$titleDelim$$ $$t$$. $$ccs$$
tableEqns: false
tableTemplate: $$tableTitle$$ $$i$$$$titleDelim$$ $$t$$
tableTitle: Table
tblLabels: arabic
tblPrefix:
- tbl.
- tbls.
tblPrefixTemplate: $$p$$ $$i$$
titleDelim: ":"
linkReferences: true
theoremnos-cleveref: True
theoremnos-names:
- id: thm
  name: Theorem
- id: dfn
  name: Definition
---

$$\begin{aligned}
\label{ezrpfire}
&A:=  \begin{pmatrix}1 & 2 & -2\\2 & 1 & -2\\2 & 2 & -3\end{pmatrix}&
& \& & 
&P:=  \begin{pmatrix}1 & 0 & 1\\1 & 1 & 1\\1 & 1 & 2\end{pmatrix}.&
\end{aligned}$${#eq:label1}

$$2=2$$

Egalité ([-@eq:label1])

::: theor
**Theorem 1**. *Le théorème de Fermat est vrai.*%{#eq:label2}
:::

::: theor
**Theorem 2**. *Le théorème de Fermat n'est vrai.*
:::

Par ailleurs

Par ailleursPar ailleurs

Par ailleursPar ailleurs

Par ailleursPar ailleurs

Par ailleursPar ailleurs

Par ailleursPar ailleurs

Par ailleursPar ailleurs

Par ailleursPar ailleurs

Par ailleursPar ailleurs

Par ailleursPar ailleurs

Par ailleursPar ailleurs

Par ailleursPar ailleurs

Par ailleursPar ailleurs

Par ailleursPar ailleurs

Par ailleursPar ailleurs

Par ailleursPar ailleurs

Par ailleursPar ailleurs

Par ailleursPar ailleurs

Par ailleursPar ailleurs

Par ailleursPar ailleurs

Par ailleursPar ailleurs

Par ailleursPar ailleurs

Par ailleursPar ailleurs

Par ailleursPar ailleurs

Par ailleursPar ailleurs

Par ailleursPar ailleurs

Par ailleursPar ailleurs

Par ailleurs
Par ailleurs

Par ailleurs

Par ailleurs

Par ailleurs


Par ailleurs

Par ailleurs

```{#lst:code1 .haskell caption="(Titre du theorème ou de l'exercice)"}
Contenu de ce block
```


On peut donc dire que:
([@lst:code1]) est très vraie





```{#thm:code2 .haskell caption="(Titre du theorème ou de l'exercice)"}
Contenu de ce block
```


On peut donc dire que:
([@thm:code2]) est très vraie



```{#lst:code3 .haskell caption="(Titre du theorème ou de l'exercice)"}
Le théorème de Fermat n'est vrai.
```

On peut donc dire que:
[@lst:code3] est très vraie




<div id="lst:code4" class="listing">
Listing caption
```{.haskell}
main :: IO ()
main = putStrLn "Hello World!"
```
</div>



[@lst:code4] est très vraie