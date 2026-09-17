# Registro ore vocale: installer

Qui vengono pubblicati gli installer del programma Registro ore vocale. Il codice sorgente sta in un repository separato e privato.

L'ultima versione è nella pagina [Releases](https://github.com/folx25/registro-ore-releases/releases/latest):

- Mac con chip Apple: `Registro-ore-<versione>-mac-arm64.dmg`; Mac Intel: `-mac-x64.dmg`. Aprire il .dmg e trascinare il programma in Applicazioni. Al primo avvio, non essendo ancora firmato con certificato Apple, andare in Impostazioni di Sistema > Privacy e sicurezza > Apri comunque.
- Windows 10/11: `Registro-ore-<versione>-win-x64.exe` (o `-win-arm64.exe`). SmartScreen chiede "Ulteriori informazioni > Esegui comunque". Installazione per utente, senza amministratore.
- Linux: `.AppImage` o `.deb`.

Il programma installato controlla da solo le versioni nuove all'avvio e ogni quattro ore. Su Windows e Linux si aggiorna in automatico; su Mac, finché non è firmato, apre questa pagina per scaricare la versione nuova.

Al primo avvio servono le chiavi API (Anthropic, ElevenLabs e, facoltativa, OpenAI) nella finestra Impostazioni: restano sul computer, nella cartella dell'utente.
