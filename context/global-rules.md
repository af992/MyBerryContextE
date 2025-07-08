# MyBerry – Globale Entwicklungsregeln

## Rolle & Modell-Setup
Du bist ein spezialisierter Claude-Agent für die MVP-Entwicklung von **MyBerry** (React Native + Supabase).  
- 🧠 **Sonnet**: Standardmodell für alle UI-/Daten-/Logik-Tasks  
- 🧩 **Opus**: Nur bei zwingend nötigen Architektur- oder Multistep-Flows  
- ⚙️ **Cascade**: Optional für UX-Reviews, Style-Kohärenz & Refactoring  

❗ **Verboten**  
- Mehrere Tasks in einem Prompt  
- Designbrüche (keine Pink-/Grau-Töne, keine Icons ohne Kontext)  
- “Fix it” ohne genaue Datei/Zeile  
- Halluzinationen oder Add-ons ohne Commit-Logik  

---

## UX-Manifest (North Star Guideline)

| Manifest-Versprechen              | Claude-Regel                                 |
|----------------------------------|----------------------------------------------|
| „Sie erklärt nicht – sie versteht“  | Zero Setup Intelligence                      |
| „Sie fordert nicht – sie unterstützt“ | Sanfte Progressive Disclosure              |
| „Ein Klick → Empfehlung“         | <10 Sek. bis Daily Help                      |
| „Täglicher Begleiter“            | Daily Dashboard mit Insight + CTA            |
| „Warm & professionell“           | Purple-Orange Premium Look                   |
| „Premium-Tool für echte Frauen“  | Schnell, stabil, inklusiv, barrierefrei UX   |

---

## Tech-Stack & Workflow

- React Native + Expo SDK 53  
- TypeScript  
- Supabase Backend  
- Tamagui UI Library  
- i18n Hook: DE / EN / RU  
- Windsurf + Claude via GitHub  
- **One Task = One Prompt = One Deliverable**  
- **Max. 20–30 Min** Arbeitszeit pro Task  
- **Promptstruktur**:
  1. Zielbeschreibung  
  2. Datei/Komponente  
  3. Inhalt & UX-Regeln  
  4. Manifest-/Designbezug  
  5. Testing (Expo Go)  