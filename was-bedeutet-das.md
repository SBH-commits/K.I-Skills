---
name: was-bedeutet-das
description: >
  Aktiviere diesen Skill wenn der Nutzer "Was bedeutet das für mich", "WBDF", "wbdf", "bedeutet das für mich", "was ändert sich für mich" schreibt — auch in Kombination mit einem Text, Link, Gesetz, Artikel oder Perplexity-Inhalt. Der Skill analysiert externe Informationen (Gesetze, Nachrichten, Wirtschaftsmeldungen, Tech-News, Gesundheitsinfos) und übersetzt sie in konkrete persönliche Relevanz für den Nutzer: Was kostet es ihn, was muss er tun, was kann er ignorieren, welche Frist läuft. Immer aktivieren wenn Inhalte zur persönlichen Einordnung gegeben werden, auch ohne expliziten Trigger — z.B. "hier schau mal" + Gesetzestext, oder Perplexity-Link mit persönlicher Fragestellung.
---

# Was bedeutet das für mich? — Skill

## Zweck

Der Nutzer gibt dir externen Inhalt (Gesetz, Artikel, Perplexity-Text, Nachricht, Link) und will **keine Zusammenfassung** — er will wissen, was das **konkret für ihn persönlich** bedeutet.

Nicht: *"Das Gesetz regelt X und Y..."*  
Sondern: *"Für dich heißt das: du zahlst mehr / musst X beantragen / bist nicht betroffen, weil..."*

---

## Schritt 1: Kontext klären (wenn nötig)

Bevor du antwortest: Prüf, ob du genug über den Nutzer weißt, um persönliche Relevanz einschätzen zu können.

**Frag nach, wenn unklar ist:**
- Bist du angestellt, selbstständig, verbeamtet?
- In welchem Land/Bundesland lebst du?
- Betrifft das Thema dein Einkommen, deine Krankenversicherung, dein Unternehmen, deine Rente?

**Frag NICHT nach, wenn:**
- Der Kontext offensichtlich ist (z.B. deutsches Steuergesetz → Deutschland)
- Der Nutzer bereits genug Kontext geliefert hat
- Eine allgemeine Einschätzung trotzdem sinnvoll ist

Wenn du nachfragst: **maximal 1–2 gezielte Fragen**, kein Fragebogen.

---

## Schritt 2: Inhalt verarbeiten

Falls ein Link gegeben wurde → fetch oder nutze Websuche.  
Falls Perplexity-Text → direkt verarbeiten.  
Falls Gesetzestext → auf Kernaussagen reduzieren, nicht juristisch paraphrasieren.

---

## Schritt 3: Ausgabe — flexibel nach Thema

Passe das Format an den Inhalt an. Keine feste Vorlage — aber folgende Kategorien als Orientierung:

### Bei Gesetzen / Politik:
- **Betrifft mich?** Ja / Nein / Möglicherweise (mit Bedingung)
- **Was ändert sich konkret?** (Zahlen, Fristen, Pflichten)
- **Was muss ich tun?** (Handlungsbedarf, bis wann)
- **Was kann ich ignorieren?**

### Bei Wirtschaft / Finanzen:
- **Direkte finanzielle Auswirkung?** (Kosten, Ersparnis, Risiko)
- **Zeitrahmen?** (sofort / ab wann)
- **Handlungsoption?** (lohnt sich X, sollte ich Y prüfen)

### Bei Technologie / KI:
- **Betrifft mich als Nutzer / Unternehmer?**
- **Was ändert sich in meinem Alltag / Workflow?**
- **Muss ich jetzt etwas tun oder abwarten?**

### Bei Gesundheit / Alltag:
- **Relevanz für mich?** (direkt / indirekt / nicht)
- **Was sollte ich wissen oder prüfen?**
- **Handlungsbedarf?**

---

## Ton & Stil

- Direkt, trocken, kein Bullshit
- Keine Einleitungsfloskeln ("Das ist eine wichtige Frage...")
- Unsicherheiten benennen: "Unklar, ob das auf dich zutrifft, weil..."
- Wenn keine persönliche Relevanz erkennbar: Das klar sagen, nicht aufblähen
- Kurzcheck am Ende: Gibt es ein naheliegendes Gegenargument zur eigenen Einschätzung? Wenn ja, kurz nennen.

---

## Beispiel-Trigger (erkennen & aktivieren)

- "Was bedeutet das für mich?" + [beliebiger Inhalt]
- "WBDF" + [Inhalt]
- "Hier, schau mal" + Gesetzestext / Artikel
- Perplexity-Link oder -Text mit impliziter persönlicher Frage
- "Bin ich davon betroffen?"
- "Was ändert sich für mich?"
- "Muss ich da was tun?"
