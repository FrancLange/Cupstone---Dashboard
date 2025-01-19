# Dashboard per l'Analisi delle Vendite di un Ecommerce Prestashop

Questo repository contiene un progetto finalizzato alla creazione di una dashboard per l'analisi dei dati di vendita di una piattaforma ecommerce basata su Prestashop. La dashboard fornisce informazioni preziose sulle performance di vendita, sul comportamento dei clienti, sulle prestazioni dei brand e delle categorie, e sulla gestione dell'inventario.

## Panoramica

Abbiamo sviluppato una pipeline per:

1. **Estrarre i dati**:
   - Utilizzato Python per scaricare le tabelle degli ordini dal server che ospita il sito ecommerce.
   - Implementata l'autenticazione API per garantire un accesso sicuro ai dati.

2. **Trasformare i dati**:
   - Processato e pulito i dati grezzi utilizzando Power Query per una visualizzazione ed analisi efficace.

3. **Visualizzare i dati**:
   - Creato una dashboard interattiva in Power BI per visualizzare gli insight ricavati dai dati processati.

## Funzionalità della Dashboard

La versione attuale della dashboard include cinque viste principali:

1. **Vista Generale**:
   - Fornisce un riepilogo delle performance di vendita complessive, dei trend di fatturato e delle metriche principali.

2. **Analisi Clienti**:
   - Si concentra sulla segmentazione dei clienti, sui modelli di acquisto e sull'analisi del comportamento.

3. **Analisi Brand**:
   - Evidenzia le prestazioni dei singoli brand in termini di volume di vendita e contributo al fatturato.

4. **Analisi Categorie**:
   - Esamina le performance di vendita nelle diverse categorie di prodotti.

5. **Analisi dello Stato dell'Inventario**:
   - Monitora i livelli di stock, i prodotti esauriti e il valore dell'inventario.

## Strumenti e Tecnologie Utilizzati

- **Python**:
  - Librerie: `requests`, `json`, `os`
  - Utilizzato per il recupero dei dati tramite API e per automatizzare la raccolta dei dati.

- **Power Query**:
  - Per la trasformazione e preparazione dei dati.

- **Power BI**:
  - Per la creazione di visualizzazioni interattive e report.

## Come Funziona

1. **Estrazione dei Dati**:
   - Lo script Python si connette all'API di Prestashop e scarica i dati degli ordini in file JSON.
   - I dati vengono eventualmente modificati (ad esempio, conversione dei campi di prezzo in formati leggibili).

2. **Preparazione dei Dati**:
   - I dati grezzi vengono importati in Power Query per essere puliti, filtrati e trasformati.

3. **Visualizzazione dei Dati**:
   - I dati processati vengono visualizzati in Power BI con filtri dinamici e report interattivi.

## Miglioramenti Futuri

- **Trasformazione e pulizia dei dati direttamente in Python.**
- **Aggiungere una matrice RFM per segmentare i clienti.**
- **Estendere l'analisi dello stato dei brand con una classificazione per urgenza di riordini.**
- **Integrare dati aggiuntivi provenienti da Google Analytics per analisi avanzate.**
- Aggiungere ulteriori viste alla dashboard, come:
  - Analisi a livello di prodotto.
  - Monitoraggio dei resi e dei rimborsi.
  - Analisi dell'efficacia delle campagne di marketing.

- Implementare l'automazione per aggiornamenti periodici dei dati.

## Come Utilizzare

1. **Clonare questo repository** sulla propria macchina locale.
2. **Configurare l'ambiente** utilizzando i requisiti forniti.
3. **Eseguire lo script Python** per scaricare i dati.
4. **Importare i dati in Power BI** e utilizzare il template predefinito della dashboard.

## Contributi

I contributi sono benvenuti! Sentiti libero di inviare pull request o aprire issue per suggerimenti e miglioramenti.

## Licenza

Questo progetto è distribuito sotto licenza MIT. Consulta il file `LICENSE` per i dettagli.
