# Aggiornamenti · La Finestra srl

Qui stanno gli **installatori** del gestionale di La Finestra srl.

Non c'è codice: il programma vive in un archivio privato. Questo posto esiste per una
ragione sola — i computer dell'ufficio, quando cercano un aggiornamento, non hanno
nessuna password da mostrare, quindi i file devono stare in un posto che si apre
senza chiavi.

## Per chi ci lavora

Ogni versione sta sotto **Releases**. Il programma la scarica da solo da:

    https://github.com/6pbcbrvmbm-cloud/la-finestra-aggiornamenti/releases/latest/download

L'indirizzo non cambia mai: `latest` vuol dire «l'ultima che c'è».

## Come ci arriva una versione nuova

Nessuno carica niente a mano. Il codice sta nell'archivio privato del gestionale, e da
lì un'azione — **Actions → Aggiornamento** — costruisce l'installatore su un computer
Windows di GitHub e lo mette qui sotto Releases.

La release nasce **bozza** e diventa visibile solo dopo che l'installatore è salito.
Non è un vezzo: le postazioni guardano `latest.yml`, e se quel foglietto si vedesse
prima del file, una postazione che controlla in quel momento andrebbe a scaricare il
vuoto.

Chi pubblica trova le istruzioni in `crm/desktop/PUBBLICARE.md`, nell'archivio del
codice.
