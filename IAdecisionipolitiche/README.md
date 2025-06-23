# Decisioni politiche con l'IA, un'applicazione tra chimica, fisica e matematica.

**Tema:**  Qualità dell’aria e intelligenza artificiale

**Scopo:** Gli alunni e le alunne appartengono a un team di ricerca finanziato dall'amministrazione locale. Il loro obiettivo è trovare la miglior strategia per gestire i blocchi del traffico. In questo momento si guarda il superamento della soglia.

Riusciamo a trovare qualcosa di più raffinato che preveda quando bloccare il traffico? 

## Plannning

|  | Tempo | Descrizione | Docenti coinvolti |
| :---- | :---- | :---- | :---- |
| Introduzione  qualità aria | 1h | Finalizzata all’analisi dei dati | Prof Fisica e Scienze  |
| Introduzione ML/AI | 2h | Modello che può essere applicato e qualche metrica Panoramica sui modelli con distinzione tra supervisionati e non supervisionati | Prof Informatica |
| Analisi dei dati | 2 h | Quali informazioni abbiamo Data exploration |  |
| Modello e applicazione pratica del modello | 3 h | Scelta delle variabili in base al modello Come aggiungere una variabile a livello di codice. |  |
| Valutazione Discussione  | 1h |  |  |

## Materiale 
 ``` 
└── IAdecisionipolitiche/
   ├── notebook/
   ├── data/
 ``` 
Nella cartella data sono presenti i file per scaricare e elaborare i dati dai siti di APPA e delle stazioni meteo.
Nella cartella notebook i file utilizzati in classe con gli studente e i file completi per il docente.

## Metodologia


Dopo un’introduzione sulla qualità dell’aria e sull’IA, viene fornito agli studenti un Notebook Colab per poter applicare un modello di ML ai dati reali precedentemente analizzati. 


La lezione risulta così strutturata:

1. Discussione - brainstorming
 
    Riusciamo a trovare qualcosa di più raffinato che preveda quando bloccare il traffico?     
    
2. Presentazione dati
    
    * Dato grezzo.  
    * Visualizzazione per stazione (facciamo noi) e visualizzazione per inquinante (da fare loro)  
    * Visualizzazione per un periodo di tempo.  
    * Calcolare medie, massimi e minimi settimanali e mensili  
    * Filtrare i massimi e vedere in che periodo sono
    
    Produrre delle osservazioni sui grafici che hanno fatto. Modulo Google per raccolta.

3. Presentiamo il modello che si basa sul giorno prima \- Naive   (2 ore)
    Questo notebook è già preparato, è un tutorial
    Prendiamo il dato training, test, validazione . Come costruire un semplice modello di ML concentrandoci solo una variabile (PM10 ad esempio)

4. Costruiamo un modello.
   L'obiettivo è capire come sia importante allenarsi sul passato per imparare il futuro.   
   Su questo modello calcoliamo le diverse metriche  e osserviamo il grafico con le predizione

5. Modello con tutte le features** (2 ore)
    Dataframe con le colonne a scelta, metriche, grafici e osservazioni. Ogni gruppo tiene traccia delle sue scelte
    Viene lasciato tempo per riflettere su quali opendata o no potresti utilizzare per migliorare il modello? 


