---
title: 'Training systems biology curators in building interoperable and reusable models following a learning path approach'
title_short: 'Learning Paths for biocurators in systems biology'
tags:
  - systems biology
  - biocuration
  - modelling
  - learning path
  - training
authors:
  - name: Livia Perfetto
    orcid: 0000-0003-4392-8725
    affiliation: 1
  - name: Sandra Orchard
    orcid: 0000-0002-8878-3972
    affiliation: 2
  - name: Alexander Mazein
    orcid: 0000-0001-7137-4171
    affiliation: 3
  - name: Ulrike Wittig
    orcid: 0000-0002-9077-5664
    affiliation: 4
  - name: Martina Kutmon
    orcid: 0000-0002-7699-8191
    affiliation: 5
  - name: Rahuman Sheriff
    orcid: 0000-0003-0705-9809
    affiliation: 2
  - name: Chris Evelo
    orcid: 0000-0002-5301-3142
    affiliation: 6
  - name: Mihail Anton
    orcid: 0000-0002-7753-9042
    affiliation: 7
  - name: Luana Licata
    orcid: 0000-0001-5084-9000
    affiliation: 8
  - name: Marek Ostaszewski
    orcid: 0000-0003-1473-370X
    affiliation: 3
affiliations:
  - name: Universita degli Studi di Roma La Sapienza Dipartimento di Biologia e Biotecnologie Charles Darwin, Roma, Lazio, IT
    index: 1
  - name: European Bioinformatics Institute, Hinxton, UK
    index: 2
  - name: University of Luxembourg, Luxembourg, LU
    index: 3
  - name: Heidelberger Institut f&uuml;r Theoretische Studien, Heidelberg, Baden-W&uuml;rttemberg, DE
    index: 4
  - name: Maastricht Centre for Systems Biology (MaCSBio), Maastricht University, Maastricht, Limburg, NL
    index: 5
  - name: Department of Bioinformatics - BiGCaT, NUTRIM, Maastricht University, Maastricht, Limburg, NL
    index: 6
  - name: Chalmers University of Technology, Gothenburg, SE
    index: 7
  - name: University of Rome Tor Vergata, Rome, Lazio, IT
    index: 8
date: 7 November 2022
cito-bibliography: paper.bib
event: Paris22
biohackathon_name: "BioHackaton2022"
biohackathon_url:   "http://biohackathon-europe.org"
biohackathon_location: "Paris, France, 2022"
group: ELIXIR Systems Biology Community, ELIXIR Biocuration Focus Group
# URL to project git repo --- should contain the actual paper.md:
git_url: https://github.com/biohackrxiv/bhxiv-gen-pdf
# This is the short authors description that is used at the
# bottom of the generated paper (typically the first two authors):
authors_short: Livia Perfetto \emph{et al.}
---

# Introduction

As part of the one week Biohackathon 2022 in Paris, France, we formed
a working group ...

Citation examples:
[@agreesWith:reasoned2nd], PhD thesis
[@ByrdPhD], and [online](https://www.youtube.com/watch?v=eQL48qYDwp4)
[talks](https://www.youtube.com/watch?v=o3AHnyEf7IE).

Itemisation example:
\begin{itemize}
\item researched state-of-the-art mapping between graph stores and logic programming;
\item created methods for bridging between SPARQL and in-memory data representations using Prolog;
\item extended the Biolink model;
\item and added Relational Biolink type inference for mediKanren.
\end{itemize}

# Results

## Approach to construct a Learning Path

![Initial sketch of the areas and potential training resources \label{fig1}](./1_draft.jpg)

## Controlled vocabulary

`has_mouse_ortholog` predicate:

```
    feature_in_range(grch38:"X", 10000000, 20000000, HumanGene),
    has_mouse_ortholog(HumanGene, MouseGene)
```

## Mapping the TeSS entries

## Summary and outlook

The following tasks were accomplished as part of the BioHackathon (example):

\begin{enumerate}
\item Represent datasets and their related metadata
\item Represent family and pedigree information to support clinical knowledge
\item Make the provenance model more rich and descriptive
\end{enumerate}

For future work, the group will ensure that the new classes added to
the model will have appropriate mappings to other schemas and
ontologies.

Future work includes:

1. integrating this work into the Racket mediKanren code;
2. integrating with the data categories in the KGs;
3. and creating query editor with decent type error messages, autocompletion,
   query synthesis, etc.

# Discussion

## Acknowledgements

We thank the organizers of the NBDC/DBCLS BioHackathon 2019 for
travel support for some of the authors.

## References
