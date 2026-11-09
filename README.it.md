# Certosa — gratuita e open source

[English](README.md) · **Italiano**

Certosa è una biblioteca digitale personale dove scrivere, leggere e raccogliere idee in quaderni. La versione attuale è **gratuita** e il
codice Certosa è distribuito con **licenza MIT**: non richiede registrazione,
indirizzo email, codice di attivazione o licenza a pagamento e non ha una
scadenza di prova.

[Apri Certosa sul web](https://certosa.htnzlab.it/) ·
[Pagina del prodotto e download](https://htnzlab.it/prodotto/certosa)

## Certosa 0.3.8 — Windows e Web/PWA

Griglia e stili dei paragrafi migliorati, formattazione conservata con Invio,
ricerca completa nelle note e ripristino di PDF/audio. Compatibile con MCP alpha.3.

- [Windows x64 — installer](https://github.com/HTNZlab/certosa-releases/releases/download/v0.3.8/Certosa-0.3.8-windows-setup.exe)
- [Windows x64 — portatile](https://github.com/HTNZlab/certosa-releases/releases/download/v0.3.8/Certosa-0.3.8-windows-portabile.zip)
- [Sorgenti Windows con wrapper Rust/Tauri e frontend](https://github.com/HTNZlab/certosa-releases/releases/download/v0.3.8/Certosa-0.3.8-windows-sorgenti.zip)
- [Apri la Web/PWA](https://certosa.htnzlab.it/)
- [Pacchetto Web/PWA](https://github.com/HTNZlab/certosa-releases/releases/download/v0.3.8/Certosa-0.3.8-web.zip)
- [HTML offline con codice client](https://github.com/HTNZlab/certosa-releases/releases/download/v0.3.8/Certosa-0.3.8-offline.html)
- [SHA256SUMS](https://github.com/HTNZlab/certosa-releases/releases/download/v0.3.8/SHA256SUMS.txt) · [Manifest Windows](https://github.com/HTNZlab/certosa-releases/releases/download/v0.3.8/MANIFEST-WINDOWS.json)
- [MCP 0.0.6-alpha.3](https://github.com/HTNZlab/certosa-mcp/releases/tag/v0.0.6-alpha.3)

Windows richiede WebView2. Build native-lite, con lettura tramite voce del
dispositivo; modelli TTS opzionali non inclusi. Eseguibili non firmati.
Collaudati su Windows 11 x64: installer, portatile, archivio cifrato, riavvio,
import/export PNG/PDF/WAV, conservazione del quaderno 0.3.4 e dei dati dopo disinstallazione.

Nel portatile, conservare **Certosa-dati** accanto all'EXE. Esportare una copia
`.certosa` con la propria password prima dell'aggiornamento. Non cancellare i dati
per aggiornare il programma. [Compilare dai sorgenti](WINDOWS-BUILD.md).
La ricerca non include contenuto PDF, OCR e nomi degli allegati.
I pacchetti Linux precedenti restano disponibili nella [release 0.3.4](https://github.com/HTNZlab/certosa-releases/releases/tag/v0.3.4).

## Pacchetti desktop precedenti — 0.3.4

[Download storici 0.3.4](https://github.com/HTNZlab/certosa-releases/releases/tag/v0.3.4).

## Licenza

Il codice Certosa della linea gratuita è disponibile secondo la
[licenza MIT](LICENSE.md). Può essere usato, studiato, modificato e distribuito,
anche per uso commerciale, conservando l'avviso di copyright e il testo della
licenza.

Font, librerie, modelli vocali, registrazioni e altri componenti di terzi
conservano le rispettive licenze. I relativi avvisi sono inclusi nei pacchetti
che li distribuiscono; la licenza MIT di Certosa non li sostituisce.

### Release storiche in questa repository

Le release GitHub `v0.1f-beta.1` e `v0.2beta.5` sono conservate come archivio
storico della precedente beta. Quei file **non sono la distribuzione gratuita
corrente** e non vengono retroattivamente rilicenziati: per ciascun vecchio
pacchetto resta applicabile la licenza inclusa al suo interno al momento della
pubblicazione.

Per usare Certosa oggi, scegli la Web/PWA oppure i download 0.3.4 indicati
sopra.

## Conservare i quaderni

Quaderni e password restano sul dispositivo. Prima di aggiornare, rimuovere
l'app o cancellare i dati del browser, usa **Esporta libreria (.certosa)** e
conserva la copia e la sua password fuori dalla cartella del programma.

La password non è recuperabile da HTNZLab. La PWA conserva i dati nello spazio
del browser; l'installazione della PWA non sostituisce una copia esterna.

Questa repository conserva la documentazione pubblica e le release ufficiali.
