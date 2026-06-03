# FinTech Calculator App (Android)

Un'applicazione Android nativa sviluppata in Kotlin progettata per supportare i retail investor nella gestione e nel calcolo dei rendimenti finanziari, ottimizzata per il regime amministrato italiano.

## 🚀 Funzionalità Principali

* **Calcolo Capital Gain Realizzato:** Computazione del guadagno lordo e netto basato su prezzo di acquisto, vendita e quantità, integrando automaticamente la tassazione italiana al 26%.
* **Integrazione Commissioni e Oneri:** Calcolo automatico della Tobin Tax e delle commissioni bancarie (configurato sul profilo Directa) basato sul numero di eseguiti.
* **Calcolo Dividendi Netti:** Gestione dei dividendi con decurtazione della ritenuta alla fonte (26%).
* **Persistenza del Capitale:** Gestione e aggiornamento dinamico del capitale iniziale dell'utente tramite database locale, con opzione per capitalizzare i guadagni o i dividendi approvati.
* **Calcolo Quantità:** Strumento integrato per determinare quante azioni è possibile acquistare in base a un determinato budget e al prezzo corrente del titolo.

## 🛠️ Stack Tecnico

* **Linguaggio:** Kotlin
* **Database Locale:** SQLite (`SQLiteOpenHelper`) per una gestione persistente dei dati finanziari dell'utente.
* **Interfaccia Utente:** Layout flessibili e reattivi realizzati tramite `ConstraintLayout` e `ScrollView` per garantire un'ottima usabilità[cite: 7].
* **Pattern & UX:** Validazione degli input in tempo reale e gestione dei dialoghi di conferma per prevenire errori operativi o crash.

---
*Progetto personale in fase di sviluppo (Work in Progress).*
