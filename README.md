# Git_and_GitHub_ohjeet
Git ja GitHub ohjeet

Versiohallinta

Versiohallinta on menetelmä, jolla säilötään tietoa ja siihen tehtyjä muutoksia. Tärkeimmät syyt sen käyttöön ovat:

    Varmuuskopiointi: Kaikki muutokset tallennetaan.
    Yhteistyö ja tiedonjako: Mahdollistaa työskentelyn samassa projektissa eri laitteilla ja käyttäjien välillä.

Git

Git on hajautettu versiohallintajärjestelmä, jonka Linus Torvalds kehitti. Se säilyttää tietoja ja pitää kirjaa muutoksista, mahdollistaen yhteistyön ja versionhallinnan.

Git koostuu kolmesta osasta:

    Työkansio: Varsinaiset tiedostot.
    Indeksi: Muutosten välitallennuspaikka.
    Paikallinen repositorio: Kaikki versiot tallennettuna.

GitHub

GitHub on pilvipalvelu, joka mahdollistaa Git-repositorioiden säilytyksen ja jakamisen. Se toimii myös varmuuskopiona tiedoille.

Peruskäyttö:

    Repositorioiden luominen ja hallinta paikallisesti ja pilvessä.
    Synkronointi paikallisen ja etärepositorion välillä:
        Lähetys GitHubiin: git push
        Tietojen hakeminen GitHubista: git pull

Git-komennot

Yleiset komennot:

    Repositorio käyttöön: git init
    Muutosten lisääminen: git add .
    Commitin luominen: git commit -m "viesti"
    Tilan tarkistus: git status
    Historian tarkistus: git log

Branch (haarat):

    Uusi haara: git branch nimi
    Haaran yhdistäminen päähaaraan: git merge nimi
    Haaran poistaminen: git branch -d nimi

Fork ja Upstream

Fork: Kopio toisen käyttäjän repositoriosta.
Upstream: Alkuperäisen repositorion synkronointi paikalliseen hakemistoon:

    Lisää: git remote add upstream <URL>
    Synkronoi: git fetch upstream

Tiivistäen, Git ja GitHub ovat olennaisia työkaluja yhteistyöskentelyyn ja varmuuskopiointiin ohjelmistokehityksessä.
