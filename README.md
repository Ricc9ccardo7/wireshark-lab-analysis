
# Analisi del Traffico di Rete

Questo repository contiene una raccolta di analisi del traffico di rete realizzate come parte di un assignment per il corso di `Network and Communication` presso la **University of the People (UoPeople)**.
L’elaborato è stato originariamente preparato in `inglese` e successivamente `tradotto in italiano`.

Il repository include file di cattura del traffico (`.pcapng`) e relative analisi scritte (`.md`) sui diversi protocolli di rete, illustrando come i protocolli funzionano e interagiscono nel traffico reale.

---

## 📂 Struttura del Repository

* **analyses/**
  Documenti in formato Markdown con analisi dettagliate dei protocolli di rete:

  * `01-DHCP+ARP.md` : Analisi della comunicazione DHCP e ARP
    
  * `02-DNS resolution.md` : Processo di risoluzione dei nomi DNS
    
  * `03-ICMP.md` : Messaggi ICMP e richieste/risposte echo
    
  * `04-TCP_Retransmition.md` : Ritrasmissioni TCP e affidabilità
    
  * `05-HTTPS.md` : Handshake, HTTPS e traffico cifrato
    
  * `06-SMB2.md` : Analisi del protocollo SMB2
    
  * `07-SSH.md` : Analisi della connessione sicura SSH
    
  * `08-mDNS.md` : Scoperta tramite Multicast DNS

* **pcaps/**
  File di cattura del traffico da aprire con Wireshark o strumenti simili:

  * `mixed_traffic.pcapng`
  * `smb445.pcapng`

* **images/**
  Immagini e screenshot a supporto delle analisi.

* **README.md**
  Documentazione del progetto (questo file).



##  Istruzioni per l’uso

1. Aprire i file `.pcapng` nella cartella **pcaps/** utilizzando [Wireshark](https://www.wireshark.org/).
2. Consultare la relativa analisi in **analyses/** per una spiegazione passo dopo passo del traffico osservato.




##  Obiettivi Formativi

Questo progetto dimostra:

* Comprensione dei principali protocolli di rete (DHCP, ARP, DNS, ICMP, TCP, HTTPS, SMB2, SSH, mDNS).
* Analisi pratica del traffico con `Wireshark`.
* Identificazione dei comportamenti protocollari, dei flussi di comunicazione e delle anomalie.
* Collegamento tra concetti teorici e applicazioni pratiche dell’analisi di rete.



##  Lingua

* Versione originale: `Inglese`
* Versione attuale: `Traduzione in Italiano`



##  Riferimenti

* [Documentazione Wireshark](https://www.wireshark.org/docs/)
* Materiali del corso **CS 2204 – Network and Communication** (UoPeople)



