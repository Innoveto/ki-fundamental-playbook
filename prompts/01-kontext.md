# Prompts: Kontext schlägt Prompt

[← Prompt-Sammlung](README.md) | [← Zum Rezept](../rezepte/01-kontext-schlaegt-prompt.md)

---

> Alle Prompts zum Kopieren und Anpassen.

## Schritt 1: Ohne Kontext (zum Vergleich)

**Wofür:** Zeigt, was passiert, wenn man AI ohne Kontext fragt
**Tool:** Claude Free
**Was du bekommst:** Eine generische Antwort, die auf jedes Unternehmen passen könnte

```
Du bist ein erfahrener Marketing-Stratege. Erstelle eine Kommunikationsstrategie für ein mittelständisches Unternehmen. Verwende das AIDA-Modell. Formatiere als Bullet Points. Sei konkret und praxisnah.
```

> [!NOTE]
> Merk dir das Ergebnis. Du wirst es gleich mit dem Kontext-Ansatz vergleichen.

## Schritt 2: Dokument hochladen

**Wofür:** Claude bekommt echten Kontext über dein Unternehmen
**Tool:** Claude Free

1. Klicke auf das Büroklammer-Symbol im Chat
2. Wähle ein eigenes Dokument (Briefing, Strategie, Produktbeschreibung)
3. Falls du kein Dokument hast: Kopiere deine Firmen-URL in den Chat

Dann schreib einfach:

```
Was wäre eine passende Kommunikationsstrategie für das nächste Quartal?
```

**Was du bekommst:** Eine spezifische Antwort, die direkt auf dein Unternehmen zugeschnitten ist. Vergleiche mit dem Ergebnis aus Schritt 1.

## Schritt 3: Kontext prüfen

**Wofür:** Sicherstellen, dass Claude dein Dokument richtig verstanden hat
**Tool:** Claude Free

```
Fass zusammen, was du über mein Unternehmen weisst. Was ist unser Kernprodukt, wer ist unsere Zielgruppe, und was unterscheidet uns von der Konkurrenz?
```

**Was du bekommst:** Eine Zusammenfassung in Claudes eigenen Worten. Stimmt etwas nicht, kannst du es korrigieren.

## Schritt 4: Projekt anlegen (für den ganzen Kurs)

**Wofür:** Deinen Kontext dauerhaft speichern, damit du ihn nicht in jedem Chat neu eingeben musst
**Tool:** Claude Free (Projekte)

1. Klicke links auf "Projekte" und dann auf "Neues Projekt"
2. Gib dem Projekt einen Namen (z.B. dein Startup-Name)
3. Unter "Projektanweisungen" fügst du deinen Kontext ein:

```
Mein Startup:
- Name: [STARTUP-NAME]
- Produkt: [WAS BIETEST DU AN]
- Zielgruppe: [WER SOLL DAS KAUFEN]
- Problem: [WELCHES PROBLEM LÖST DU]
- Tonalität: [WIE SOLL DIE KOMMUNIKATION KLINGEN]
```

4. Klicke auf "Projekt erstellen"
5. Ab jetzt startest du jeden neuen Chat innerhalb dieses Projekts

> [!TIP]
> Dieses Projekt begleitet dich durch den ganzen Kurs. Alles, was du in den Projektanweisungen hinterlegst, kennt Claude automatisch in jedem neuen Chat.
