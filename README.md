# Assignment #1




Per far funzionare la repository oltre a Git installato sul pc
 https://git-scm.com/downloads
 serve anche l'estensione LFS
 https://git-lfs.github.com/
 
 Better use Pycharm
 
 
 ##ORGANIZZAZIONE

####1) pulire dati:

a) Stando alla docomentazione la durata in secondi non concide con la differenza dei time stamp in quanto sono arrotondati al quarto d'ora

b) Togliamo gli outlier usando il Winsorizing/Trimming però selezioniamo i percentili manualmente in base
    alla forma dei dati
b) Calcoliamo le statistiche

c) I NAN dei GeoData non li togliamo la riga in quanto hanno senso ora che sono stati tolti li outlier
sono comunque possibili i viaggi fuori chicago.

d)si genera file csv pulito. (spazi con underscore)

Il dataset del Tempo sembra pulito, ho sistemato le colonne con nomi umani.

~~**TODO** Fare trimming o winsorizing (_scegliere bene!_) delle categorie rimaste da fare~~

####2)TODO Visualization:

a) Nuovo notebook per visualizzazione idee per la visualizzazione + Carman:

**TODO** Compara costi medi tra le varie compagnie di taxi


**TODO** Vedi pickup e dropoff a seconda dell'orario (sotto forma di heatmap?)

**TODO** Preferenze di pagamento: gli utenti preferiscono pagare con carta se la cifra è piccola o grande? (contactless?)

**TODO** Vedi effetti lockdown su mobilità, prezzi, entrate compagnie, pickup e dropoff (più viaggi verso gli ospedali?)

**TODO** Vedi effetti del meteo su utilizzo dei taxi (serve però l'altro csv)

**TODO** Media mesi e confronto (grafico diviso per giorni/settimane e spostamenti infrasettimanale (weekend e lavorativo),
orario di punta (6:00-9:00/18:00-21:00)

####3)Prediction model
a)Finita la visualizzazione nuovo notebook per prediction Carman + idee
