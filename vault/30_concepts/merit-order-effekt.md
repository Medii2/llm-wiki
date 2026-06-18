---
title: "Merit-Order-Effekt"
note_type: concept
summary: "Preissetzungsmechanismus am Strommarkt: das teuerste eingesetzte Kraftwerk setzt den Preis für alle Anbieter"
canonical: true
aliases:
  - Merit Order
  - Merit-Order
related_notes: []
related_summaries:
  - "[[20_summaries/helaba-2026-energiebranche-transformation.md]]"
related_methods: []
related_datasets: []
related_synthesis: []
projects: []
tags:
  - concept
  - strommarkt
  - preisbildung
updated: "2026-06-08"
---

# Merit-Order-Effekt

## Definition

Der Merit-Order-Effekt beschreibt den Preissetzungsmechanismus am liberalisierten Strommarkt. Kraftwerke werden nach ihren Grenzkosten gereiht (Merit Order = Reihenfolge der Verdienste). Das letzte Kraftwerk, das benötigt wird, um die aktuelle Stromlast zu decken, setzt den Preis für alle Anbieter (Grenzkraftwerk = Marginalpreis).

## Scope boundaries

- Gilt für den kurzfristigen Spot- und Day-Ahead-Markt (z.B. EEX)
- Langfristige Investitionsentscheidungen folgen anderen Logiken

## Mechanism

1. Kraftwerke mit niedrigen Grenzkosten (EE: ~0, Kernkraft, Laufwasser) werden zuerst eingesetzt
2. Mit steigender Last kommen teurere Kraftwerke hinzu (Braunkohle → Steinkohle → Gas → Öl)
3. Das Grenzkraftwerk bestimmt den Marktpreis für alle
4. EE-Ausbau → drückt Grenzkraftwerk nach oben in der Reihenfolge → **Merit-Order-Effekt senkt Großhandelspreise** (statisch)
5. Bei Dunkelflaute rücken Gaskraftwerke ins Grenzkraftwerk → **Gaspreise dominieren Börsenstrompreis**

## How it is measured

- Börsenstrompreis (Grundlast, €/MWh, z.B. EEX)
- Korrelation Börsenstrompreis / Gaspreis
- CO₂-Zertifikatspreis (EUA) als Zusatzkosten für fossile Erzeuger

## Papers that discuss this concept

- [[20_summaries/helaba-2026-energiebranche-transformation.md]] — Erklärung warum höhere Gaspreise den Strompreis treiben; Erzeugermargen unter Druck

## How the papers use the concept

Helaba (2026): Merit Order erklärt, warum die Energiekrise 2022 (Gaspreisschock) zu historisch hohen Börsenstrompreisen führte; und warum der weitere EE-Ausbau langfristig Großhandelspreise senkt.

## Related concepts

- [[30_concepts/energiewende.md]]
- [[30_concepts/dekarbonisierung.md]]

## Related methods and datasets

—

## Open questions and tensions

- Dunkelflaute-Problem: Wie wird die Preisspitze durch Gaskraftwerke langfristig abgemildert (Speicher, Interconnectors)?
- Führt sinkender Großhandelspreis (durch EE-Ausbau) zu Unterinvestition in gesicherte Kapazität?

## Relevance for my research

Wichtig für Analysen der Rentabilität von Energieversorgern und des Finanzierungsbedarfs der Energiewende.
