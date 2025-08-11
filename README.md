# Annalisa Ori   

## Introduzione  
Sono Annalisa Ori, ho 23 anni e fin da piccola sono sempre stata affascinata dai numeri e da come la realtà può essere spiegata attraverso essi. 

Per questo mio interesse, ho conseguito una laurea triennale in Matematica e ora sto frequentando la laurea magistrale in Scienze Statistiche ed Economiche. 
Il mio percorso di studi mi ha permesso di sviluppare una solida comprensione delle teorie fondamentali e anche delle loro applicazioni pratiche. Ho imparato a lavorare con modelli matematici, analisi dei dati e metodi statistici avanzati, che mi hanno permesso di acquisire un'abilità nel riconoscere schemi e fare previsioni basate su dati numerici. La matematica non è solo una passione, ma un linguaggio attraverso il quale esploro e comprendo il mondo che ci circonda.

Sono sempre alla ricerca di opportunità per espandere le mie conoscenze e competenze analitiche.
In questo canale condivido i miei progetti personali realizzati durante gli anni dei miei studi. 



## Indice  
- [Introduzione](#Introduzione) 
- [Progetti](#Progetti)  
- [Educazione](#Educazione)  
- [Certificazioni](#Certificazioni)
- [Contatti](#Contatti)

---

## Progetti  


###  Tesi triennale: Dinamica di modelli di predazione e competizione

**Descrizione:** Ho modellizzato la dinamica di tre popolazioni tramite sistemi di equazioni differenziali ordinarie, ne ho studiato l'evoluzione mediante strumenti matematici 
utili per lo studio qualitativo di modelli differenziali e ne ho rappresentato i risultati ottenuti mediante simulazioni numeriche Matlab.

**File pdf:** [Tesi triennale](https://github.com/AnnalisaOri/Progetti/blob/main/Tesi%20triennale)

**Codice latex:** [latex](https://github.com/AnnalisaOri/Progetti/blob/main/latex.tex)

**Alcuni codici Matlab per la realizzazione dei grafici:** 

[Figura 2.28](https://github.com/AnnalisaOri/Progetti/blob/main/Figura2-28.m)

[Simulazione numerica 1 con piano di fase 3D per l'equilibrio E2](https://github.com/AnnalisaOri/Progetti/blob/main/sim1_E2stabile.asv)

[Piano di fase 2d per sottosistema y-z](https://github.com/AnnalisaOri/Progetti/blob/main/piano_yz_specialista.m)


### MODELLO SIRS

**Descrizione:** La diffusione di alcune pandemie, come quella del COVID-19, può essere, sotto ovvie ipotesi semplificative, modellizzata attraverso una variante del classico modello SIR. A differenza di quest'ultimo, il modello SIRS considera la possibilità che gli individui perdano l’immunità nel tempo e possano tornare suscettibili all’infezione.
Grazie alla teoria della stabilità dei sistemi dinamici, ho potuto studiare l'evoluzione nel tempo del sistema in esame.

**File pdf:** [Sirs](https://github.com/AnnalisaOri/Progetti/blob/main/SIRS.pdf)

**Alcuni codici Matlab per la realizzazione dei grafici:** 

[Simulazione numerica](https://github.com/AnnalisaOri/Progetti/blob/main/Simulazione_2%5C3D.m)

[Ritratto di fase 1](https://github.com/AnnalisaOri/Progetti/blob/main/ritrattodifase1.m)




### Analisi di una serie storica: ANDAMENTO DEL TRAFFICO STRADALE IN MINNESOTA

**Descrizione:** L’obiettivo di questo elaborato è analizzare il traffico stradale in Minnesota, USA, in relazione a vari fattori come condizioni meteo, temperatura e giorni festivi/weekend. Inizialmente, ho condotto un'analisi esplorativa delle serie storiche, verificando la normalità, la stazionarietà e la presenza di trend e stagionalità. Successivamente, ho sviluppato diversi modelli, tra cui regressione lineare semplice, ARIMA, SARIMA e regARIMA. Infine, ho selezionato il modello migliore e l'ho utilizzato per prevedere l’andamento del traffico.

**Dataset:** [Dati](https://github.com/AnnalisaOri/Progetti/blob/main/Metro_Interstate_Traffic_Volume.csv)

**Codice R e analisi:** [Quart document](https://github.com/AnnalisaOri/Progetti/blob/main/Analisi%20di%20una%20serie%20storica%20.pdf)

**Funzioni aggiuntive:** [Arch Test](https://github.com/AnnalisaOri/Progetti/blob/main/FN%20-%20ARCHTest.txt)
[PortmanteauQ test](https://github.com/AnnalisaOri/Progetti/blob/main/FN%20-%20AutoPortmanteauQ.txt)
[Sarima](https://github.com/AnnalisaOri/Progetti/blob/main/FN%20-%20PerfMetr_SARIMA.txt)
[Sequence of dates](https://github.com/AnnalisaOri/Progetti/blob/main/FN%20-%20Sequence%20of%20dates.txt)
[Custom aggregate](https://github.com/AnnalisaOri/Progetti/blob/main/FN%20-%20TS_custom_aggregate.txt)


### Analisi di modelli in forma State Space, filtro e smoother di Kalman
**Descrizione:** Analisi e stima di modelli state space applicati alla serie storica delle portate annuali del Nilo, usando il pacchetto R KFAS. Include stima tramite massima verosimiglianza, filtraggio e smoothing con Kalman, e analisi di cambiamenti strutturali tramite variabili scalino.

**Codice R e analisi:** [Quart document, pdf](https://github.com/AnnalisaOri/Progetti/blob/main/Analisi%20di%20modelli%20State%20Space%20con%20KFAS.pdf)




### Progetto Excel - Economia delle Assicurazioni

**Descrizione:** Il file Excel è organizzato per seguire i diversi temi del corso:
1. **Assicurazioni Danni**  
   - **Stima della riserva sinistri – Metodo della Catena (Chain-Ladder)**: a partire da un triangolo di Run-Off dei sinistri pagati, vengono stimati i fattori di sviluppo e completato il triangolo per determinare la riserva sinistri necessaria.  
   - **Metodo della separazione**: la riserva viene ricalcolata separando la frequenza (numero di sinistri) dalla severità (importo medio), fornendo una valutazione più dettagliata.  
   - **Conto tecnico ramo danni**: partendo dai dati di bilancio (premi, riserve, sinistri pagati, spese) vengono calcolate le grandezze tecniche mancanti (premi e sinistri di competenza, riserve finali, loss ratio, expense ratio, combined ratio).  

2. **Assicurazioni Vita**  
   - **Unit Linked**: calcolo dei caricamenti sul premio, suddivisione nei diversi fondi, e determinazione del valore minimo della quota di un fondo affinché il capitale pagabile in caso di sinistro sia superiore alla garanzia minima.  
   - **Assicurazione mista rivalutabile**: calcolo del premio puro annuo (con evidenza delle componenti di rischio e risparmio), delle riserve matematiche, della rivalutazione del capitale assicurato (sia con premio costante che rivalutabile) in base ai rendimenti della gestione separata.  
   - **Rivalutazione Cliquet e Best Of**: confronto tra i due meccanismi di rivalutazione del capitale assicurato in presenza di un tasso minimo garantito e di rendimenti variabili.  

**File Excel:**  [File Excel](https://github.com/AnnalisaOri/Progetti/blob/main/assicurazioni.xlsx)

---

## Educazione
- Diploma presso Liceo Scientifico Giacomo Ulivi, Parma; 2015-2020; con votazione 100/100 con lode
- Laurea Triennale in Matematica (L35) presso Università degli Studi di Parma; 09.2020-03.2024; con votazione 105/110
- Laurea Magistrale in Scienze Statistiche ed Economiche (curriculum: mercati assicurativi e finanziari, LM82), presso Università degli Studi di Milano Bicocca; in corso

---
## Certificazioni
---

## Contatti
- LinkedIn: [@AnnalisaOri](https://www.linkedin.com/in/annalisa-ori-92b436292)
- Email: anni.ori@hotmail.it


