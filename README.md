# 🌟 **Formation-Control con Leader** 🌟

## 🔍 **Analisi e Implementazione di Sistemi Multi-Agente Basati su Potenziali**
Questo repository contiene il notebook **"Formation Control con Leader"**, un'analisi dettagliata e un'implementazione di sistemi multi-agente basati su potenziali. Il notebook guida attraverso la realizzazione di un controllo di formazione per un leader e un gruppo di agenti che mantengono una disposizione circolare intorno al leader.

---

## 🛠️ Descrizione del Progetto
Il progetto simula un sistema multi-agente che prevede:
- **🤖 Leader:** Un agente guida che si sposta verso un obiettivo (goal) seguendo un potenziale attrattivo.
- **🌀 Agenti:** Un gruppo di N agenti che mantengono una formazione circolare attorno al leader, grazie a un potenziale di formazione.  

### 🎯 **Obiettivi Principali**
- **🚩 Controllo del leader:** Guidare il leader verso un goal inizialmente fisso.  
- **⚙️ Mantenimento della formazione:** Assicurare che gli agenti non-leader rispettino la disposizione desiderata.  
- **🔒 Robustezza:** Testare la stabilità della formazione anche con un goal in movimento (a velocità costante).  
- **📊 Analisi delle prestazioni:** Calcolare la velocità massima del goal che consente di mantenere la formazione. 

### 🧲 **Principali Potenziali Utilizzati**
- **Potenziale Attrattivo**: Dirige il leader verso il goal.  
- **Potenziale di Formazione**: Forza gli agenti a mantenere la formazione rispetto al leader.  

---

## 📂 Struttura del Progetto
🔸 **Notebook principale:**  
Contiene il codice Python e spiegazioni passo-passo. Utilizza le librerie:  
- 🧮 `numpy` per i calcoli numerici.  
- 📈 `matplotlib` per la visualizzazione.

🔸 **Tuning dei parametri:**  
Viene mostrato come ottimizzare i parametri dei potenziali per garantire robustezza e stabilità.

---

## 🎥 **Informazioni sui Risultati**
Notare che i grafici nel notebook risultano essere statici, per questo vengono realizzate delle Gif durante l'esecuzione grazie a `matplotlib.animation` che permettono di visualizzare il movimento degli agenti. 

---

## 💡 **Contributi**
Questo progetto è stato realizzato da **Giovanni Stefanini** come parte di un'analisi sul controllo di formazione multi-agente, per l'esame di Multiagent Systems.
