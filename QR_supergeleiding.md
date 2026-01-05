# Supergeleiding – Experiment

Dit Jupyter Notebook is gebaseerd op het practicum **Supergeleiding (Quantum Rules!)**.

## Inleiding
In 1911 ontdekte Heike Kamerlingh Onnes dat de elektrische weerstand van kwik nul wordt onder 4,2 K. Dit verschijnsel noemen we **supergeleiding**.

In dit experiment onderzoeken we drie weerstanden (A, B en C):
- een goudweerstand
- een halfgeleider
- een supergeleider

Door deze af te koelen met vloeibare stikstof meten we hun elektrische weerstand

## Onderzoeksvraag
- Hoe herkennen we de supergeleidende toestand?
- Welk sample (A, B of C) is de supergeleider?

## Stap 1 – Weerstanden bij kamertemperatuur
Noteer de gemeten weerstanden en maak een eerste inschatting.

  import pandas as pd

    data_room = pd.DataFrame({
    'Sample': ['A', 'B', 'C'],
    'Weerstand (Ohm)': [None, None, None],
    'Verwacht type': ['', '', '']
    })

    data_room'''
