title: "Mein Markdown Meilenstein"
author: "Cristina Salazar"
output:
  html_document:
    toc: true
    toc_depth: 3
    number_sections: true
---

```{r setup, include=FALSE}
knitr::opts_chunk$set(
	message = FALSE,
	warning = FALSE,
	include = FALSE
)
```



# Mein erstes Markdown-Dokument
Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua. Hauptüberschrift und einen Unterüberschrift

\tableofcontents

## Mein Datenmanifest
* Digitaler Selbstschutz hilft dabei, Datenmissbrauch zu vermeiden. Besonders sensible Zugangsdaten können in die falschen Hände gelangen und somit gravierende Folgen haben.

### Wem gehören meine Daten?
* Große Unternehmen wie 
1. *Google* 
1. *Apple* 
1. *Facebook* 
haben exklusiven Zugang zu Informationen, die wir über uns auf digitale Medien preisgeben.

### Datensicherheit und ich?
* Die Kontrolle, die wir über **unsere persönlichen Daten** haben, ist geringer als ich gedacht habe.

### Was hat sich verändert?
* Nun achte ich darauf, welche Informationen ich online veröffentliche. 

# Kleine Einführung in Variablen
1. Bitte ergänzen Sie in dem kleinen Skript unten ihr Geburtsjahr. 

```{r Wie lange muss ich bis zur Rente arbeiten?}
geburt <- 2000 # bitte Geburtsjahr eingeben [YYYY eingeben]
alter <- 2021 - geburt
# wir berechnen Ihr Alter im Jahr 2020 (für das gesamte Jahr)
alter

# Wir berechnen Ihr Rentenalter und gehen davon aus, dass Sie mit 69 in  Rente gehen können.
rentenalter <- geburt + 69
rentenalter

# Wir gehen davon aus, dass Sie in drei Jahren anfangen werden zu arbeiten.
arbeitsbeginn <- 2023
arbeitsjahre <- rentenalter - arbeitsbeginn

# Voila: wenn alles klappt, arbeiten Sie so lange.
arbeitsjahre

```
# Variablen im Reporting verwenden
## Variablen in Dokumente einbauen.
Wir können die Ergebnisse von Variablen direkt in unseren Report einbetten, wenn der codechunk zuvor ausgeführt wurde. Schauen Sie sich das Beispiel unten an und ersetzen Sie die letzte Variable davon. 

### Einsatz von dynamischen Variablen im Dokument
Ich bin im Jahr `r geburt` geboren und werde im Jahr 2021 `r alter` Jahre alt sein. Das bedeutet, dass ich wahrscheinlich `r arbeitsjahre` Jahre arbeiten darf. Wenn Sie mal nachdenken, wie das Leben vor `r arbeitsjahre` Jahren, also im Jahr `r 2021-arbeitsjahre` aussah (ohne Smartphone oder Netflix), dann kommt in den nächsten `XX ersetzen Sie hier den richtigen Wert` Jahren ganz schön viel Veränderung auf mich zu!  

### Eine kleine Geschichte mit Text- und Zahlen-Variablen

Schreiben Sie eine  kleine Geschichte mit den Werten, die Sie in dieses Dokument einbauen. 

```{r Mini-Geschichte}
hund_name <- "Kira"
katze_name <- "Luna"
google_trefferanzahl <- 44.400.000

```
# Kira und Luna verbringen viel Zeit miteinander. Auch wenn es auf den ersten Blick nicht so aussieht, weiß ich, dass sie sich mögen. Letztens habe ich ihre Namen bei Google gesucht und 44.400.000 Ergebnisse bekommen. Anscheinend gibt es viele Instagram Accounts, die die Wörter Kira und Luna enthalten. 
