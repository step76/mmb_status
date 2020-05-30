---
section: issue
title: YAP è in over quota
date: 2020-05-30T05:10:00.000Z
resolved: true
informational: false
resolvedWhen: 2020-05-30T07:22:22.969Z
affected:
  - webclient
  - api-export
  - api-int
severity: down
---
*Risolto* - I servizi sono regolari. {{< track "2020-05-30 09:20:00" >}}

*Monitoraggio in corso* - I servizi sono ripartiti, ma ci sono ancora errori e rallentamenti dovuti al picco di traffico e al fatto che tutte le risorse devono ripartire.\
Occorrono ancora alcuni minuti affinché la situazione si stabilizzi.\
{{< track "2020-05-30 09:00:00" >}}

*Monitoraggio in corso* - Lo YAP è completamente offline a causa di una procedura che ha completamente esaurito tutto il budget giornaliero predisposto.\
Il budget è giornaliero e viene azzerato ogni giorno, il momento dell'azzeramento corrisponde alle 0:00 della costa ovest degli Stati Uniti e corrisponde alle 9:00 ora italiana, pertanto alle 9:00 lo YAP tornerà pienamente operativo.\
Intanto è stato aperto un ticket con l'azienda che si occupa del billing per cercare di alzare momentaneamente il budget prima delle 9:00 e riprendere l'operatività prima.\
La procedura che ha causato il problema è stata annullata in modo che alla ripresa del servizio non riprenda a consumare le risorse.

