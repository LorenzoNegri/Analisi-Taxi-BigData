# NYC Taxi Big data
# Bonifica, Elaborazione, Analisi e Data-mining con RevoScale R
Data Science case study for a Microsoft 213x Class Project

Lorenzo Negri, April 2018

Applications used: Microsoft R Open, Visual Studio, RevoScaleR libraries


## Obbiettivi del progetto 

Lo scopo di questo progetto è dimostrare la capacità di analizzare dati e applicare algoritmi di previsioni in ambiente Microsoft R con dati CSV di capienza superiore ai 6GB. Il set di dati (TLC Trip Record Data), che riguardano la telemetria, le tempistiche e le operazioni di pagamento, di tutti i clienti Taxi della città di New York, è reso pubblicamente disponibile dal dipartimento dei trasporti della città: NYC.gov Taxi and Limousine Commission (TLC). Per questo progetto verranno utilizzati i dati relativi ai primi sei mesi dell’anno 2016. Ogni file CSV grezzo ha una dimensione di circa 2GB. Il totale di 12GB di dati solitamente riempirebbero solo loro la metà della memoria disponibile su un singolo personal computer da ufficio. Un server può avere una capacità di memoria molto più grande, ma in Cloud Computing o su un server utilizzato da molti utenti contemporaneamente, R Studio può esaurire molto rapidamente la memoria. Questa repository ha lo scopo di illustrare le tecniche utilizzate per poter elaborare comodamente dati di grandi dimensioni utilizzando RevoScale R con MS R Open e Visual studio, praticamente ovunque.

### Indice ed Argomenti applicati:

[1. Panoramica Dati, Esplorazione e Statistiche riassuntive](https://github.com/LorenzoNegri/Analisi-Taxi-BigData/blob/master/01_Panoramica_Esplorazione_Statistiche.pdf)

- Installazione Pacchetti aggiuntivi
- Importazione e conversione CSV file in formato XDF (external data frame)
- Controllo preliminare dei dati
- Analisi esplorativa dei dati

[2. Trasformazione e Integrazione dati](https://github.com/LorenzoNegri/Analisi-Taxi-BigData/blob/master/02_Trasformazione_Integrazione.pdf)

- Controllo tipologie colonna
- Bonifica dati
- Trasformazioni semplici e complesse con rxDataStep
- Utilizzo di librerie GIS (Geographic Information System) e shapefile per integrare dati
- Trasformazione e integrazione con dati geografici da shapefile

[3. Analisi e Visualizzazioni](https://github.com/LorenzoNegri/Analisi-Taxi-BigData/blob/master/03_Analisi_Visualizzazioni.pdf)

- Analisi dati a livello di quartiere e distanze percorse
- Analisi Outliers
- Visualizzazioni delle distribuzione delle corse taxi
- Schemi riccorrenti nel tempo

[4. Clustering e Modeling](https://github.com/LorenzoNegri/Analisi-Taxi-BigData/blob/master/04_Clustering_Modelling.pdf)

- Visualizzazione grafica con libreria ggmap e Google maps API
- K-means clustering per raggruppare i dati in base alla longitudine e alla latitudine
- Modellazione lineare
- Analisi risultati di previsione
- Decision Tree e Random Forest
- Confronto algoritmi
- Misurazione e miglioramento prestazione predittiva

[5. Deploying e Ridimensionamento](https://github.com/LorenzoNegri/Analisi-Taxi-BigData/blob/master/05_Deploying_Ridimensionamento.pdf)

- Interfaccia con SQL server
- In-database analytics


