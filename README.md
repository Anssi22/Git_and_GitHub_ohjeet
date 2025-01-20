# Git_and_GitHub_ohjeet

![](GitHub_kuva.jpeg)

# :smile: 1. Yleistä :smile:

### 1.1 Versiohallinta
<div>
  <img src="https://media3.giphy.com/media/v1.Y2lkPTc5MGI3NjExbXU3aWF6eWRuY3g3cXYyeTRvamc1bHBkam5pY2w0dGpmODQ4ZWJpNyZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/ZVik7pBtu9dNS/giphy.gif" alt="GIF 1" width="400">
  <img src="https://media4.giphy.com/media/v1.Y2lkPTc5MGI3NjExNjlzZjAzejcxcDFjdDhzZHc2d25udW83cmN1MnduaGJ3YzZudWt4eCZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/A06UFEx8jxEwU/giphy.gif" alt="GIF 2" width="400">
</div>

Versiohallinta on menetelmä, jolla säilötään tietoa ja siihen tehtyjä muutoksia. Tärkeimmät syyt sen käyttöön ovat:

    Varmuuskopiointi: Kaikki muutokset tallennetaan.
    Yhteistyö ja tiedonjako: Mahdollistaa työskentelyn samassa projektissa eri laitteilla ja käyttäjien välillä.

### 1.2 Git

Git on hajautettu versiohallintajärjestelmä, jonka Linus Torvalds kehitti. Se säilyttää tietoja ja pitää kirjaa muutoksista, mahdollistaen yhteistyön ja versionhallinnan.

Git koostuu kolmesta osasta:

    Työkansio: Varsinaiset tiedostot.
    Indeksi: Muutosten välitallennuspaikka.
    Paikallinen repositorio: Kaikki versiot tallennettuna.


```mermaid
graph TD;
    A[Working Directory] --> B[Staging Area: git add]
    B --> C[Repository: git commit]
```


### 1.3 GitHub

GitHub on pilvipalvelu, joka mahdollistaa Git-repositorioiden säilytyksen ja jakamisen. Se toimii myös varmuuskopiona tiedoille.

Peruskäyttö:

    Repositorioiden luominen ja hallinta paikallisesti ja pilvessä.
    Synkronointi paikallisen ja etärepositorion välillä:
    Lähetys GitHubiin: git push
    Tietojen hakeminen GitHubista: git pull

# 2. Git-komennot

### 2.1 Yleiset komennot:

    Repositorio käyttöön: git init
    Muutosten lisääminen: git add
    Commitin luominen: git commit -m "viesti"
    Tilan tarkistus: git status
    Historian tarkistus: git log

### 2.2 Branch (haarat):

    Uusi haara: git branch nimi
    Haaran yhdistäminen päähaaraan: git merge nimi
    Haaran poistaminen: git branch -d nimi
    
Esimerkki haaroista:

```mermaid
gitGraph
commit
commit
branch AnssinHaara
checkout AnssinHaara
commit
checkout main
branch MoonanHaara
checkout MoonanHaara
commit
checkout main
merge AnssinHaara
commit
merge MoonanHaara
commit
```
    
### 2.3 Fork ja Upstream

Fork: Kopio toisen käyttäjän repositoriosta.
Upstream: Alkuperäisen repositorion synkronointi paikalliseen hakemistoon:

    Lisää: git remote add upstream <URL>
    Synkronoi: git fetch upstream

Tiivistäen, Git ja GitHub ovat olennaisia työkaluja yhteistyöskentelyyn ja varmuuskopiointiin ohjelmistokehityksessä.
---
![](koodaaja.jpg)


