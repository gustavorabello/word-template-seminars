### Introduction

This is the README for using the `ppgem-word-template` bundle MS Word files
required to compile correctly the template paper of the internal seminars of PPG-EM @UERJ.


### Data fields 

#### Title

- `\Title`: adds the title of your paper.

Use: titles must be CAPITALISED.

#### Author and advisor names

- `\AuthorName`: author's name 
- `\CorrEmail`: corresponding e-mail
- `\AdvisorName`: your advisor's name 
- `\CoAdvisorName`: your co-advisor's name
- `\Year`: year to which the paper is attached in the PPG-EM seminar series


#### Institution

- `\InstA`: default is your institution, for instance UERJ, as it should
  be if you are a member of PPG-EM
- `\InstB`: your co-advisor's institution

Use: 

``` latex
\InstA{State University of Rio de Janeiro} 
\InstB{Federal University of Rio de Janeiro} 
```
#### Keywords 

Add up to 4 keywords to your paper in the environment `keywords` by separating them by commas.  

Use:

``` Word 
    keyword_1, keyword_2, keyword_3, keyword_4
```

### Files and directories

- `main.doc` is the MS Word source file
- `refs.bib` is the bibTeX reference file
- `logos/` is the logo's directory
- `figs/` is the suggested directory where you may store your figures
- `instructions.txt` is the raw version of `README.md`

### Meta

- Authors: 
  - Gustavo PEIXOTO DE OLIVEIRA, D.Sc. (maintainer) :[mailto](mailto:gustavo.oliveira@uerj.br)
  - Leon Matos Ribeiro de LIMA, M.Sc. :[mailto](mailto:matosleon@gmail.com)
  - Gustavo R. ANJOS, Prof. :[mailto](mailto:gustavo.anjos@uerj.br)


### Version notes

- release



