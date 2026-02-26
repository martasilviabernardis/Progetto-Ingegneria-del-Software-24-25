# Progetto-Ingegneria-del-Software-24-25: GALAXY TRUCKER

Questo progetto è una versione software del gioco da tavolo Galaxy Trucker, sviluppata per la Prova Finale di Ingegneria del Software (A.A. 2024–2025).
L’implementazione segue fedelmente il regolamento ufficiale del gioco e rispetta tutti i requisiti game-specific e game-agnostic forniti.

Il progetto è stato realizzato in collaborazione con Luca Bevivino e Angelo Cantoli.

***DESCRIZIONE DEL PROGETTO***

Il sistema realizza una piattaforma client–server per partite multiplayer di Galaxy Trucker.
Il server gestisce interamente la logica di gioco, mentre i client consentono ai giocatori di partecipare tramite interfaccia testuale.

Il progetto adotta il paradigma MVC, separando chiaramente:

  - MODEL: stato della partita, navi, carte, giocatori
  - VIEW: interfaccia CLI
  - CONTROLLER: gestione delle azioni di gioco e sincronizzazione

La comunicazione client–server è implementata tramite RMI.

***FUNZIONALITA' PRINCIPALI***

   - Gestione completa delle regole di Galaxy Trucker
   - Costruzione e validazione automatica delle navi
   - Gestione delle carte avventura e delle fasi di volo
   - Partite multiplayer con nickname univoci
   - Sincronizzazione dello stato di gioco tra tutti i client
   - Interfaccia CLI per l’interazione con il gioco
   - Architettura e tecnologie

Linguaggio: Java
Architettura: Client–Server
Comunicazione: RMI
Paradigma: MVC
Interfaccia: CLI
Progettazione: UML (diagrammi di alto livello e di dettaglio)

***CONTENUTO DELLA REPOSITORY***

   - Specifica del progetto
   - Codice sorgente del client e del server
   - Diagrammi UML dell’architettura e dei componenti
   - Specifica ufficiale del progetto
   - Documentazione del protocollo di comunicazione
   - Test di unità
   - Documentazione JavaDoc
   - Relazione finale

--------------------------------------------------------------------------------------------------------------------

# Software Engineering Project 2024–2025: GALAXY TRUCKER

This project is a software version of the board game Galaxy Trucker, developed for the Final Project of Software Engineering (A.Y. 2024–2025).
The implementation faithfully follows the official game rules and complies with all the provided game-specific and game-agnostic requirements.

The project was developed in collaboration with Luca Bevivino and Angelo Cantoli.

***PROJECT DESCRIPTION***

The system implements a client–server platform for multiplayer Galaxy Trucker matches.
The server fully manages the game logic, while the clients allow players to participate through a textual interface.

The project adopts the MVC paradigm, clearly separating:

  - MODEL: game state, ships, cards, players  
  - VIEW: CLI interface  
  - CONTROLLER: management of game actions and synchronization  

Client–server communication is implemented using RMI.

***MAIN FEATURES***

   - Complete management of Galaxy Trucker rules  
   - Automatic ship construction and validation  
   - Management of adventure cards and flight phases  
   - Multiplayer matches with unique nicknames  
   - Synchronization of the game state across all clients  
   - CLI interface for game interaction  
   - Architecture and technologies  

Language: Java  
Architecture: Client–Server  
Communication: RMI  
Paradigm: MVC  
Interface: CLI  
Design: UML (high-level and detailed diagrams)

***REPOSITORY CONTENTS***

   - Project specification  
   - Client and server source code  
   - UML diagrams of the architecture and components  
   - Official project specification  
   - Communication protocol documentation  
   - Unit tests  
   - JavaDoc documentation  
   - Final report
