# Gamification Lernplattform – Prototypen

Dieses Repository enthält die interaktiven HTML/CSS/JS-Prototypen, die im Rahmen der Transferarbeit 3 (TA3) «Gamification von Ausbildungsstellen im BIT mittels Design Science Research» an der FFHS entstanden sind.

## Hintergrund

Die Prototypen sind Teil des Design Cycle nach dem DSR-Framework (Hevner et al., 2004). Sie illustrieren ein Konzept für eine webbasierte Ausbildungsunterstützungsapplikation für Auszubildende und Praxisbildende im Bundesamt für Informatik und Telekommunikation (BIT). Sie dienen ausschliesslich als Mockups zur vereinfachten Darstellung der erarbeiteten Konzepte und sind nicht für den produktiven Einsatz vorgesehen.

Die Anforderungen wurden im Relevance Cycle durch drei Experteninterviews erhoben; die Gestaltungsprinzipien basieren auf einer Literaturanalyse zu Gamification im Arbeits- und Ausbildungskontext (Rigor Cycle).

## Module

| Modul | Bezeichnung | Beschreibung |
|-------|-------------|--------------|
| M1 | Fortschrittsvisualisierung & Kompetenztracking | Skilltree-Darstellung der Handlungskompetenzen aus der BiVo mit Fortschrittsbalken und Statusanzeige |
| M2 | Feedback & Kommunikation | Strukturierter, kompetenzgebundener Feedbackprozess zwischen Praxisbildenden und Auszubildenden inkl. Feedbackhistorie |
| M3 | Erweiterte Gamification-Elemente | Badge- und Meilenstein-System (Major/Minor) mit konfigurierbarer Badge-Galerie |
| M4 | Benachrichtigungen & sozialer Vergleich | Peer-Badges, anonymisierter Jahrgangsvergleich und konfigurierbare Erinnerungen/Nudges |

## Struktur

```
index.html                          # Übersichtsseite aller Module
M1/
  M1_SkillTree.html
  M1_SkillTree.css
  BP_Context                        # Kontext-Datei für den Bildungsplan
M2/
  M2_FeedbackAndCommunication.html
  M2_FeedbackAndCommunication.css
M3/
  M3_ExtendedGamificationElements.html
M4_NotificationAndSocialComparison/
  M4_NotificationAndSocialComparison.html
```

## Verwendung

Die Prototypen sind statische HTML-Seiten ohne Backend. Sie können direkt im Browser geöffnet oder über GitHub Pages aufgerufen werden:

**https://thrawn10.github.io/Transferarbeit3_Gamification/**

## Disclaimer

Die Prototypen wurden KI-gestützt (Claude AI, GitHub Copilot) auf Basis der im Relevance- und Rigor Cycle erarbeiteten Inhalte generiert und vom Autor überarbeitet. Design-Konzepte wie der Skilltree und das Badge-System stammen vom Autor. Die Prototypen erfüllen keine Produktionsanforderungen (kein Backend, keine Authentifizierung, keine echten Daten).

## Kontext

- **Arbeit:** Transferarbeit 3, FFHS PiBS Informatik, HS25
- **Autor:** Tim Ambühl
- **Abgabedatum:** 10.05.2026
- **Framework:** Design Science Research nach Hevner et al. (2004)

---

© 2026 Tim Ambühl. Alle Rechte vorbehalten.
