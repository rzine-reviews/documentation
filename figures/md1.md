## Citation {-}

```{r Citation, echo=FALSE}

rref <- bibentry(
   bibtype = "article",
   title = "Titre de la fiche",
   author = person("Auteur.e 1", "Auteur.e 2" ),
   journal = "Rzine.fr",
   publisher = "FR CIST",
   year = 2021,
   url = "https://...")


``` 

`r capture.output(print(rref))`

### BibTex : {-}

```{r generateBibTex, echo=FALSE}

writeLines(toBibtex(rref), "cite.bib")
toBibtex(rref)

``` 


<br/>