# devs-kb-layout-ita

_devs-kb-layout-ita_ è un layout di tastiera personalizzato per Windows 10.

Il layout è basato su quello classico della tastiera italiana, con l'aggiunta di alcuni tasti specifici per gli sviluppatori, più alcuni altri segni che è comodo avere sulla tastiera, come le virgolette caporali o le vocali accentate maiuscole.

I tasti aggiunti, con le relative combinazioni da premere per attivarli, sono i seguenti:

Segno | Simbolo scritto | Tasti da premere
:---:| :---: | :---:
~ | Tilde | <kbd>ALT GR</kbd>+<kbd>ì</kbd>
~ | Tilde | <kbd>ALT GR</kbd>+<kbd>5</kbd>
\` | Backtick | <kbd>ALT GR</kbd>+<kbd>'</kbd>
« | Virgolette caporali aperte | <kbd>ALT GR</kbd>+<kbd>8</kbd>
» | Virgolette caporali chiuse | <kbd>ALT GR</kbd>+<kbd>9</kbd>
“ | Doppie virgolette aperte in alto | <kbd>ALT GR</kbd>+<kbd>6</kbd>
„ | Doppie virgolette chiuse in basso | <kbd>ALT GR</kbd>+<kbd>7</kbd>
À | _A_ accentata maiuscola | <kbd>ALT GR</kbd>+<kbd>SHIFT</kbd>+<kbd>à</kbd>
È | _E_ accentata maiuscola | <kbd>ALT GR</kbd>+<kbd>SHIFT</kbd>+<kbd>e</kbd>
Ì | _I_ accentata maiuscola | <kbd>ALT GR</kbd>+<kbd>SHIFT</kbd>+<kbd>ì</kbd>
Ò | _O_ accentata maiuscola | <kbd>ALT GR</kbd>+<kbd>SHIFT</kbd>+<kbd>ò</kbd>
Ù | _U_ accentata maiuscola | <kbd>ALT GR</kbd>+<kbd>SHIFT</kbd>+<kbd>ù</kbd>

>**Nota**: La combinazione per generare la `È` utilizza i tasti <kbd>SHIFT</kbd> e la <kbd>E</kbd> non accentata, differentemente dalla convenzione usata per scrivere le altre maiuscole accentate aggiunte da questo layout, in quanto la combinazione <kbd>ALT GR</kbd>+<kbd>SHIFT</kbd>+<kbd>è</kbd> viene usata già dal layout normale di Windows per generare la parentesi graffa aperta `{`.

## Installazione

Per installare il layout basta [scaricare](https://github.com/linuxiamo/devs-kb-layout-ita/archive/master.zip) manualmente il file zippato del repository, decomprimerlo e lanciare `setup.exe` che si trova nella cartella `install`.

In alternativa per scaricare il repository si può usare anche _Git Bash_:
```bash
git clone https://github.com/linuxiamo/devs-kb-layout-ita devs-kb-layout-ita
```

Una volta completata l'installazione occorre riavviare Windows, quindi, per poter utilizzare i nuovi tasti, dalla barra delle applicazioni in basso a destra, accanto all'orario, selezionare il layout tastiera indicato come "ITA".

È consigliabile rimuovere dalle Impostazioni di Windows, il layout di tastiera originale, in modo da non incorrere in un inavvertito cambio di layout qualora si premesse per sbaglio l'apposito shortcut.

## Personalizzazione del layout di tastiera

Se lo si desidera, è possibile personalizzare il layout di tastiera, utilizzando l'apposita utility ufficiale <a href="https://www.microsoft.com/en-us/download/details.aspx?id=22339" terget="_blank">MSKLC</a> di Microsoft.

Il file sorgente del layout si trova nella cartella `src` di questo repository.
