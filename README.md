# Seminario estate GIS 2020 UNIPD

Analisi geografica di dati sul [**COVID-19**](https://github.com/pcm-dpc/COVID-19) sfruttando le potenzialità del _calcolatore dei campi_ ![](https://raw.githubusercontent.com/gbvitrano/HfcQGIS/master/img/mActionCalculateField.png) di [**QGIS**](https://qgis.org/it/site/) e i grafici di  [**DataPlotly**](https://www.faunalia.eu/it/dev/dataplotly) ![](https://raw.githubusercontent.com/ghtmtt/DataPlotly/master/DataPlotly/icons/dataplotly.svg)

<!-- TOC -->

- [Seminario estate GIS 2020 UNIPD](#seminario-estate-gis-2020-unipd)
  - [Relatore](#relatore)
  - [Data, luogo e durata](#data-luogo-e-durata)
  - [Piattaforma](#piattaforma)
  - [Programma](#programma)
  - [Stampe PDF](#stampe-pdf)
  - [Dati](#dati)
  - [Contatti](#contatti)
  - [Sitografia](#sitografia)
- [](#)

<!-- /TOC -->

[![GitHub license](https://img.shields.io/badge/License-Creative%20Commons%20Attribution%204.0%20International-blue)](https://github.com/pigreco/seminario-estate-gis-2020/blob/master/license)
[![GitHub commit](https://img.shields.io/github/last-commit/pcm-dpc/COVID-19)](https://github.com/pigreco/seminario-estate-gis-2020/commits/master)

## Relatore

- **Totò FIANDACA** (Socio [GFOSS.it](https://gfoss.it/), membro [QGIS Italia](http://qgis.it/), membro [OpenDataSicilia](http://opendatasicilia.it/) )

![](imgs/loghi_small.png)

## Data, luogo e durata

- 24/06/2020 con orario 17.30-19.30
- on-line
- due ore

## Piattaforma

- ZOOM

## Programma

1. Dove trovare i dati italiani sul [**COVID-19**](https://github.com/pcm-dpc/COVID-19), chi li raccoglie e come sono strutturati;
   1. come usare file csv remoti;
   2. come forzare il tipo di dato su file CSV remoti;
2. dove sono gli [shapefile ISTAT](https://www.istat.it/it/archivio/222527) dei confini amministrativi italiani, come sono strutturati e come scaricarli;
   1. differenza tra shapefile generalizzati e non, quale scaricare;
   2. perché ottengo 4 cartelle se scarico gli shapefile ISTAT;
3. dove sono i dati sulla [popolazione residente italiana ISTAT](http://dati.istat.it/Index.aspx?DataSetCode=DCIS_POPRES1), come scaricarli;
   1. sito I.Stat popolazione residente al 1° gennaio;
   2. [alternative](https://pigrecoinfinito.com/2020/05/16/scaricare-i-dati-sulla-popolazione-residente-italiana-non-e-mai-stato-cosi-facile/) più veloci per scaricare la serie temporale dal 2011 al 2019;
   3. uso riga di comando in win10 [WSL](https://turbolab.it/sottosistema-windows-linux-wsl-3308/linux-windows-10-grande-guida-wsl2.-come-installare-sottosistema-windows-linux-wsl-eseguire-programmi-accedere-file-video-895);
   4. [VisiData](https://www.visidata.org/about/) per analizzare i dati;
4. come importare i dati scaricati in **QGIS**;
   1. metodo classico tramite il datamana;
   2. metodo moderlo tramite Drag&Drop;
5. calcolare incidenza dati **COVID-19** con il **field calc**;
   1. perché NON usare i dati assoluti sul COVID-19 per la rappresentazione grafica;
   2. perché usare l'incidenza dei parametri medici su 10k abitanti;
6. come collegare i dati sul **COVIS-19** agli shapefile **ISTAT**;
   1. concetto di JOIN tabellare;
   2. concetto di relazione 1:m;
7. come creare grafici cumulati e giornalieri usando DataPlotly;
   1. differenza tra grafici cumulati e giornalieri;
   2. come creare grafici con DataPlotly;
   3. come calcolare i valori giornalieri usando il field calc;
8. come creare una atlas con grafici dinamici;
   1. compositore di stampe, layout;
   2. atlante e dataplotly per gli atlas;
9.  come stampare in serie.
    1.  in PDF;
    2.  immagini png,jpg

## Stampe PDF

![](./imgs/img_01.png)

## Dati

- **shapefile ISTAT** : <https://www.istat.it/it/archivio/222527>
- **CSV popolazione residente ISTAT**: <http://dati.istat.it/Index.aspx?DataSetCode=DCIS_POPRES1>
- **CSV remoti** : 

---

## Contatti

* **Mail**: <pigrecoinfinito@gmail.com>
* **Facebook**: <https://www.facebook.com/pigreco314>
* **Twitter**: <https://twitter.com/totofiandaca>
* **Telegram**: <https://t.me/pigreco71>

## Sitografia

* **blog**: <https://pigrecoinfinito.com/>
* **canale youtube**: <http://www.youtube.com/c/TotòFiandaca>
* **HfcQGIS**: <http://hfcqgis.opendatasicilia.it/it/latest/index.html>
* **Tansignari**: <http://tansignari.opendatasicilia.it/it/latest/#>
* **data.world**: <https://data.world/pigrecoinfinito>
* **github**: <https://github.com/pigreco>
* **gitlab**: <https://gitlab.com/pigr3co>
* **Canale Telegram** : <https://t.me/pigrecoinfinito>

# 