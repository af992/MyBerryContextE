# Feature: Onboarding – Zero Setup Intelligence

## Zweck
Schnelle Erfassung des letzten Periodenstarts, um sofort Zyklus-Empfehlungen zu liefern.

## Ablauf & Screens
1. **PrivacyScreen**  
   - DSGVO-Hinweis, Buttons: „Weiter“, „Überspringen“  

2. **PeriodInputScreen**  
   - Eingabe: Datum der letzten Periode  
   - Option: Zykluslänge („Weiß ich nicht“ → default 28 Tage)  
   - UX: klare Labels, Spacing nach Theme  

3. **CompletionScreen**  
   - Output:  
     - aktueller Zyklustag  
     - Zyklusphase  
     - Tage bis nächste Periode  
   - Button: „Zum Dashboard“

## UX-Regeln
- Jeder Step < 30 Sek.  
- Purple-Orange Manifest einhalten  
- `testID`-Props für E2E  
- Sofortiges Feedback, minimale Klicks  

## Success Criteria
- Navigation: Privacy → Period → Completion ohne Crash  
- Datumseingabe & Default-Handling funktionieren  
- Abschlussschritt bietet Aktion „Zum Dashboard“  