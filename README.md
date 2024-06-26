
# Bingo Online Bootstrap
Bingo Multi-Player in cui giocare le Cartelle del Botteghino o le Cartelle del Tabellone


> [!TIP]
> Corretto funzionamento garantito

> [!TIP]
> Sito web **Responsive** con modalità **Desktop** e **Mobile**


## Icona 
<img src="https://github.com/vittorioPiotti/Bingo/blob/main/img/icona.png" alt="Icona" width="100"/>




## Sito Web

Sito Web Bingo: [Link al Sito](https://vittoriopiotti.altervista.org/Bingo/Online/index.php)

---

<img src="https://github.com/vittorioPiotti/Bingo-Online-Bootstrap/blob/main/socialpreview.png" />




## API

| Nome API                | URL                    | Parametri                           | Descrizione                                                                    |
|-------------------------|------------------------|-------------------------------------|--------------------------------------------------------------------------------|
| **creaPartita**         | `/event=0`             | `id`                                | Crea una nuova partita con l'id del giocatore specificato.                      |
| **eliminaPartita**      | `/event=1`             | `id`                                | Elimina la partita associata all'id del giocatore specificato.                  |
| **aggiornaListaCodici** | `/event=3`             | Nessuno                             | Aggiorna la lista dei codici disponibili.                                       |
| **aggiornaStorico**     | `/event=4`             | `id`, `str`                         | Aggiorna lo storico della partita con una stringa specificata.                  |
| **ottieniStorico**      | `/event=5`             | `id`                                | Ottiene lo storico della partita per un giocatore specificato.                  |
| **accediPartita**       | `/event=6`             | `id`, `username`, `ruolo`           | Permette a un giocatore di accedere a una partita con username e ruolo specificati. |
| **uscitaPartita**       | `/event=7`             | `id`, `username`                    | Permette a un giocatore di uscire dalla partita specificata.                    |
| **ottieniListaPartecipanti** | `/event=8`        | `id`                                | Ottiene la lista dei partecipanti per una partita specificata.                  |
| **aggiornaStatoGiocatore** | `/event=9`          | `id`, `username`, `stato`           | Aggiorna lo stato di un giocatore nella partita specificata.                   |
| **verificaTuttiPronti**  | `/event=10`           | `id`                                | Verifica se tutti i giocatori sono pronti nella partita specificata.           |
| **aggiornaStatoPartita** | `/event=11`           | `id`                                | Aggiorna lo stato della partita specificata.                                    |
| **ottieniStatoPartita** | `/event=12`           | `id`                                | Ottiene lo stato della partita specificata.                                     |
| **verificaPresenzaUsername** | `/event=13`        | `id`, `username`                    | Verifica se l'username è presente nella partita specificata.                   |
| **aggiornaNumeriEstratti** | `/event=14`          | `id`, `num`                         | Aggiorna i numeri estratti per la partita specificata.                          |
| **ottieniNumeriEstratti** | `/event=15`           | `id`                                | Ottiene i numeri estratti per la partita specificata.                           |
| **initPremi**           | `/event=16`            | `id`                                | Inizializza i premi per la partita specificata.                                 |
| **aggiornaPremio**      | `/event=17`            | `id`, `username`, `premio`          | Aggiorna il premio per un giocatore specificato nella partita.                  |
| **ottieniPremi**        | `/event=18`            | `id`                                | Ottiene i premi per la partita specificata.                                      |
| **ripristinaNumeri**    | `/event=19`            | `id`                                | Ripristina i numeri per la partita specificata.                                  |


## Licenze

| Componente         | Versione  | Copyright                         | Licenza                                                       |
|--------------------|-----------|-----------------------------------|---------------------------------------------------------------|
| Bingo-Online-Bootstrap | v1.0.0    | 2024 Vittorio Piotti              | [GPL-3.0 License](https://github.com/vittorioPiotti/Bingo-Online-Bootstrap/blob/main/LICENSE.md) |
| Bootstrap          | v4.0.0    | 2011-2018 The Bootstrap Authors   | [MIT License](https://github.com/twbs/bootstrap/blob/master/LICENSE) |
