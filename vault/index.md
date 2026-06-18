# Index

This is the content-oriented catalog of the research wiki.

Each entry should contain:
- page link
- one-line description
- optional metadata such as date, source count, or status

---

## Summaries

```dataview
TABLE authors, year, proximity, tags FROM "20_summaries"
WHERE note_type = "summary"
SORT proximity ASC, year DESC
```

## Concepts

```dataview
TABLE summary, tags FROM "30_concepts"
WHERE note_type = "concept"
SORT file.name ASC
```

## Methods

```dataview
TABLE summary, tags FROM "40_methods"
WHERE note_type = "method"
SORT file.name ASC
```

## Datasets

```dataview
TABLE summary, provider, geography FROM "50_datasets"
WHERE note_type = "dataset"
SORT file.name ASC
```

## People and Institutions

```dataview
TABLE summary, entity_type FROM "60_people_instructions"
WHERE note_type = "entity"
SORT file.name ASC
```

## Projects

```dataview
TABLE summary, status FROM "70_projects"
WHERE note_type = "project"
SORT file.name ASC
```

## Syntheses

```dataview
TABLE summary, tags FROM "90_synthesis"
WHERE note_type = "synthesis"
SORT file.name ASC
```

---

## Manual entries (non-Dataview)

### Summaries
- [[20_summaries/helaba-2026-energiebranche-transformation.md]] — Helaba Research & Advisory (2026): Status quo der deutschen Energiewende; Investitions- und Finanzierungsbedarfe; Hindernisse

### Concepts
- [[30_concepts/energiewende.md]] — Deutschlands Transformation zu erneuerbaren Energien und Klimaneutralität
- [[30_concepts/merit-order-effekt.md]] — Preissetzungsmechanismus am Strommarkt
- [[30_concepts/netzausbau-strominfrastruktur.md]] — Ausbau- und Umbaubedarfe der deutschen Stromnetze
- [[30_concepts/dekarbonisierung.md]] — CO₂-Reduktion als Zieldimension der Klimapolitik
- [[30_concepts/fremdkapitalfinanzierung-energiesektor.md]] — Finanzierungsinstrumente für Energiewende-Investitionen

### Datasets
- [[50_datasets/ag-energiebilanzen-strommix.md]] — Bruttostromerzeugung Deutschland nach Energieträgern (AGEB)

---

## Maintenance note

Whenever a new source is ingested, this index should be updated.
Whenever a new page is created, it should be added here in the correct section.
Whenever a page becomes obsolete, that should be reflected here.
