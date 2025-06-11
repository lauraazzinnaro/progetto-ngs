# Pipeline di Analisi FASTQ - NGS

Questo progetto permette di analizzare la qualità dei file FASTQ tipici del sequenziamento di nuova generazione (NGS), usando sia un’interfaccia grafica che uno script Python.

## Come usare il progetto senza terminale

### Aprire il progetto in PyCharm

1. Avvia PyCharm.
2. Seleziona **File > Open** e scegli la cartella del progetto.
3. Aspetta che PyCharm carichi tutti i file.

### Eseguire lo script con interfaccia grafica (consigliato)

1. Nel pannello del progetto, trova e apri il file `interfaccia_fastq.py`.
2. Fai clic destro sul file e scegli **Run 'interfaccia_fastq'**.
3. Si aprirà una finestra grafica.
4. Usa il pulsante **Scegli file FASTQ** per selezionare un file `.fastq` dal tuo computer.
5. Visualizza il report di qualità nel riquadro testo.
6. Clicca su **Mostra grafico qualità per posizione** per vedere il grafico.
7. Puoi salvare il report su file usando il pulsante dedicato.

### Eseguire lo script di analisi base

1. Apri `analisi_fastq.py`.
2. Fai clic destro e seleziona **Run 'analisi_fastq'**.
3. Assicurati che il file FASTQ di esempio (`sample.fastq`) sia nella cartella del progetto oppure modifica il percorso nel codice.
4. Il risultato apparirà nella console di PyCharm.

## Requisiti

- Python 3 (PyCharm solitamente gestisce già l’interprete)
- Modulo matplotlib per i grafici (puoi installarlo da PyCharm tramite **File > Settings > Python Interpreter > + > matplotlib > Install**)
