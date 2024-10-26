---
sidebar_position: 2
keywords:
  - pdf
---

# LB 2 : Sprint 2

## Überblick

| Sozialform               | Form                      | Abgabe  | Gewicht               |
| :----------------------- | :------------------------ | :------ | :-------------------- |
| :smile: **Einzelarbeit** | 🗣️ Fachgespräch           | Woche 8 | 30% vom LB2           |
| :smile: **Einzelarbeit** | 🖋️ Schriftliche Reflexion | Woche 8 | 30% vom LB2           |
| 👬 **Gruppenarbeit**     | 👷 Arbeitsvorgang         | Woche 8 | 40% vom LB2           |
| ...                      |                           |         |                       |
|                          | 🏅 **LB2: Sprintnote**    | Woche 8 | **1/3 der Modulnote** |

## Teilnote: Fachgespräch

Am **Ende des Sprints** findet ein Sprint-Review, in Form eines
**Fachgespräches** statt. Jedes Gruppenmitglied wird zum **Sprint 2** und den
dabei relevanten Themen **8 Minuten** befragt.

:::caution Achtung!

Die Themen sind auf den jeweiligen [Sprint-Beschreibungen](../sprints/index.md)
ersichtlich.

:::

### Bewertung

| Was           | Wie                                                       | Punkte |
| ------------- | --------------------------------------------------------- | ------ |
| Inhalt        | Ist korrekt und entspricht der Fragen der Diskussion.     | 4      |
| Wissen        | Brauchte keine Hilfestellungen.                           | 2      |
| Fachbegriffe  | Werden richtig und an stelle von Umschreibungen verwendet | 2      |
| Kommunikation | Die Antworten erfolgen deutlich, zügig und klar           | 2      |
| ...           |                                                           |        |
| **Total**     |                                                           | **10** |

## Teilnote: Schriftliche Reflexion

Am **Ende des Sprints** wird in **Einzelarbeit** eine **schriftliche Reflexion**
über den Verlauf des Sprint 2 verfasst.

### Bewertung

| Thema                                                        | Punkte |
| :----------------------------------------------------------- | -----: |
| Alle Leitfragen sind beantwortet _(0.5 pro Frage)_           |      6 |
| Die Antworten sind Tiefgründig und **kritisch** hinterfragt. |      4 |
| ...                                                          |        |
| **TOTAL**                                                    | **10** |

:::caution Achtung!

- Die Reflexionen müssen auf **alle** Leitfragen eingehen.
- Die Antworten sollen auch **kritisch** hinterfragen!
  - "Wir waren alle super und die Kommunikation war toll", ist keine wirkliche
    Reflexion!
- Die Antworten sollen auf das **wieso** eingehen und nicht einfach behaupten.
  **Ohne Begründung, kein Punkt für die Frage.**

:::

### Wo wird die Reflexion geschrieben?

- Für jede Reflexion pro Person soll ein `GitHub Issue` erstellt werden.
- Die Reflexion soll als `markdown`-Datei unter Ihrem Nachnamen im Ordner
  `/docs` geschrieben werden.
- Für jede Reflexion wird ein Branch `docs/reflexion-ihr-nachname` erstellt.
- Es wird ein Pull-Request erstellt und mir `@codingluke` als Reviewer
  zugewiesen.
- Nach dem mergen, soll der Branch `docs/reflexion-ihr-nachname` wieder gelöscht
  werden.
- Die Commit-Message soll folgendermassen heissen.
  - `docs(ihr-nachname): Reflexion Sprint 2`

:::tip Beispieldatei: `/docs/hodel/reflexion-sprint2.md`

```markdown
# Hodel - Reflexion Sprint 2

## Welche verschiedenen Themen beinhaltete der Sprint?

lorem ipsum...

## Sind diese Themen zum Zeitpunkt im Projekt gut gewählt, wenn ja, wieso?

lorem ipsum...

...
```

:::

:::info Wieso so kompliziert?

1. Ihr wendet direkt Prinzipien von Git und GitHub an
2. Ich habe dich Möglichkeit im Pull-Request einzelne Zeilen zu kommentieren

:::

### Leitfragen

:::danger nicht ganz gleich zum LB1!

:::

#### Inhalt

- [x] Welche verschiedenen Themen beinhaltete der Sprint?
- [x] Sind diese Themen zum Zeitpunkt im Projekt gut gewählt, wenn ja, wieso?
- [x] Was wurde in diesem Sprint erreicht?
- [x] Was wurde in diesem Sprint nicht erreicht?

#### Gruppendynamik

- [x] Wie war die Zusammenarbeit im Team?
- [x] Auf was achtet Ihr bei der Kommunikation, damit diese Konstruktiv ist?
- [x] Was ist **uns** besonders gut gelungen, worauf sind alle richtig stolz?

#### Lernzuwachs

- [x] Was kann ich nun mehr als vorher?
- [x] Dieses Thema vom Sprint ist besonders relevant?, Begründen Sie?
- [x] Was ist **mir** besonders gut gelungen, worauf bin ich richtig stolz?

#### Lerneffekt

- [x] Was sollte beibehalten werden?
- [x] Was sollte geändert werden?

## Teilnote: Arbeitsvorgang

Am **Ende des Sprint 2** wird der **Arbeitsvorgang der Gruppe** analysiert und
bewertet.

| Sozialform           | Form              | Abgabe  |     Gewicht |
| :------------------- | :---------------- | :-----: | ----------: |
| 👬 **Gruppenarbeit** | 👷 Arbeitsvorgang | Woche 4 | 40% vom LB1 |

:::danger Achtung Kollektivnote!

- 👮 Bitte kontrolliert euch selbst, dass alle sich an die Vorgaben halten.
- 💡 Diese Note ist bewusst nicht individuell, damit die Gruppe sich
  zusammenrauft.

:::

### Bewertung

| Thema                                                                                                                         | Punkte |
| :---------------------------------------------------------------------------------------------------------------------------- | :----: |
| **Issues** sind **klar und verständlich** beschrieben                                                                         |   1    |
| **Issues** beinhalten eine **Definion of Done**                                                                               |   1    |
| **Geschlossene Issues** sind an einen **Pull Request geknüpft**                                                               |   1    |
| **Geschlossene Issues** erfüllen die **Definition of Done**                                                                   |   1    |
| **Pull Requests** besitzen eine **Berschreibung** (oder eine Referenz in der Beschreibung, auf den Issue den Ihn beschreibt). |   1    |
| **Pull Requests** sind **konstruktiv** kommentiert (auch Code!)                                                               |   2    |
| **Pull Requests** beziehen sich **genau auf einen** Issue                                                                     |   1    |
| **Commits** sind anhand **conventional-commits** geschrieben                                                                  |   1    |
| **Commits** beschreiben den **Inhalt** kurz (und nicht die Datei die geändert wurde)                                          |   1    |
| ...                                                                                                                           |        |
| **TOTAL**                                                                                                                     | **10** |
