# Rezept 9: Automatisieren

> Tag 2, Block 3

[← Vorheriges Rezept](08-video-und-multimedia.md) | [Zurück zum Playbook](../README.md) | [Nächstes Rezept →](10-prompt-playbook.md)

---

## Kernaussage

AI-Workflows verbinden verschiedene Tools miteinander. Das Konzept ist wichtiger als die Umsetzung: APIs sind die Sprache, mit der Tools miteinander reden.

## Lernziel

Du verstehst das Konzept von AI-Workflows und kannst dir vorstellen, wie du repetitive Aufgaben automatisieren könntest.

## Ablauf

### Demo

Live-Demo eines einfachen Workflows in n8n:

**Beispiel-Flow:** Lead kommt rein > AI schreibt personalisierte Nachricht > Ab ins Postfach zur Freigabe

1. Trigger (z.B. neuer Kontakt)
2. AI-Node: Claude/GPT generiert personalisierten Text
3. Output: Email-Draft oder Slack-Nachricht

### Ausblick

Was kommt als Nächstes:
- **MCPs:** AI verbindet sich direkt mit CRM, Analytics, etc.
- **Agents:** AI die selbstständig Aufgaben erledigt
- **Skills:** Spezialisierte Fähigkeiten, wie Apps für AI

## Tools

- n8n (n8n.io): Workflow-Automation
