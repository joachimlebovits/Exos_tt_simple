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

$$\protect\hypertarget{eq:label2}{}{\begin{align*}
&A:=  \begin{pmatrix}1 & 2 & -2\\2 & 1 & -2\\2 & 2 & -3\end{pmatrix}&
& \& & 
&P:=  \begin{pmatrix}1 & 0 & 1\\1 & 1 & 1\\1 & 1 & 2\end{pmatrix}.&
\end{align*}}\label{eq:label2}$$

$$\protect\hypertarget{eq:label}{}{ x = 2 }\label{eq:label}$$

On voit que l'équation ( [\[eq:label\]](#eq:label){reference-type="ref"
reference="eq:label"}) indique que $x$ vaut $2$.

Par ailleurs, l'égalité
([\[eq:label2\]](#eq:label2){reference-type="ref"
reference="eq:label2"}) montre que:
