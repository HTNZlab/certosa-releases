# Certosa — download ufficiali

Certosa è un'app per scrivere e conservare quaderni personali cifrati, con interfaccia italiana e inglese.

[Scarica Certosa 0.1f beta per Windows](https://github.com/HTNZlab/certosa-releases/releases/tag/v0.1f-beta.1) · [Apri la versione web](https://certosa.htnzlab.it/)

## Download e requisiti

- **Installer**: `Certosa-0.1f-windows-setup.exe`.
- **Portabile**: `Certosa-0.1f-windows-portabile.zip`; estrai tutta la cartella e apri `Certosa.exe`.
- Windows 10/11 a 64 bit e [Microsoft WebView2 Runtime](https://developer.microsoft.com/microsoft-edge/webview2/).
- `SHA256SUMS.txt` contiene le impronte dei due download. In PowerShell: `Get-FileHash .\Certosa-0.1f-windows-setup.exe -Algorithm SHA256`.

Questa è una **beta**. Gli eseguibili non sono firmati digitalmente: Windows può mostrare un avviso. Verifica provenienza e impronta del file prima di eseguirlo. Il funzionamento dell'EXE è stato verificato su Windows; installazione e disinstallazione su un PC pulito restano da collaudare. Non sono disponibili qui pacchetti nativi collaudati per macOS o Linux.

## Prova, licenza e acquisto

Il download è pubblico. L'app offre una prova di 14 giorni; alla scadenza i quaderni restano leggibili ed esportabili. L'attivazione avviene con un codice di licenza e richiede la connessione; successivamente la verifica della licenza è locale.

Per informazioni sull'acquisto e sulle licenze: [certosa@htnzlab.it](mailto:certosa@htnzlab.it). GitHub ospita i download e non gestisce il pagamento. Si applicano la licenza inclusa **PolyForm Noncommercial 1.0.0** e gli avvisi allegati; l'uso commerciale richiede una licenza separata.

## Conservare i quaderni

Prima di aggiornare o rimuovere l'app, usa **Impostazioni → Salva una copia (.certosa)** e conserva la copia e la sua password fuori dalla cartella del programma. La password dell'archivio non è recuperabile da HTNZlab.

Nel portabile Windows i dati vengono conservati in `Certosa-dati` accanto all'eseguibile, se la cartella è scrivibile; altrimenti viene usato il profilo utente. Per spostare un portabile conserva anche la cartella dei dati. La PWA conserva i dati nel browser: rimuovere i dati del sito può cancellarli, quindi salva prima una copia esterna.

Quaderni e password restano sul dispositivo. Registrazione e attivazione comunicano al servizio i dati descritti nell'informativa mostrata nell'app.

## Novità della 0.1f

- Foto e video diritti e ridimensionabili con mouse, touch e tastiera.
- Saluto di accesso tradotto quando si cambia lingua.
- Anteprima delle impostazioni con righe e aggiornamento di scrittura e corpo.
- Motto iniziale più leggibile e tradotto.

Questa repository contiene soltanto documentazione pubblica e download dell'app. I sorgenti e gli strumenti amministrativi sono conservati separatamente.
