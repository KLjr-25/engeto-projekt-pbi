# Projekt Power BI – mzdy a ceny potravin v ČR

Autor: Květoslav Leidorf
Engeto – Datová akademie

## Obsah repozitáře

- `projekt_pbi.pbix` – report Power BI
- `README.md` – tento popis

## Data

Report vychází z výsledných tabulek prvního (SQL) projektu:

- `t_kvetoslav_leidorf_project_SQL_primary_final` – průměrné mzdy podle odvětví a ceny potravin v ČR za roky 2006–2018,
- `t_kvetoslav_leidorf_project_SQL_secondary_final` – HDP, GINI a populace evropských států.

Data jsou do reportu importována, soubor se tedy dá otevřít a procházet bez připojení k databázi.

## Stránky reportu

### 1. Přehled
- průřez let (posuvník od–do),
- karta: průměrná mzda, růst mezd a růst cen potravin za vybrané období,
- spojnicový graf: vývoj mezd a cen potravin jako index (rok 2006 = 100).

Hlavní zjištění: mzdy vzrostly za období 2006–2018 o 64 %, ceny potravin v průměru o 38 %. Dostupnost potravin se tedy zlepšila.

### 2. Detail
- průřezy podle odvětví a podle potravin,
- pruhový graf: průměrná mzda v jednotlivých odvětvích,
- tabulka: průměrná cena potravin a kolik jednotek lze koupit za průměrnou mzdu,
- bodový graf: meziroční růst HDP ČR vs. meziroční růst mezd (každý bod je jeden rok).

## Interaktivita

- navigační tlačítka mezi stránkami,
- tlačítko pro vymazání všech průřezů,
- odkaz na GitHub repozitář SQL projektu,
- vzájemné filtrování vizuálů kliknutím.

## Splnění zadání

| kritérium | splněno |
|---|---|
| 2–5 stránek | 2 stránky |
| min. 5 typů vizuálů | karta, spojnicový graf, pruhový graf, tabulka, bodový graf (+ průřezy, tlačítka) |
| filtrování průřezy | rok, odvětví, potraviny |
| interaktivní prvky | navigace, vymazání průřezů, odkaz na web |
