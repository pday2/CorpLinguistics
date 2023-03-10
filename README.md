"Obama Speech Correspondence Analysis"

Peter Day

Methods of Corpus Linguistics

15 January, 2023

This github repository contains an R project with the following subfolders and files around the paper titled "Obama Speech Correspondence Analysis":

## Raw data
- Folder "DataUCSB" with three subfolders: "international", "national" and "sotu" contains Barack Obama speeches in raw text files separated into three categories in each of the three subfolders.
- Folder: "assets" with four text documents: 
- content-words.txt: list of content words from previous topic modeling project to be used as features in CA
- function-words.txt: list of function words (prepositions) to be used as features in CA
- kaggle-stopwords.txt: long list of stop words from Kaggle.com
- stop-list.txt: short list of stop words from class

## Scripts
- no external scripts

## Quarto
- obama.qmd: Source quarto document with all the R script to generate the paper
- obama.pdf, obama.html: output files generated by the obama.qmd quarto file

## Helpers
- bibliography.bib: bibliography of literature references
- packages.bib: bibliography of R related references, written by 'knitr::write_bib' in obama.qmd
- unified-style-sheet-for-linguistics.csl: the stylesheet for references
