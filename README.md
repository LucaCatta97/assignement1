# Assignment #1




Per far funzionare la repository oltre a Git installato sul pc
 https://git-scm.com/downloads
 serve anche l'estensione LFS
 https://git-lfs.github.com/
 
 Better use Pycharm
 
 
 ##ORGANIZZAZIONE

####1)TODO pulire dati:

a) TODO c'è da verificare che il Timestamp siano corretti e corrispondenti con Trip second
a) TODO Togliamo gli outlier usnado il Winsorizing però selezioniamo i percentili manualmente in base
    alla forma dei dati
    
    **CONCLUSIONI di Luca del 31/10/2020** gli outlier principali sono Trips Second and Trips Miles. Secondo me
    è meglio applicare il trimming invece del Winsorizing almeno per i valori oltre il 99.9th percentile
    mentre quelli sotto si riallineano col Winsorizing.
    Anche perchè di quel 0,1% saranno riferiti a viaggi extra chicago quindi inoltre i Nan dei Geodata sono lo 0,07%

b) Calcoliamo le statistiche

c) I NAN dei GeoData li togliamo la riga. Gli altri li sostituiamo con la mediana/media
  
  **ATTENZIONE** STANDO AL SITO HA SENSO CHE I GEODATA NON ABBIANO VALORI PERCHè SONO
  FUORI CHIACAGO

d) si genera file csv pulito. (spazi con underscore e tutto minuscole)


####2) Finita la pulizia:

a) Nuovo notebook per visualizzazione idee per la visualizzazione + Carman:

**TODO** Compara costi medi tra le varie compagnie di taxi

**TODO** Fare trimming o winsorizing (_scegliere bene!_) delle categorie rimaste da fare

**TODO** Vedi pickup e dropoff a seconda dell'orario (sotto forma di heatmap?)

**TODO** Preferenze di pagamento: gli utenti preferiscono pagare con carta se la cifra è piccola o grande? (contactless?)

**TODO** Vedi effetti lockdown su mobilità, prezzi, entrate compagnie, pickup e dropoff (più viaggi verso gli ospedali?)

**TODO** Vedi effetti del meteo su utilizzo dei taxi (serve però l'altro csv)

**TODO** Media mesi e confronto (grafico diviso per giorni/settimane e spostamenti infrasettimanale (weekend e lavorativo),
orario di punta (6:00-9:00/18:00-21:00)


b)Finita la visualizzazione nuovo notebook per prediction Carman + idee
