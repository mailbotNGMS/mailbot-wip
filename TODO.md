## ToDoList

###### drawer = sidebar

###### pagine di errore(400 - 403 - 404) guardare altre repo

<hr>

### visualizzazione client

- [x] :white_check_mark: [sprint 7](./Sprint%207)
- [x] |--- <b>rifinire e allineare stile FormOptional (GLOBAL PARTE1)</b> ---|
- [ ] -------------------------------------------------------------------------
- [ ] ridisegnare form per UX
- [ ] ridisegnare/ re-layout della formOptional
- [ ] aggiungere responsive per la form (dopo refactoring css)
- [ ] Ridisegnare Colomun Checkbox
- [ ] rivedere la logica tutti i BTN info (alcuni non funzionano) / da completare
- [ ] aggiungere i btns funzionali del calendar
- [ ] aggiungere checkbox del downtime ES: Abiltato[true,false] - Date_start: 23/03 Time Start: 12:54 Date_End: 24/03 Time End: 12:54 (enable, start_date, start_end, time, unit) ... / calendario() -> restituisce timestamp?
- [x] Aggiungere info ai campi del formOptional (risolvere problema con il CSS)
- [x] :rotating_light: verificare perchè se clicco su number parte il submit
- [x] mancano delle chiavi
- [x] rivedere la logica per il tooltip del mailcount system (cambiare model di ref)
- [ ] |--- <b>rifinire e allineare stile FormOptional (GLOBAL PARTE2)</b> ---|
- [ ] -------------------------------------------------------------------------
- [ ] aggiungere pulsanti actions nella tabella del sender
- [ ] aggiungere expansion sulla singola regola con layout (che non c'è / da)
- [ ] fixare width tabella (referrer to checkColumns) -> la visibility ha la precedenza quindi si devono vedere le colonne anche se sono empty
- [ ] pagina notifica quando l'oggetto `senders[] empty`
- [ ] |--- <b>Tabella SENDERS E RULES (GLOBAL PARTE2)</b> ---|
- [ ] -------------------------------------------------------------------------
- [ ] pagina errore 400
- [ ] pagina errore 403
- [ ] pagina errore 404
- [ ] |--- <b>pagine di errore (GLOBAL)</b> ---|

### funzionalità client

- [x] :white_check_mark: [sprint 7](./Sprint%207)
- [x] |--- <b>validazione (GLOBAL STEP1)</b> ---|
- [ ] -----------------------------------------------------------
- [ ] REOPEN - (rivedere nel submit vengono considerate come true anche se unchecked) // aggiungere logica autoesclusione checkbox harmless, mailcount, autosuspend,
- [ ] aggiungere logica autoesclusione rispetto al downtime,
- [ ] rivedere logica per il reset degli optional (ENUM) (pag2)
- [ ] fixare l'azione required (asterisco) dei fields
- [ ] Non stampare i sender se le sue regole sono empty
- [ ] fixare comportamento dei q-input number
- [ ] sviluppo comportamento calendar
- [ ] attivare lo switch della lingua per i test
- [x] Refactoring - unificati nomi dei campi con ENUM-field
- [x] sender dei nuovi field (PUSH in PAYLOAD)
- [x] fixare i valori dei filtri (VALUE of field select)
- [x] fixare i submit della form
- [ ] |--- <b>validazione (GLOBAL STEP2)</b> ---|
- [ ] -----------------------------------------------------------
- [ ] Aggiungere il sender nella dialog quando premo il + sul rispettivo
- [ ] Aggiungere logica del reset (editing rules)
- [ ] Aggiungere logica della delete tabella (delete rules) //DELETE
- [ ] Aggiungere logica dell'editing (editing rules) //PATCH
- [ ] Aggiungere logica del clone sulla rules (clone rules) //CLONE
- [ ] |--- <b>Logica Tabella (GLOBAL STEP2)</b> ---|
- [ ] -----------------------------------------------------------
- [ ] chiamate edit sender
- [ ] chiamate delete sender (e delete rules)
- [ ] |--- <b>chiamate CRUD (GLOBAL)</b> ---|
- [ ] -----------------------------------------------------------
- [ ] getione pagine errore
- [ ] |--- <b>gestione pagine errore</b> ---|
- [ ] implementare keycloak

### gestione repo necessaria

- [x] :white_check_mark: [sprint 7](./Sprint%207)
- [ ] riconversione/adattamento del css attuale classi mailbot

<hr>

### chiarimenti necessari

- [x] :white_check_mark: [sprint 7](./Sprint%207)
- [ ] cosa fa precisamente autosuspend?

<hr>

### ottimizzazioni stile

- [x] :white_check_mark: [sprint 7](./Sprint%207)
- [ ] fixare trasparenza messaggio di chiusura nella dialog del form
- [ ] nel campo mail in copia, contrassegnare di rosso i 'chips' errati
- [ ] nel campo mail in copia attivare la modifica sul 'chips' errato
- [ ] aggiungere icona tipo lente negli input di ricerca
- [ ] centrare la i dentro icona info

### ottimizzazioni funzionalità
- [ ] migliorare il campo cartellamail (dialogForm) in modo da poter rieseguire una nuova ricerca (es tasto reset field)

<hr>

### non in MVP

- [ ] Landing Page da Fare (ma come?) - priorità 0
