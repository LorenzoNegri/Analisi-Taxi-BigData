# NYC Taxi Big data
# Bonifica, Elaborazione, Analisi e Data-mining con RevoScale R
Data Science case study for a Microsoft 213x Class Project

Lorenzo Negri, April 2018

Applications used: Microsoft R Open, Visual Studio, RevoScaleR libraries


## Obbiettivi del progetto 

Lo scopo di questo progetto è dimostrare la possibilità di analizzare dati e applicare algoritmi di previsioni in ambiente Microsoft R con dati CSV di capienza superiore ai 6GB. Il set di dati (TLC Trip Record Data), che riguardano la telemetria, le tempistiche e le operazioni di pagamento, di tutti i clienti Taxi della città di New York, è reso pubblicamente disponibile dal dipartimento dei trasporti della città: NYC.gov Taxi and Limousine Commission (TLC). Per questo progetto verranno utilizzati i dati relativi ai primi sei mesi dell’anno 2016. Ogni file CSV grezzo ha una dimensione di circa 2GB. Il totale di 12GB di dati solitamente riempirebbero solo loro la metà della memoria disponibile su un singolo personal computer da ufficio. Un server può avere una capacità di memoria molto più grande, ma in Cloud Computing o su un server utilizzato da molti utenti contemporaneamente, R Studio può esaurire molto rapidamente la memoria. Questa repository ha lo scopo di illustrare le tecniche utilizzate per poter elaborare comodamente dati di grandi dimensioni utilizzando RevoScale R con MS R Open e Visual studio, praticamente ovunque.

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


