---
title: "GroupDocs.Editor"
second_title: "GroupDocs.Editor för .NET API-referens"
description: "GroupDocs.Editor‑namnutrymmet tillhandahåller klasser för att redigera dokument med tredjeparts‑frontend‑WYSIWYG‑redigerare utan några ytterligare program."
type: docs
weight: 10
url: /sv/net/groupdocs.editor/
---
GroupDocs.Editor-namnrymden tillhandahåller klasser för att redigera dokument med hjälp av tredjeparts front-end WYSIWYG-redigerare utan några ytterligare program.

## Klasser

| Klass | Beskrivning |
| --- | --- |
| [EditableDocument](./editabledocument) | Intermediärt dokument som innehåller innehåll före och efter redigering |
| [Editor](./editor) | Huvudklassen som kapslar in konverteringsmetoder. Editor‑klassen tillhandahåller metoder för att läsa in, redigera och spara dokument i alla stödda format. Den är avyttrbar, så använd en 'using'-direktiv eller frigör dess resurser manuellt via 'Dispose()'-metodanrop. Dokumentladdning utförs via konstruktorer. Dokumentredigering – via metoden 'Edit', och sparande tillbaka till det resulterande dokumentet efter redigering – via metoden 'Save'. |
| [EncryptedException](./encryptedexception) | Undantaget som kastas när en användare försöker öppna ett dokument som krypterades med X509Certificates. |
| [FormFieldManager](./formfieldmanager) | Hantera ett formulär med äldre formulärfält. Äldre formulärfält är de fälttyper som fanns i tidigare versioner av ordbehandling. Gruppen Äldre formulär (synlig efter att du klickat på ikonen för Legacy Tools) innehåller tre typer av formulärfält som du kan infoga i ett dokument: text, kryssruta, rullgardin, datum osv., se mer [`FormFieldType`](../groupdocs.editor.words.fieldmanagement/formfieldtype). Varje av dessa formulärfält låter formulärets användare att välja eller ange information av den typ du anser lämplig. |
| [IncorrectPasswordException](./incorrectpasswordexception) | Undantaget som kastas när det angivna lösenordet är felaktigt. |
| [InvalidFormatException](./invalidformatexception) | Undantaget som kastas när en användare försöker öppna ett dokument med format‑specifika alternativ som är inkompatibla med det ursprungliga dokumentformatet. |
| [License](./license) | Tillhandahåller metoder för att licensiera komponenten. Läs mer om licensiering [här](https://purchase.groupdocs.com/faqs/licensing). |
| [Metered](./metered) | Tillhandahåller metoder för att tillämpa [Metered](https://purchase.groupdocs.com/faqs/licensing/metered) licens. |
| [PasswordRequiredException](./passwordrequiredexception) | Undantaget som kastas när en användare försöker öppna ett lösenordsskyddat krypterat dokument av något format och inte anger ett lösenord för att öppna detta dokument. |

<!-- REDIGERA INTE: genererad av xmldocmd för GroupDocs.editor.dll -->
