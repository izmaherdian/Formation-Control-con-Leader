# Formation-Control-con-Leader: Analisi e Implementazione di Sistemi Multi-Agente Basati su Potenziali

Questo repository contiene il notebook **"Formation Control con Leader"**, un'analisi dettagliata e un'implementazione di sistemi multi-agente basati su potenziali. Il notebook guida attraverso la realizzazione di un controllo di formazione per un leader e un gruppo di agenti che mantengono una disposizione circolare intorno al leader.

## Descrizione del Progetto
Il progetto ha come obiettivo la simulazione di un sistema multi-agente in cui:
- Un agente leader si muove verso un obiettivo (goal) seguendo un potenziale attrattivo.
- N agenti si dispongono intorno al leader mantenendo una formazione circolare e rispettando le distanze relative tramite un potenziale di formazione.

### Obiettivi principali
-  **Controllo del leader**: Portare il leader verso un punto goal inizialmente fisso.
-  **Mantenimento della formazione**: Garantire che gli agenti non-leader mantengano la formazione desiderata rispetto al leader.
-  **Robustezza del sistema**: Verificare la stabilità della formazione in presenza di un goal in movimento a velocità costante.
-  **Analisi delle prestazioni**: Determinare la velocità massima del goal che consente di mantenere la formazione.

### Principali Potenziali Utilizzati
- **Potenziale Attrattivo**: Agisce sul leader, portandolo verso il goal.
- **Potenziale di Formazione**: Agisce sugli agenti, costringendoli a mantenere la formazione desiderata rispetto al leader.

## Struttura del Progetto
**Notebook principale**:  
  - Contiene il codice Python e le spiegazioni passo-passo dell'implementazione.
  - Utilizza librerie come `numpy` e `matplotlib` per calcoli numerici e visualizzazione.
**Tuning dei parametri**:  
  - Viene mostrato come ottimizzare i parametri dei potenziali per garantire robustezza e stabilità.

## Informazioni sui risultati
Notare che i grafici nel notebook risultano essere statici, per questo vengono realizzate delle Gif durante l'esecuzione grazie a `matplotlib.animation` che permettono di visualizzare il movimento degli agenti. 

## Contributi
Questo progetto è stato realizzato da **Giovanni Stefanini** come parte di un'analisi sul controllo di formazione multi-agente, per l'esame di Multiagent Systems.
