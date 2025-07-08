# Feature: Zyklusvorhersage-Logik

## Zweck
Implementierung eines wissenschaftlichen Algorithmus für Zyklusphase & Energie-Empfehlungen.

## Input
- letztes Periodendatum (Date)  
- Zykluslänge (number, default 28)  
- Periodendauer (number, default 5)  

## Output
- currentDay (1…cycleLength)  
- phase: `menstrual` | `follicular` | `ovulatory` | `luteal`  
- energyLevel (1…5)  
- trainingSuggestion (string)  
- daysUntilNext (number)  

## Wissenschaftliche Basis
- Alissa Vitti (4-Phasen-Modell)  
- Stacy Sims (hormonbasierte Trainings-Periodisierung)  
- FLO / Clue (28-Tage-Zyklus, Ovulation ∼ Tag 14)  

## UX-Regeln
- Logik in `utils`, nicht in Screens  
- TypeScript-Typen & Unit-Tests  
- Schnelle Ausführung (< 50 ms)  

## Success Criteria
- Funktion `calculateCycleInfo()` liefert `CycleInfo`  
- Flexible Zykluslängen (21–35 Tage)  
- Unit-Tests für Phasen & Energy  