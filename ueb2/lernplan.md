# HW02 - Lernplan

**Deadline: Mittwoch 18. März, 10:00 Uhr**
**Peter schreibt das Blatt per Hand ab.**

## Übersicht der Aufgaben

| Aufgabe | Thema | Aufwand | Schwierigkeit |
|---------|-------|---------|---------------|
| **7a** | Gauß + Gauß-Jordan, 4×3 System | ~30 min | Mittel |
| **7b** | Gleiches System, leicht geändert (RHS=1 statt -1) | ~25 min | Mittel |
| **7c** | 3×5 System (unendlich viele Lösungen erwartet) → closed + expanded form | ~40 min | Mittel-Schwer |
| **7d** | 4×5 Matrixgleichung → gleich wie 7c aber als Matrix | ~40 min | Mittel-Schwer |
| **8** | Parametrisches 2×2 System, Fallunterscheidung nach k | ~30 min | Mittel |
| **9** | Theoretische Fragen zu Ax=b (m>n, m<n), Beispiele/Begründungen | ~20 min | Leicht-Mittel |

**Gesamtaufwand: ca. 3 Stunden**

## 3-Tage-Plan

### Sonntag 15. März — Aufgabe 7a + 7b (~55 min)

- **7a & 7b** sind fast identische Systeme (nur die rechte Seite von Gleichung 1 unterscheidet sich: -1 vs 1). Mach beides hintereinander.
- **Vorgehen:** Erweiterte Koeffizientenmatrix aufstellen → Gauß-Elimination (Stufenform) → Rückwärtseinsetzen → dann nochmal Gauß-Jordan (reduzierte Stufenform). Alle Schritte mit ganzzahligen Koeffizienten!
- Eines wird vermutlich konsistent sein, das andere nicht (oder unterschiedliche Lösungen) — achte auf Widersprüche.

### Montag 16. März — Aufgabe 7c + 7d (~1h 20min)

- **7c:** 3 Gleichungen, 5 Unbekannte → wird unendlich viele Lösungen haben. Du musst:
  1. Gauß-Elimination
  2. Gauß-Jordan
  3. Lösung als **n-Tupel** (closed form)
  4. Lösung als **v₀ + t₁v₁ + ... + tₖvₖ** (expanded form)
- **7d:** Gleiche Prozedur, nur als Matrixgleichung gegeben. Matrix aufstellen und los.
- **Tipp:** Bei freien Variablen systematisch vorgehen — freie Variablen = Parameter setzen, gebundene Variablen ausdrücken.

### Dienstag 17. März — Aufgabe 8 + 9 (~50 min)

- **8:** Determinante der 2×2 Koeffizientenmatrix berechnen (hängt von k ab). Dann:
  - Det ≠ 0 → eindeutige Lösung
  - Det = 0 → Gleichungen einsetzen, prüfen ob unendlich viele oder keine Lösung
- **9:** Theorieaufgabe. Für jede der 3 Situationen:
  - m > n, eindeutige Lösung → **ja**, Beispiel angeben
  - m > n, unendlich viele → **ja**, Beispiel angeben
  - m < n, eindeutige Lösung → **nein**, begründen (mehr Unbekannte als Gleichungen → mindestens eine freie Variable, falls konsistent)
- **Abends:** Alles nochmal durchschauen, sauber abschreiben.

## Wichtige Hinweise aus der Angabe

- Immer **ganzzahlige Koeffizienten** bei den Zeilenoperationen verwenden
- Bei konsistenten Systemen immer **beide** Verfahren zeigen (Gauß UND Gauß-Jordan)
- Bei unendlich vielen Lösungen: **closed form** (n-Tupel) UND **expanded form** (v₀ + t₁v₁ + ...)
