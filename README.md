# ArchaeoDB

**ArchaeoloDB** è un'applicazione web open source per la gestione e l'analisi di dati archeologici. Il progetto è sviluppato in Python, utilizza il framework Flask per il rendering dell'applicazione e PostgreSQL come database.

## Caratteristiche

- Gestione di siti archeologici, reperti, e metadati associati.
- Interfaccia web user-friendly per l'inserimento, modifica e ricerca dei dati.
- Sistema di autenticazione e autorizzazione degli utenti.

## Requisiti

- **Python** 3.9 o superiore
- **PostgreSQL** 13 o superiore
- **pip** per la gestione delle dipendenze
- Ambiente virtuale Python (consigliato)

## Struttura del progetto

```
archaeological-db-manager/
│
├── app/
│   ├── __init__.py         # Configurazione di Flask
│   ├── models.py           # Modelli del database
│   ├── routes.py           # Rotte dell'applicazione
│   ├── templates/          # Template HTML
│   └── static/             # File statici (CSS, JS, immagini)
│
├── migrations/             # Migrazioni del database
├── tests/                  # Test automatici
├── requirements.txt        # Dipendenze Python
├── config.py               # Configurazione dell'app
├── .env.example            # Esempio di file .env
└── README.md               # Questo file
```

## Contributi

Contributi e suggerimenti sono benvenuti! Per contribuire:

1. Fai un fork del progetto.
2. Crea un nuovo branch per le tue modifiche:
   ```bash
   git checkout -b feature-nome-funzionalità
   ```
3. Implementa le modifiche e scrivi i test necessari.
4. Invia una pull request.

## Licenza

Questo progetto è rilasciato sotto licenza **MIT**. Vedi il file [LICENSE](LICENSE) per maggiori dettagli.

## Contatti

Per domande o feedback, puoi contattare l'autore via email a [dev@bughunter.me].
```