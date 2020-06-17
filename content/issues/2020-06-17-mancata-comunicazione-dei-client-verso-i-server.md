---
section: issue
title: Mancata comunicazione dei server verso i client
date: 2020-06-17T09:01:30.270Z
resolved: true
informational: false
resolvedWhen: 2020-06-17T09:34:56.390Z
affected:
  - webclient
  - pcp
  - yapds
  - wsnet
  - stampe
  - ced
severity: disrupted
---
*Risolto* - Confermata la piena risoluzione del problema. {{< track "2020-06-17 11:30:00" >}}

*Monitoraggio in corso* - I servizi stanno funzionando parzialmente. Non dovrebbero esserci problemi evidenti dal punto di vista funzionale grazie ai sistemi ridondanti e di backup. {{< track "2020-06-17 11:25:00" >}}

*Mitigazione* - E' stata incrementata la capacità computazionale del sistema che ha sofferto di un carico eccessivo. {{< track "2020-06-17 11:20:00" >}}

*Monitoraggio in corso* - Ci sono ancora problemi, anche nell'interrogazione dei servizi esterni come DMC, CED e DMZ. {{< track "2020-06-17 11:11:00" >}}

*Monitoraggio in corso* - Il problema è rientrato, permangono alcuni rallentamenti che si andranno a risolvere nei prossimi minuti. {{< track "2020-06-17 11:05:00" >}}

*Indagine in corso* - C'è un malfunzionamento che impedisce all'agenda di ricevere aggiornamenti, che impedisce ai client YAP di ricevere le notifiche. Altri comparti che potrebbero avere malfunzionamenti sono le situazioni di magazzino e le comunicazioni con i software desktop esterni. {{< track "2020-06-17 11:00:00" >}}