# HackInBo2020_SafeEdition
## DFIR Lab
# Cosa faremo?
L’obiettivo del presente laboratorio sarà l’analisi di due immagini forensi, l’una in formato WMDK e l’altra in E01, generate rispettivamente da una macchina macOS compromessa e una macchina Windows utilizzata da un attaccante.
Il nostro obiettivo sarà quello di analizzare la macchina compromessa alla ricerca di evidenze di compromissione e di risposte a domande del tipo: 
1. Quale metodo ha utilizzato l’attaccante per avere accesso alla macchina?
2. Quali tracce del suo operato sono tutt’ora presenti?
3. Quali metodi ha utilizzato per assicurarsi (siamo veramente sicuri??) persistenza?

D’altro canto, una volta individuata ed acquisita la macchina dell’attaccante, dovremo essere in grado di capire esattamente quali sono stati i passi compiuti per la compromissione:
1. Che sistema ha utilizzato?
2. Quali dati è riuscito ad esfiltrare?
3. Quali programmi ha utilizzato per compromettere il sistema macOS?
4. ...?

# Cosa vi servirà?
Per arrivare preparati alla giornata di **sabato 30 maggio** consiglio di scaricare i seguenti tools:
- VMware (qualsiasi versione)
- Zimmermann's tools (https://ericzimmerman.github.io/)
- Autopsy 4.15 (https://www.autopsy.com/download/)
- FTK Imager v.4.3.0 (https://accessdata.com/product-download/ftk-imager-version-4-3-0)
- TSK (https://www.sleuthkit.org/sleuthkit/)
- plist editor (https://www.icopybot.com/plist-editor.htm)

Si consiglia di arrivare al giorno dell’evento con le immagini già processate in Autopsy.

# Dove scaricare le immagini
Le immagini si trovano all’interno di un archivio 7z scaricabile al seguente link:

https://www.dropbox.com/s/2zcnevfz2d6nedz/HackInBo2020_SafeEdition_DFIR.7z?dl=0

**Data la dimensione (55GB) si consiglia di iniziare il download prima possibile!**

# Cosa mi serve per seguire al meglio questo workshop?
Per essere a vostro agio con lo scenario proposto, si consiglia di:
- Utilizzare una macchina Windows;
- Installare tutti i programmi segnalati;
- Aver processato le rispettive immagini con il software Autopsy;
- Avere delle basi di Windows Forensics
- Avere conoscenze, anche superficiali, di macOS Forensics 

**NOTA BENE:** durante il workshop, date le tempistiche a disposizione (45 minuti), alcuni concetti potrebbero essere dati per scontati. Sarà messo a disposizione dei partecipanti un link Zoom dove continuare la discussione dello scenario proposto.

# Dettaglio scenario
Verrà pubblicato ASAP un file pdf contenente i dettagli dello scenario proposto
