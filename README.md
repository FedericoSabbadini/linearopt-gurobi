# 📐 Linear Optimization with Gurobi

[![Java](https://img.shields.io/badge/Java-100%25-orange.svg)](https://openjdk.org)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

**Utilizzo di Gurobi Optimizer per risolvere problemi di ottimizzazione con Java.**

## Overview

Questo progetto dimostra l'uso di **Gurobi Optimizer** per risolvere problemi di ottimizzazione con Java. Include modelli di esempio e script che mostrano come formulare, risolvere e analizzare problemi di ottimizzazione lineare e intera usando il solver Gurobi.

## Purpose

L'obiettivo è fornire soluzioni e template di codice riutilizzabili per:

- Definire variabili di ottimizzazione, vincoli e funzioni obiettivo
- Risolvere problemi di programmazione lineare (LP), descritti in "Elaborato.txt"
- Estrarre e interpretare soluzioni dal modello Gurobi

## Struttura del Progetto

```
linear-optimization-gurobi/
├── src/it/unibs/gurobi/    # Codice sorgente
├── bin/it/unibs/gurobi/    # Classi compilate
├── myGurobilib/            # Libreria custom
├── .settings/              # Configurazione Eclipse
├── Elaborato.txt           # Descrizione del problema
├── coppia_24.txt           # Dati di input
└── README.md
```

## Requisiti

- Java 11+
- Gurobi Optimizer (con licenza)
- IDE Java (Eclipse consigliato)

## License

MIT License — See [LICENSE](LICENSE) for details.

*Nota: Gurobi Optimizer richiede una licenza separata da Gurobi Optimization, LLC.*
