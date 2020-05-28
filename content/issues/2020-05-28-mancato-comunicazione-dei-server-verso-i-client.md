---
section: issue
title: Mancata comunicazione dei server verso i client
date: 2020-05-28T13:13:40.333Z
resolved: true
informational: false
resolvedWhen: 2020-05-28T13:39:24.388Z
affected:
  - webclient
  - pcp
  - yapds
  - wsnet
  - stampe
  - ced
severity: disrupted
---
*Postmortem*

All'incirca alle 15:10, il sistema di monitoraggio di Google ha rilevato dei problemi su 2 server di un cluster di 3 facendo partire una procedura di ripristino che consiste nel distruggere ed eliminare i server non funzionanti per ricrearne di nuovi.

Alcuni servizi ospitati sul cluster sono realizzati per poter funzionare correttamente solo in presenza di almeno 2 server e questo ha creato un malfunzionamento su alcuni componenti.

Tutta la gestione dell'anomalia è stata completamente automatizzata ed anche se ha causato alcuni malfunzionamenti per alcuni minuti non ha richiesto alcun intervento manuale. 

---

*Risolto* - Confermata la piena risoluzione del problema. Seguirà una piena analisi delle cause. {{< track "2020-05-28 15:39:00" >}}

*Monitoraggio in corso* - Il problema è rientrato ed i servizi sono tutti operativi. Ci sono alcune code che devono essere svuotate e che quindi possono provocare anche qualche lentezza. {{< track "2020-05-28 15:32:00" >}}

*Monitoraggio in corso* - Il servizio CED dovrebbe essere nuovamente funzionante, gli altri servizi sono ancora non disponibili. {{< track "2020-05-28 15:20:00" >}}

*Indagine in corso* - C'è un malfunzionamento che impedisce all'agenda di ricevere aggiornamenti, che impedisce ai client YAP di ricevere le notifiche. Altri comparti che potrebbero avere malfunzionamenti sono le situazioni di magazzino. {{< track "2020-05-28 15:13:00" >}}