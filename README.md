# strategic-inference
Based on external trends, strategies and business models, the business drivers (BD) need to be derived. The BD will yield business requirements (BR) that will themselves be translated into architecture requirements (AR) and finally be mapped onto architecture components (AC).

Idea:
Separate repositories (nodes) for:
a. (external) trends (TR)
b. strategies and business models (SB)
c. business drivers (BD)
d. business requirements (BR)
e. architecture requirements (AR)
f. architecture componentes (AC)

To link the entries between the repositories are edges as links between the entries inside the different repositories. Relationships m:n are possible, i.e. each entry of a repository can be be linked to one or more entries in another repository. But only links between a/b, a/c, b/c, c/d, d/e, e/f are allowed.
Currently it is not definied, whether edges shall carry additional information (attributes).

Presentation:
Each entry of each repository shall be presented as a single form in an overview page. It starts on the left hand side with a. and all entries of a. are displayed in a single colum. The next column on the sheet contains b.-entries and so on.
The edges between the entries are displayed as lines. Colour-coding is not yet completely definied, but there will be different colours and/or widths depending on the amount of entries connected between the repositories.
It will be necessary to identify those entries within AC and/or AR, that are only linked to one SB. There needs to be some kind of highlighting of those connections.

New entries need to be added to the repositories any time. Entries must only be removed if it is not assigend to any edge any longer.
Szenarios are currently not in scope. Validity periods are currently not in scope.

