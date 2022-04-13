## ToDoList

###### drawer = sidebar

###### pagine di errore(400 - 403 - 404) guardare altre repo

<hr>

### visualizzazione client

- [x] :white_check_mark: [sprint 7](./Sprint%207)
- [x] |--- <b>rifinire e allineare stile FormOptional (GLOBAL PARTE1)</b> ---|
- [ ] -----------------------------------------------------------------------
- [x] :white_check_mark: [sprint 8](./Sprint%208)
- [ ] |--- <b>rifinire e allineare stile FormOptional (GLOBAL PARTE2)</b> ---|
- [ ] ***
- [ ]  FORM DESIGN -Email in copia: anche lo spazio da tastiera consente di aggiungere una nuova email appena scritta
- [ ] Email in copia: una riga per campo email, con scroll verticale
- [ ] FORM DESIGN - Per passare da pagina 1 a pagina 2 e viceversa del form di creazione regola inserire in fondo alla pagina form, al centro, l'opzione di cambio schermata tramite dot-scroll
- [ ] mancano i tooltip info sulle checkbox
- [ ] aggiungere i btns funzionali del calendar
- [ ] aggiungere responsive per la form (dopo refactoring css) / dovrebbe essere a posto (rivedere per il calendario)
- [ ] :rotating_light: Nascondere la lista delle folder quando scrollo // ??forse no??
- [ ] :rotating_light: Bloccare prima colonna
- [ ] fixare width tabella (referrer to checkColumns) -> la visibility ha la precedenza quindi si devono vedere le colonne anche se sono empty
editin, il duplicate e il create)
- [ ] Ridisegnare Column Checkbox
- [ ] |--- <b>Tabella SENDERS E RULES (GLOBAL PARTE2)</b> ---|
- [ ] -----------------------------------------------------------------------
- [ ] pagina errore 400
- [ ] pagina errore 403
- [ ] pagina errore 404
- [ ] |--- <b>pagine di errore (GLOBAL)</b> ---|

### funzionalità client

- [x] :white_check_mark: [sprint 7](./Sprint%207)
- [x] |--- <b>validazione (GLOBAL STEP1)</b> ---|
- [ ] ----------------------------------------------------------------------
- [x] :white_check_mark: [sprint 8](./Sprint%208)
- [ ] |--- <b>Form Otpional</b> ---|
- [ ] -----------------------------------------------------------------------
- [ ] LOGOUT DA MAILBOT: manca il btn di logout
- [ ] SENDER LIST:Manca tutta la logica dei toggle - toggle su tutte regole
- [ ] SENDER + RULE_LIST: toggle sulla singola regola
- [x] SENDER_LIST: Aggiungere descrizione sender (chiamata patch)
- [ ] SENDER LIST: Manca il focus alla regola (ad esempio un highlight)
- [ ] SENDER LIST: Necessari i test per lo scroll nelle regole del sender
- [ ] SENDER_LIST: Non stampare i sender se le sue regole sono empty
- [ ] SENDER_LIST+FORMDIALOG_NEW+RULE: Aggiungere il sender nella dialog quando premo il + sul rispettivo
- [ ] RULE_LEVEL: Manca il livello - al momento è un input senza icona di submit (submit all'invio)
- [ ] RULE_LEVEL: Aggiungere la logica del livello quando vado a duplicare una regola
- [ ] FORM_GLOBAL: fixare l'azione required (asterisco) dei fields
- [ ] FORM_EDITING: Controllare la chiamata get "nell'editing"
- [ ] FORM_EDITING: Fixare L'editing non funziona in questo stato: apro new rule vado a pag2 chiudo apro l'editing non ho alcun dato
- [ ] FORM_EDITING: aggiungere asterisco per KEYWORD (solo per l'opzione MUST MATCH), pipe nell'harmless
- [ ] FORM_EDTING_GET: rivedere logica per il reset degli optional (ENUM la lista nella chiamata get) (pag2) da vedere insieme
- [ ] FORM_CREATE: Riportare il form a pag 1 ogni volta che si chiude
- [ ] FORM_CREATE: Validazione campi 
- [ ] FORM_RESET: Aggiungere logica del reset (nell'editing rules) Hide btn in editing
- [ ] CALENDAR_FORM: Calendario multi-selezione al drag
- [ ] CALENDAR_FORM: Collegare il calendario al payload (nome campo + value---> dovrà essere un array di numeri + test)
- [ ] CALENDAR : sviluppo comportamento calendar // parziale
- [ ] REOPEN - (rivedere nel submit vengono considerate come true anche se unchecked) // aggiungere logica autoesclusione checkbox harmless, mailcount, autosuspend,
- [ ] DOWNTIME: Date del downtime test di funzionamento con le varie logiche (create, duplicate)
- [ ] DOWNTIME: Nella lista dei sender attivare l'highlight per il downtime (nel tempo in cui agisce la regola)
- [ ] DOWNTIME: aggiungere logica autoesclusione rispetto al downtime,
- [ ] attivare lo switch della lingua per i test
- [ ] Refactoring ShowConfirm da uniformale alla logica delle dialog
- [ ] |--- <b>chiamate CRUD (GLOBAL)</b> ---|
- [ ] -----------------------------------------------------------------------
- [ ] getione pagine errore
- [ ] |--- <b>gestione pagine errore</b> ---|

### gestione repo necessaria

- [x] :white_check_mark: [sprint 7](./Sprint%207)
- [x] :white_check_mark: [sprint 8](./Sprint%208)
- [ ] riconversione/adattamento del css attuale classi mailbot

<hr>

### chiarimenti necessari

- [x] :white_check_mark: [sprint 7](./Sprint%207)
- [x] :white_check_mark: [sprint 8](./Sprint%208)
- [ ] cosa fa precisamente autosuspend?

<hr>

### ottimizzazioni stile

- [x] :white_check_mark: [sprint 7](./Sprint%207)
- [x] :white_check_mark: [sprint 8](./Sprint%208)
- [ ] fixare trasparenza messaggio di chiusura nella dialog del form
- [ ] nel campo mail in copia, contrassegnare di rosso i 'chips' errati
- [ ] nel campo mail in copia attivare la modifica sul 'chips' errato
- [ ] aggiungere icona tipo lente negli input di ricerca
- [ ] centrare la i dentro icona info

### ottimizzazioni funzionalità

- [ ] migliorare il campo cartellamail (dialogForm) in modo da poter rieseguire una nuova ricerca (es tasto reset field)
- [ ] far vedere se tra le rules c'è almeno un rule con il downtime

<hr>

### non in MVP

- [ ] Landing Page da Fare (ma come?) - priorità 0
