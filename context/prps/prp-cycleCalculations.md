# PRP: Zyklusvorhersage-Algorithmus implementieren

**Modell:** Opus  

## Ziel  
Implementiere `calculateCycleInfo` in TypeScript.

### Datei  
`src/utils/cycleCalculations.ts`

### Typdefinition + Funktion
```ts
export interface CycleInfo {
  currentDay: number;
  phase: 'menstrual' | 'follicular' | 'ovulatory' | 'luteal';
  energyLevel: 1 | 2 | 3 | 4 | 5;
  trainingSuggestion: string;
  phaseDescription: string;
  daysUntilNext: number;
}

export function calculateCycleInfo(
  lastPeriodDate: Date,
  cycleLength: number = 28,
  periodDuration: number = 5
): CycleInfo {
  // TODO: Implementierung laut Spezifikation
}
```
