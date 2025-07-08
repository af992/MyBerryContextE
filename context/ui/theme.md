# MyBerry – Designsystem & Tamagui Tokens

## Farbpalette (60 % / 30 % / 10 %)

- **Deep Purple** `#4A148C` → Headlines, Akzente  
- **Vibrant Orange** `#FF6F00` → CTAs, Ovulation, sekundäre Inhalte  
- **Medium Purple** `#7B1FA2` → Sekundärfarbe (active Tabs)  
- **Light Purple** `#E1BEE7` → Hintergründe  

## WCAG-Kontrast & Spacing

- **WCAG AAA** Mindestkontrast  
- Systemschrift, `fontSize` 16–20  
- Spacing über Tamagui-Tokens: `$space.$1` .. `$space.$8`

## Tamagui Token-Mapping

| Token              | Bedeutung                 |
|--------------------|---------------------------|
| `$color.primary`   | Deep Purple               |
| `$color.secondary` | Vibrant Orange            |
| `$color.tertiary`  | Medium Purple             |
| `$bg.soft`         | Light Purple              |
| `$text.main`       | `$color.primary`          |
| `$text.accent`     | `$color.secondary`        |
| `$space.$n`        | n×4 px Padding/Margin     |