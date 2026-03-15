# HW02 - Lernplan

**Deadline: Mittwoch 18. März, 10:30 Uhr**
**Peter schreibt das Blatt per Hand ab.**

## Kreuzelliste (5 Kreuze, gleichgewichtet)

| # | Kreuz | Thema | Aufwand | Schwierigkeit |
|---|-------|-------|---------|---------------|
| 1 | **7(a,b)** | Gauß + Gauß-Jordan, 4×3 System (2 Varianten, nur RHS unterschiedlich) | ~55 min | Mittel |
| 2 | **7(c)** | 3×5 System → unendlich viele Lösungen, closed + expanded form | ~40 min | Mittel-Schwer |
| 3 | **7(d)** | 4×5 Matrixgleichung, gleiche Prozedur wie 7c | ~40 min | Mittel-Schwer |
| 4 | **8** | Parametrisches 2×2 System, Fallunterscheidung nach k | ~30 min | Mittel |
| 5 | **9** | Theoretische Fragen zu Ax=b (m>n, m<n) | ~20 min | Leicht-Mittel |

**Gesamtaufwand: ca. 3 Stunden**

## 3-Tage-Plan

### Sonntag 15. März — Kreuz 1 + 2 (2/5 Kreuze, ~1h 35min)

**Kreuz 1 — Aufgabe 7(a,b):**
- Sind fast identische Systeme (nur RHS von Gleichung 1: -1 vs 1). Mach beides hintereinander.
- **Vorgehen:** Erweiterte Koeffizientenmatrix aufstellen → Gauß-Elimination (Stufenform) → Rückwärtseinsetzen → dann nochmal Gauß-Jordan (reduzierte Stufenform). Alle Schritte mit ganzzahligen Koeffizienten!
- Eines wird vermutlich konsistent sein, das andere nicht — achte auf Widersprüche.

**Kreuz 2 — Aufgabe 7(c):**
- 3 Gleichungen, 5 Unbekannte → unendlich viele Lösungen.
  1. Gauß-Elimination
  2. Gauß-Jordan
  3. Lösung als **n-Tupel** (closed form)
  4. Lösung als **v₀ + t₁v₁ + ... + tₖvₖ** (expanded form)
- **Tipp:** Freie Variablen = Parameter setzen, gebundene Variablen ausdrücken.

### Montag 16. März — Kreuz 3 + 4 (4/5 Kreuze, ~1h 10min)

**Kreuz 3 — Aufgabe 7(d):**
- Gleiche Prozedur wie 7c, nur als Matrixgleichung gegeben. Matrix aufstellen und los.
- Wieder beide Verfahren + closed/expanded form falls unendlich viele Lösungen.

**Kreuz 4 — Aufgabe 8:**
- **Keine Determinanten verwenden!** Stattdessen Gauß-Elimination mit Parameter $k$ durchführen:
  - Erweiterte Matrix aufstellen und Zeilenumformungen mit k durchführen
  - Fallunterscheidung: Wann wird ein Pivot-Element 0? → Für welche k-Werte?
  - Dann je nach Fall prüfen: eindeutige Lösung / unendlich viele / keine Lösung

### Dienstag 17. März — Kreuz 5 + Kontrolle (5/5 Kreuze, ~30min)

**Kreuz 5 — Aufgabe 9:**
- Theorieaufgabe. Für jede der 3 Situationen:
  - m > n, eindeutige Lösung → **ja**, Beispiel angeben
  - m > n, unendlich viele → **ja**, Beispiel angeben
  - m < n, eindeutige Lösung → **nein**, begründen (mehr Unbekannte als Gleichungen)

**Abends:** Alles durchschauen, Peter gibt die Reinschrift ab.

## Wichtige Hinweise aus der Angabe

- Immer **ganzzahlige Koeffizienten** bei den Zeilenoperationen verwenden
- Bei konsistenten Systemen immer **beide** Verfahren zeigen (Gauß UND Gauß-Jordan)
- Bei unendlich vielen Lösungen: **closed form** (n-Tupel) UND **expanded form** (v₀ + t₁v₁ + ...)
