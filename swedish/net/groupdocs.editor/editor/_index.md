---
title: "Editor"
second_title: "GroupDocs.Editor för .NET API-referens"
description: "Huvudklassen som kapslar in konverteringsmetoder. Editor-klassen tillhandahåller metoder för att läsa in, redigera och spara dokument i alla stödda format. Den är avyttrbar så använd en using-direktiv eller frigör dess resurser manuellt via Dispose‑metodanrop. Dokumentladdning utförs via konstruktorer. Dokumentredigering sker via metoden Edit och sparas tillbaka till det resulterande dokumentet efter redigering via metoden Save."
type: docs
weight: 20
url: /sv/net/groupdocs.editor/editor/
---
## Editor class

Huvudklassen som kapslar in konverteringsmetoder. Editor‑klassen tillhandahåller metoder för att läsa in, redigera och spara dokument i alla stödda format. Den är avyttrbar, så använd en 'using'-direktiv eller frigör dess resurser manuellt via 'Dispose()'-metodanrop. Dokumentladdning utförs via konstruktorer. Dokumentredigering – via metoden 'Edit', och sparande tillbaka till det resulterande dokumentet efter redigering – via metoden 'Save'.

```csharp
public sealed class Editor : IAuxDisposable
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [Editor](editor#constructor)(DocumentFormatBase) | Initierar en ny instans av klassen [`Editor`](../editor) och skapar ett nytt tomt dokument baserat på det angivna formatet. |
| [Editor](editor#constructor_1)(Stream) | Initierar en ny Editor-instans med angivet inmatningsdokument (som en ström). |
| [Editor](editor#constructor_3)(string) | Initierar en ny Editor-instans med angivet inmatningsdokument (som en fullständig filsökväg) och Editor-inställningar. |
| [Editor](editor#constructor_2)(Stream, ILoadOptions) | Initierar en ny Editor-instans med angivet inmatningsdokument (som en ström) med dess laddningsalternativ. |
| [Editor](editor#constructor_4)(string, ILoadOptions) | Initierar en ny Editor-instans med angivet inmatningsdokument (som en fullständig filsökväg) med dess laddningsalternativ. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [FormFieldManager](../../groupdocs.editor/editor/formfieldmanager) { get; } | Tillhandahåller åtkomst till funktionalitet för att hantera formulärfält i dokumentet. |
| [IsDisposed](../../groupdocs.editor/editor/isdisposed) { get; } | Indikerar om denna Editor-instans redan har frigjorts och inte kan användas längre (true) eller om den ännu inte har frigjorts och därför är aktiv (false). |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [Dispose](../../groupdocs.editor/editor/dispose)() | Frigör denna instans av Editor, så att den släpper alla interna resurser och blir otillgänglig för vidare användning. |
| [Edit](../../groupdocs.editor/editor/edit#edit)() | Öppnar ett tidigare inläst dokument för redigering med standardalternativ genom att skapa och returnera en instans av klassen '[`EditableDocument`](../editabledocument)', som i sin tur innehåller metoder för att producera HTML‑markup och tillhörande resurser. |
| [Edit](../../groupdocs.editor/editor/edit#edit_1)(IEditOptions) | Öppnar ett tidigare inläst dokument för redigering med angivna format‑specifika alternativ genom att skapa och returnera en instans av klassen '[`EditableDocument`](../editabledocument)', som i sin tur innehåller metoder för att producera HTML‑markup och tillhörande resurser. |
| [GetDocumentInfo](../../groupdocs.editor/editor/getdocumentinfo)(string) | Returnerar metadata om dokumentet som laddades till denna 'Editor'-instans. |
| [Save](../../groupdocs.editor/editor/save#save)(Stream) | Spara det aktuella dokumentets innehåll till den angivna utströmmen. |
| [Save](../../groupdocs.editor/editor/save#save_3)(EditableDocument, string) | Konverterar det angivna redigerade dokumentet, representerat som en instans av '[`EditableDocument`](../editabledocument)', till det resulterande dokumentet i format som bestäms av filnamnstillägget, och sparar dess innehåll till en fil på den angivna filsökvägen. |
| [Save](../../groupdocs.editor/editor/save#save_1)(Stream, WordProcessingSaveOptions) | Konverterar det ursprungliga dokumentet efter modifiering (till exempel [`FormFieldManager`](./formfieldmanager)) till det resulterande dokumentet i det angivna formatet och sparar dess innehåll till den tillhandahållna strömmen. |
| [Save](../../groupdocs.editor/editor/save#save_2)(EditableDocument, Stream, ISaveOptions) | Konverterar det angivna redigerade dokumentet, representerat som en instans av '[`EditableDocument`](../editabledocument)', till det resulterande dokumentet i det angivna formatet och sparar dess innehåll till den angivna strömmen. |
| [Save](../../groupdocs.editor/editor/save#save_4)(EditableDocument, string, ISaveOptions) | Konverterar det angivna redigerade dokumentet, representerat som en instans av '[`EditableDocument`](../editabledocument)', till det resulterande dokumentet i angivet format och sparar dess innehåll till en fil på den angivna filsökvägen. |

## Händelser

| Namn | Beskrivning |
| --- | --- |
| event [Disposed](../../groupdocs.editor/editor/disposed) | Händelse som inträffar när denna Editor-instans har frigjorts med alla sina interna resurser. |

### Anmärkningar

Editor-klassen bör betraktas som en ingångspunkt och rotobjektet för GroupDocs.Editor. Alla operationer utförs med hjälp av denna klass. Typisk användning av Editor-klassen för att genomföra en fullständig dokumentredigeringspipeline är följande:

1. Ladda ett dokument i Editor-instansen via dess konstruktor.
2. Eventuellt identifiera en dokumenttyp med hjälp av metoden [`GetDocumentInfo`](./getdocumentinfo).
3. Öppna ett dokument för redigering genom att anropa metoden [`Edit`](./edit) och erhålla en instans av klassen [`EditableDocument`](../editabledocument) från den.
4. Redigera dokumentets innehåll på klientsidan med någon WYSIWYG HTML-editor.
5. Skapa en ny instans av [`EditableDocument`](../editabledocument) från det redigerade dokumentets innehåll.
6. Spara ett redigerat dokument till ett visst utdataformat genom att anropa metoden [`Save`](./save).
7. Frigöra en instans av Editor-klassen via 'using'-operatorn eller manuellt.

### Se även

* interface [IAuxDisposable](../../groupdocs.editor.htmlcss.resources/iauxdisposable)
* namespace [GroupDocs.Editor](../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../)

<!-- REDIGERA INTE: genererad av xmldocmd för GroupDocs.editor.dll -->
