# Data-analyse, Veilig en vertrouwd op jouw apparaat

Per kantoor zullen andere regels en procedures gelden voor het omgaan met data. Gebruikelijk is dat prive-cloud omgevingen, zoals Google Collab, niet gebruikt mogen worden voor het verwerken van vertrouwelijke data. Dit omdat de data dan op een server van een derde partij staat. In deze opdracht gaan we daarom een lokale omgeving opzetten waarin we data kunnen verwerken.

Je zult nog steeds werken met Notebooks. Alleen zie je niet meer "Google Collab" maar "Jupyter" in de titelbalk staan. Jupyter is een open-source project dat je lokaal kunt installeren. Jupyter is feitelijk je eigen Google Collab omgeving - maar dan op je eigen computer.

## Jupyter installeren

Om Jupyter te installeren heb je Python nodig. Google heeft Python op de Collab server geinstalleerd. Omdat we nu op jouw computer gaan werken, moet je het nu lokaal installeren. Dat is eenvoudiger dan het klinkt. We gebruiken hiervoor Anaconda, een bekende distributie:

1. Download Anaconda van https://www.anaconda.com/products/individual
2. Installeer Anaconda
3. Start Anaconda Navigator
4. Klik op "Launch" bij Jupyter Notebook

Je ziet nu een browser openen met Jupyter. Je kunt nu een nieuw Notebook aanmaken of een bestaand Notebook openen.

## Jupyter Openen
1. Start Anaconda Navigator
2. Klik op "Launch" bij Jupyter Notebook

Tip: omdat je nu op je eigen apparaat werkt, kun je ook veel eenvoudiger databestanden openen die op jouw computer staan. Je kunt bijvoorbeeld een Excel bestand openen door de volgende code uit te voeren in een Python Notebook:

```python
import pandas as pd
df = pd.read_excel("C:\\Users\\jouwgebruikersnaam\\Documents\\bestand.xlsx")
```


## Packages bijwerken en installeren
Om de code die we je in deze voorbeelden lieten zien te kunnen uitvoeren, heb je een aantal packages nodig. Deze packages zijn niet standaard geinstalleerd.

Je kunt ze installeren door een Jupyter Notebook te openen, en de volgende code uit te voeren dat notebook:

```python
!pip install pandas
!pip install numpy
!pip install matplotlib
!pip install seaborn
```
