---
section: issue
title: Problemi di comunicazione col CED
date: 2020-09-28T07:15:00.000Z
resolved: true
informational: false
resolvedWhen: 2020-09-28T12:02:51.734Z
affected:
  - ced
severity: disrupted
---
*Aggiornamento* - In questo momento il CED è tornato a rispondere correttamente e quindi i servizi sono tornati a funzionare. {{< track "2020-09-28 14:00:00" >}}

*Aggiornamento* - Da alcuni test una piccolissima parte delle chiamate funziona correttamente, ma il grosso del traffico va ancora in errore. {{< track "2020-09-28 13:00:00" >}}

*Aggiornamento* - Continuano i problemi, ma la mitigazione permette di ridurre al minimo l'impatto sull'operatività. {{< track "2020-09-28 11:15:00" >}}

*Aggiornamento* - L'operatività delle revisioni dovrebbe essere salvaguardata, invece la mancanza di collegamento CED influisce sui seguenti servizi:

- importazione ACI con normalizzazione parte ma rimane in blocco

- normalizzazione di fine mese parte ma rimane in blocco

- caricamento veicoli lento perché il sistema cerca di aggiornare i dati identificativi del veicolo

- caricamento pratiche lento perché vengono caricati i veicoli secondo quando riportato sopra

{{< track "2020-09-28 10:05:00" >}}

*Mitigazione* - Stiamo procedendo ad un tentativo di mitigazione del problema diminuendo in modo consistente i timeout. {{< track "2020-09-28 09:55:00" >}}

*Indagine in corso* - Un disservizio da parte del CED causa rallentamenti nell'apertura di alcune pratiche e, in alcuni specifici casi, la totale impossibilità di aprirle. I problemi si ripercuotono anche sull'invio in linea di revisioni e sulla stampa delle relative etichette.