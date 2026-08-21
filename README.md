# IT-Support Git-Übung

Praxisprojekt zur Übung der wichtigsten Git- und GitHub-Standardbefehle im Kontext des IT-Supports der Musterfirma XYZ.

## Ziel

In diesem Repository werden einfache TXT-Dateien gepflegt (Teamnotiz, Support-Checkliste, Dokumentation, Ticket-Regeln), um den Umgang mit `add`, `commit`, `push`, `branch`, `checkout` und `merge` praktisch zu üben — ohne dass Merge-Konflikte entstehen.

## Enthaltene Dateien

| Datei | Beschreibung |
|---|---|
| `teamnotiz.txt` | Kurze interne Teamnotiz |
| `support-checkliste.txt` | Checkliste für die Bearbeitung von Support-Anfragen |
| `dokumentation.txt` | Dokumentation zur Git-Übung selbst |
| `ticket-regeln.txt` | Regeln für die saubere Ticketbearbeitung |

## Verwendeter Workflow

Jede neue Datei bzw. Änderung wurde auf einem eigenen `feature/...`-Branch erstellt, committet und gepusht, bevor sie per Fast-Forward-Merge in `main` übernommen wurde:

- `feature/dokumentation`
- `feature/ticket-regeln`
- `feature/checkliste-erweiterung`

## Autor

Harry — IT-Support Trainee, Sky Education
