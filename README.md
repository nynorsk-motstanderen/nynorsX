# nynorsx

Nynorsk...

Aperitum i Docker med Nynorsk til Bokmål language pack.

https://www.nb.no/sprakbanken/ressurskatalog/oai-nb-no-sbr-80/

---

## Requirements

-   Python versjon 3 (Python3)
-   Docker Desktop
-   Nynorsk motstand

# Installasjon

<br/><br/>

## 1 Installer Docker Desktop for Windows eller MacOS

[https://docker.com/products/docker-desktop/](https://www.docker.com/products/docker-desktop/).

Installer og start, Docker Dekstop applikasjonen må kjøre hele tiden dette programmet skal brukes. Den som bruker programmet må ha pc'en plugget inn i laderen, Docker krever relativt mye kraft.
<br/><br/>

## 2 Last ned zip filen i Downloads og unzip - Kjør deretter følgende kommandoer med admin rettigheter

<br/>
[Klikk her for å laste ned](https://github.com/nynorsk-motstanderen/nynorsX/archive/refs/heads/main.zip)

### MacOS i terminal.app

I rekkefølge, en etter en.
<br/>
`mkdir /Users/$User/Documents/eksamensFiler/ && mkdir /Users/$User/Documents/eksamensFiler/ferdigTekst` <br/>
`cd /Users/$USER/Downloads/nynorsX-main`<br/>
`sudo docker build -t apertium --no-cache .`<br/>

### Windows - FUNKER IKKE ENDA

Åpne terminal som administrator i den nedlastede mappen
`docker build -t apertium --no-cache .`
<br/><br/>

# 3 Start Docker containeren

`docker run --name apertiumDockerContainer -t -d -v /Users/$USER/Documents/watchedFolder:/src apertium`

<br/><br/>

## 4 Kjør python programmet med Python3

`python3 folderWatcherAperitumLocal.py`

<br/><br/>

## Hvordan oversetter jeg?

Lagre filen din i eksamensFiler/ mappen, ikke ha mellomrom i navnet. Og vent noen sekunder til programmet spytter ut den oversatte filen i ferdigTekst/ mappa

---

<br/><br/><br/>

### - 🐻‍❄️ Isbjørnen
