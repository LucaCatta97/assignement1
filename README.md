# assignement1




Per far funzionare la repository oltre a Git installato sul pc
 https://git-scm.com/downloads
 serve anche l'estensione LFS
 https://git-lfs.github.com/
 
 Better use Pycharm
 
 
 %% md

##### 1) Pulizia dati:

a) Togliamo gli outlier usanado il Winsorizing però selezioniamo i percentili manualmente in base
    alla forma dei dati
    
    TODO Considera outliers in base alla loro ragionevolezza...
    Carman suggerisce: "How fast can a taxi travel?"
    TODO Quali relazioni ci sono tra le variabili? Lineari, quadratiche, più complicate?

b) Calcoliamo le statistiche

c) Se ci sono NAN nei GeoData togliamo la riga. Gli altri li sostituiamo con la mediana/media.

d) Si genera file .csv pulito (spazi con underscore e tutto minuscole)

#####2) Finita la pulizia:

a) Nuovo notebook per visualizzazione idee per la visualizzazione + richieste Carman: 

    TODO Compara costi medi tra le varie compagnie di taxi
    TODO Vedi pickup e dropoff a seconda dell'orario (con heatmap?)
    TODO Preferenze di pagamento: gli utenti preferiscono pagare con carta se la cifra è piccola o grande? (contactless?)
    TODO Vedi effetti lockdown su mobilità, prezzi, entrate compagnie, pickup e dropoff (es. più viaggi verso ospedali?)
    TODO Vedi effetti del meteo su utilizzo dei taxi
    TODO Media mesi e confronto (grafico diviso per giorni/settimane e spostamenti infrasettimanale (weekend e lavorativo)
         orario di punta (6:00-9:00/18:00-21:00)

b) Finita la visualizzazione nuovo notebook per prediction Carman + idee
