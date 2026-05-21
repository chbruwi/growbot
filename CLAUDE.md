# GrowBot — Grow Media GmbH

Automatisierter Daily-Check für Projektleiter Christian Braunwalder.

## Verwendung

```
/daily-check
```

Führt den vollständigen 18:00-Check durch:
- Scannt alle offenen Tasks von Diego Borellini und Roman Suter
- Klassifiziert: OK / WARN / ESKALATION
- Postet autonom Rückfragen bei WARN/ESKALATION
- Sendet Daily-Report an Christian via ClickUp-Chat

## Setup-Voraussetzungen

- ClickUp MCP-Integration muss in Claude Code aktiv sein
- Workspace-ID: `9012619565`
- Permissions sind in `.claude/settings.json` hinterlegt
