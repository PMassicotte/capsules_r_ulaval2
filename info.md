## webr and checkdown

- https://cran.r-project.org/web/packages/checkdown/
- https://datavizf24.classes.andrewheiss.com/lesson/02-lesson.html#select-the-best-file-type
- https://github.com/andrewheiss/datavizf24.classes.andrewheiss.com/blob/e6ad108f9892cf31c53cf4a33aebe1499f912aeb/lesson/02-lesson.qmd#L43

## Data files

- BIO1006_H2018_Echantillon.csv -> https://tinyurl.com/bio1006csv
- BIO1006_H2018_Echantillon.dat -> https://tinyurl.com/bio1006dat
- mpg.csv -> https://tinyurl.com/bio1006mpg
- pew.csv -> https://tinyurl.com/bio1006pew

## Callout blocks

::: {.callout-tip}
N'oubliez pas qu'il faut éviter d'utiliser des caractères accentués dans les noms de variables. C'est pourquoi on nommera la colonne `espece` et non `espèce`.
:::

## Hints for the exercises

```r
check_hints(
  hint_text = c(
    "Attention à la casse (minuscule ou majuscule) des fonctions.",
    "`type()` n'est pas une fonction de base de R."
  ),
  hint_title = "Cliquez ici pour obtenir un indice!",
  list_title = "<strong>ⓘ  Indice(s)</strong>"
)
```
