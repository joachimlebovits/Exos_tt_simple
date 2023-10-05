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
---

$$\begin{aligned}
\label{ezrpfire}
&A:=  \sympy{A}&
& \& & 
&P:=  \sympy{P}.&
\end{aligned}$$

$$2=2$$

Egalité [\[ezrpfire\]](#ezrpfire){reference-type="eqref"
reference="ezrpfire"}

::: theor
**Theorem 1**. *Le théorème de Fermat est vrai.*
:::

::: theor
**Theorem 2**. *Le théorème de Fermat n'est vrai.*
:::
