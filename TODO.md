## ToDoList

###### drawer = sidebar

###### pagine di errore(400 - 403 - 404) guardare altre repo

<hr>

### visualizzazione client

- [x] Fixare `rule.name` su Drawer
- [x] Fixare timer_time timer_unit (time indica il tempo da 1-59 / unit la misura da considerare tra H/m)
- [x] Fixare harmless_time/autosafe? harmless_unit (time indica il tempo da 1-59 / unit la misura da considerare tra H/m)
- [x] Aggiungere info il campo copia mail
- [x] aggiungere autosuspend
- [x] Fixare behavior autoclose: se autoclose=true tutti gli altri timer/keyword sono false
- [x] Fixare label per le time unit
- [x] manca harmless_keyword_start nel FE (e i18n)
- [x] manca harmless_keyword_stop nel FE (e i18n)
- [x] manca harmless_mail_count_time nel FE (e i18n)
- [x] manca harmless_mail_count_unit nel FE (e i18n)
- [x] manca harmless_mail_count_number nel FE (e i18n)
- [x] schiarire i disabled (opacity/colore)
- [x] rimuovere submit sulla formOptional
- [x] |--- <b>rifinire e allineare stile FormOptional (GLOBAL PARTE2)</b> ---|
  [ ] -------------------------------------------------------------------------
- [ ] ridisegnare/ re-layout della formOptional
- [ ] aggiungere responsive per la form (dopo refactroing css)
- [ ] aggiungere un highlight per far capire quali sono le opzioni disponibili dopo un certo check
- [ ] aggiungere i btns funzionali del calendar
- [ ] Aggiungere info ai campi del formOptional (risolvere problema)
- [ ] |--- <b>rifinire e allineare stile FormOptional (GLOBAL PARTE2)</b> ---|
  [ ] -------------------------------------------------------------------------
- [ ] aggiungere pulsanti actions nella tabella del sender
- [ ] fixare width tabella (referrer to checkColumns) -> la visibility ha la precedenza quindi si devono vedere le colonne anche se sono empty
- [ ] aggiungere downtime (enable, start_date, start_end, time, unit) ... / calendario() -> restituisce timestamp?
- [ ] pagina notifica quando l'oggetto `senders[] empty`
- [ ] pagina errore 400
- [ ] pagina errore 403
- [ ] pagina errore 404
- [ ] |--- <b>pagine di errore (GLOBAL)</b> ---|

### funzionalità client

- [x] :rotating_light: fix build (semgrep)
- [x] :rotating_light: rivedere apertura sender su dev ( selectd is not defined)
- [x] verificare perchè una volta creato il sender si apre a volte si a volte no.
- [x] fixare comportamento della dialog per chiudere il form (show is not defined)
- [x] fixare il campo mail in copia (keystroke e spazi-> vd trim) //no keystroke per ora
- [x] rimuovere submit sulla formOptional (pag1)
- [ ] accordare il reset allo step corrente
- [x] fixare comportamento delle validazioni allo switch form
- [x] conservare dati durante lo switch della form (state mgm)
- [ ] Validazione match regex campo servizio/service
- [ ] Validazione match regex campo coda/queue
- [ ] Validazione match regex campo campiDinamici/DynamicField
- [ ] Validazione match regex campo sla
- [ ] |--- <b>validazione (GLOBAL)</b> ---|
- [ ] -----------------------------------------------------------
- [ ] sviluppo comportamento calendar
- [ ] |--- <b>validazione (GLOBAL STEP2)</b> ---|
- [ ] -----------------------------------------------------------
- [ ] pagine di errore
- [ ] |--- <b>gestione pagine errore</b> ---|
- [ ] -----------------------------------------------------------
- [ ] chiamate edit sender
- [ ] chiamate delete sender (e delete rules)
- [ ] chiamate edit rule
- [ ] chiamate delete rule (singola)
- [ ] |--- <b>chiamate CRUD (GLOBAL)</b> ---|
- [ ] implementare keycloak

### gestione repo necessaria

- [x] aggiunta di ~sass~ usiamo postcss
- [x] riconversione/adattamento del css attuale classi quasar
- [ ] riconversione/adattamento del css attuale classi mailbot

<hr>

### chiarimenti necessari

- [x] le unità di misura di tempo con una lettera o due? // due
- [x] cosa fa precisamente autosafe //autosafe è l'harmless unit
- [x] gli harmless_time sono gli autosafe_time? // si
- [ ] cosa fa precisamente autosuspend?
- [ ] se c'è attivo un timer gli altri sono disattivati?
- [x] a quale timer sono collegate le harmless_keyword o sono dei timer a sè? //sono collegate agli harmless unit
- [x] mailcount - quali mail conteggia? //conteggia e blocca le mail che hanno come ref lo stesso ticket

<hr>

### ottimizzazioni stile

- [ ] fixare trasparenza messaggio di chiusura nella dialog del form
- [ ] nel campo mail in copia, contrassegnare di rosso i 'chips' errati
- [ ] nel campo mail in copia attivare la modifica sul 'chips' errato
- [x] ottimizzare pulsanti di navigazione slider form
- [ ] aggiungere icona tipo lente negli input di ricerca
- [ ] centrare la i dentro icona info

### ottimizzazioni funzionalità
- [ ] migliorare il campo cartellamail (dialogForm) in modo da poter rieseguire una nuova ricerca (es tasto reset field)

<hr>

### non in MVP

- [ ] Landing Page da Fare (ma come?) - priorità 0
