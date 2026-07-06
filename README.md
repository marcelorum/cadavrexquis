# cadavre-exquis — Exquisite Corpse with Sequence

A daily procedural poetry generator. Every weekday, a cron job picks 1 to 5
random lines from José Hernández's *Martín Fierro* and commits them to this
repository — one line per hour.

## How it works

- **Cron**: `0 9-20 * * 1-5` — every hour from 9 AM to 8 PM, Monday through Friday
- Each day a random number (1–5) decides how many lines will be added
- Lines are appended to [`cadavrexquis.txt`](cadavrexquis.txt) and pushed
  one by one throughout the day

The result is an evolving, aleatory poem — an *exquisite corpse* fed by one of
the foundational works of Argentine literature.

## Current state

- **Lines accumulated**: 2,023
- **Commits**: 2,070
- **Running since**: June 2023

## Reference

[*El Gaucho Martín Fierro*](https://es.wikipedia.org/wiki/El_Gaucho_Mart%C3%ADn_Fierro)
— José Hernández, 1872
