## ToDoList
###### drawer = sidebar
###### pagine di errore(400 - 403 - 403) guardare altre repo

<hr>

### visualizzazione client
- [ ] Fixare `rule.name` su Drawer
- [ ] Fixare timer_time timer_unit (time indica il tempo da 1-59 / unit la misura da considerare tra H/m)
- [ ] Fixare harmless_time/autosafe? harmless_unit (time indica il tempo da 1-59 / unit la misura da considerare tra H/m)
- [ ] aggiungere autosuspend
- [ ] Fixare behavior autoclose: se autoclose=true tutti gli altri timer/keyword sono false
- [ ] manca harmless_keyword_start nel FE (e i18n)
- [ ] manca harmless_keyword_stop nel FE (e i18n)
- [ ] manca harmless_mail_count_time nel FE (e i18n)
- [ ] manca harmless_mail_count_unit nel FE (e i18n)
- [ ] rimuovere submit sulla formOptional
- [ ] aggiungere i btns funzionali del calendar
- [ ] |--- <b>rifinire e allineare stile FormOptional (GLOBAL)</b> ---|
- [ ] aggiungere pulsanti actions nella tabella del sender
- [ ] pagina notifica oggetto `senders[] empty`
- [ ] pagina errore 400
- [ ] pagina errore 403
- [ ] pagina errore 404
- [ ] |--- <b>pagine di errore (GLOBAL)</b> ---|

### funzionalità client
- [ ] rimuovere submit sulla formOptional 
- [ ] :rotating_light: rivedere apertura sender su dev
- [ ] fixare comportamento delle validazioni allo switch form
- [ ] fixare comportamento della dialog per chiudere il form (show is not defined)
- [ ] conservare dati durante lo switch della form (state mgm)
- [ ] Validazione match regex campo servizio/service
- [ ] Validazione match regex campo coda/queue
- [ ] Validazione match regex campo campiDinamici/DynamicField
- [ ] Validazione match regex campo sla
- [ ] eliminare una singola regola
- [ ] eliminare sender e tutte le sue regole
- [ ] |--- <b>validazione (GLOBAL)</b> ---|
- [ ] |--- <b>Gestione comportamento calendar</b> ---|
- [ ] |--- <b>gestione pagine errore</b> ---|
- [ ] keycloak lo dobbiamo prevedere?

### gestione repo necessaria
- [ ] aggiunta di sass
- [ ] riconversione/adattamento del css attuale

<hr>

### chiarimenti necessari
- [x] le unità di misura di tempo con una lettera o due? // due
- [ ] cosa fa precisamente autosafe
- [ ] gli harmless_time sono gli autosafe_time?
- [ ] cosa fa precisamente autosuspend?
- [ ] se c'è attivo un timer gli altri sono disattivati?
- [ ] a quale timer sono collegate le harmless_keyword o sono dei timer a sè?
- [x] mailcount - quali mail conteggia? //conteggia e blocca le mail che hanno come ref lo stesso ticket


<hr>

### ottimizzazioni stile
- [ ] fixare trasparenza messaggio di chiusura nella dialog del form
- [ ] ottimizzare pulsanti di navigazione slider form
- [ ] aggiungere icona tipo lente negli input di ricerca
- [ ] centrare la i dentro icona info
### ottimizzazioni funzionalità

<hr>

### non in MVP
- [ ] Landing Page da Fare (ma come?) - priorità 0