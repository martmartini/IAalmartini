**UDA STEM COMPRENDERE ML**  
**Tema:** Algoritmi di IA, il machine learning ML e l’apprendimento con supervisione 

**Classe:** 3AFMC \- 3AFMB (Replicata a fine anno in 3LOSA \-Prof.ssa Tonoli)

**Scopo:** Comprendere gli algoritmi di ML dal punto di vista teorico e applicare tali modelli a casi concreti (Dataset Spotify). Usiamo una classificazione, il risultato potrebbe essere usato per creare un sistema di raccomandazioni. 

**Attività:**

|  | Tempo | Descrizione | Docenti coinvolti |
| :---- | :---- | :---- | :---- |
| Introduzione all’IA con focus su ML e apprendimento supervisionato | 2 ore | Presentazione generale (1ora)  Applicazione con teachable machine: vengono utilizzate le immagini preparate in precedenza dagli studenti per allenare un modello di ML (1 ora)   | Prof informatica |
| Introduzione all’IA con focus su ML e apprendimento supervisionato | 2 ore | Applicazione con teachable machine: predizione con i due diversi dataset (1 ora) Presentazione sui modelli di ML e applicazione, train e test (1 ora) | Prof informatica |
| Il modello k-NN teoria e pratica | 2 ore | Esercizio  sul metodo k-NN e calcolo della distanza (1ora) Notebook, scelta delle features e applicazione del modello su dataset reale (1 ora) | Prof Matematica/Fisica e Prof Informatica |
| Il modello k-NN teoria e pratica | 2 ore | Esercizio su definizione di confusion matrix e accuratezza  Notebook, determinazione della confusion matrix e accuratezza Esercizio variazione k con cambio di previsione Notebook, scatter plot distanze e ragioniamo sul nostro dataset al variare di k | Prof Matematica/Fisica e Prof Informatica  |
| Valutazione | 2 ore | Applicazione k-NN a nuovo dataset |  |

**Planning**

|  | Tempo | 
| :---- | :---- | :---- | :---- |
| Introduzione all’IA con focus su ML e apprendimento supervisionato | 2 ore | 
| Introduzione all’IA con focus su ML e apprendimento supervisionato | 2 ore | 
| Il modello k-NN teoria e pratica | 2 ore | 
| Il modello k-NN teoria e pratica | 2 ore | 
| Valutazione | 2 ore | 

**Metodologia:**

Si alternamento parti di lezione più teoriche ad applicazioni.

* **Introduzione IA** (4 ore)  
  1 dataset per teachable machine  
  Prima dell’inizio dell’UdA si forniscono agli studenti dei cartoncini di due colori **A** e **B**. Sul cartoncino di colore A ognuno deve scrivere il numero **1** con un pennarello di colore **rosso** mentre sul B il **2** con un pennarello di colore **blu.**  
  Il docente crea un dataset per la predizione in modo anche da “ingannare l’algoritmo” incrociando i colori (2 rosso sul cartoncino A, 1 blu su cartoncino B)  
  2 dataset per teachable machine  
  Si chiede agli studenti di rappresentare il numero 1 e due su sfondi diversi, con grafie e colori diverse  
    
  Entrambi i dataset vengono usati per allenare due diversi modelli di teachable machine e valutare l’importanza del dato  
    
  Questa attività pratica viene inserita dopo la presentazione generale su IA e prima di parlare nello specifico di ML e apprendimento supervisionato e introduzione a k-NN.  
    
    
* **Il modello k-NN** (4 ore)

	Gli esercizi vengono svolti a coppie  
	1 esercizio (carta e penna)  
Rappresentazione nel piano cartesiano dei punti da classificare e calcolo della distanza. Ordinamento e classificazione

Notebook   
Dataset spotify. Iniziamo dalle features e le visualizziamo Le facciamo osservare e ogni coppia decide quelle più rilevanti, solo 2 features. Train, test, dividere in ordine intelligente mostrando la tabella di x\_test. Modello con k, provate con quello di default.

2 esercizio (carta e penna)  
Confusion matrix su caso simil reale da calcolare e accuratezza a mano  
Accuratezza quante canzoni vengono classificate correttamente sul totale

\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_

Notebook   
Calcolo accuratezza   
Confusion matrix con valori assoluti

3 esercizio (carta e penna)  
Si riprende il primo esercizio e di fa variare k in modo che cambi la previsione

Notebook  
Plot caso particolare; Energy e danceability, canzone 200 (vicino arancione ma classe blu) provare con k=3 e k=5  
Si chiede agli studenti di far variare k e osservare come varia la confusion matrix e l’accuratezza  
   
   
**Ulteriori approfondimenti su notebook**

Plot distanza e vediamo il caso particolare (loudness, tempo)

(Togliamo:Se non viene fuori da nessuno,  facciamo vedere loudness e danceability, plot distanze, osservare che non hanno la stessa scale: questione della visualizzazione con due scale diverse e questione del fatto che il modello nel calcolo della distanza è come se desse un peso maggiore ad una delle due features.)

Aggiunta features

RandomForest
