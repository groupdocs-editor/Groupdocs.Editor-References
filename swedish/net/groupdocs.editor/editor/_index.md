---
title: Editor
second_title: GroupDocs.Editor för .NET API-referens
description: Main class som kapslar in konverteringsmetoder. Editor class tillhandahåller metoder för att ladda redigera och spara dokument i alla format som stöds. Det är disponibelt så använd ett usingdirektiv eller kassera dess resurser manuellt via Dispose metodanrop. Dokumentladdning utförs genom konstruktörer. Dokumentredigering  genom metoden Redigera och spara tillbaka till det resulterande dokumentet efter redigering  genom metoden Spara.
type: docs
weight: 20
url: /sv/net/groupdocs.editor/editor/
---
## Editor class

Main class, som kapslar in konverteringsmetoder. Editor class tillhandahåller metoder för att ladda, redigera och spara dokument i alla format som stöds. Det är disponibelt, så använd ett "using"-direktiv eller kassera dess resurser manuellt via 'Dispose()' metodanrop. Dokumentladdning utförs genom konstruktörer. Dokumentredigering - genom metoden 'Redigera', och spara tillbaka till det resulterande dokumentet efter redigering - genom metoden 'Spara'.

```csharp
public sealed class Editor : IAuxDisposable
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [Editor](editor#constructor)(Func&lt;Stream&gt;) | Initierar ny Editor-instans med specificerat indatadokument (som en ström) |
| [Editor](editor#constructor_2)(string) | Initierar ny Editor-instans med specificerat indatadokument (som en fullständig sökväg) |
| [Editor](editor#constructor_1)(Func&lt;Stream&gt;, Func&lt;ILoadOptions&gt;) | Initierar ny Editor-instans med specificerat indatadokument (som en ström) med dess laddningsalternativ |
| [Editor](editor#constructor_3)(string, Func&lt;ILoadOptions&gt;) | Initierar ny Editor-instans med specificerat indatadokument (som en fullständig filsökväg) med dess laddningsalternativ |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [IsDisposed](../../groupdocs.editor/editor/isdisposed) { get; } | Indikerar om den här Editor-instansen redan har kasserats och inte kan användas längre (true) eller om den inte har kasserats ännu och därför är aktiv (false) |

## Metoder

| namn | Beskrivning |
| --- | --- |
| [Dispose](../../groupdocs.editor/editor/dispose)() | Kasserar den här instansen av Editor, så att den frigör alla interna resurser och blir otillgänglig för vidare användning |
| [Edit](../../groupdocs.editor/editor/edit#edit)() | Öppnar ett tidigare laddat dokument för redigering med standardalternativ genom att generera och returnera en instans av '[`EditableDocument`](../editabledocument) klass, som i sin tur innehåller metoder för att producera HTML-uppmärkning och tillhörande resurser. |
| [Edit](../../groupdocs.editor/editor/edit#edit_1)(IEditOptions) | Öppnar ett tidigare laddat dokument för redigering med angivna formatspecifika alternativ genom att generera och returnera en instans av '[`EditableDocument`](../editabledocument) klass, som i sin tur innehåller metoder för att producera HTML-uppmärkning och tillhörande resurser. |
| [GetDocumentInfo](../../groupdocs.editor/editor/getdocumentinfo)(string) | Returnerar metadata om dokumentet som laddades till denna "Editor"-instans |
| [Save](../../groupdocs.editor/editor/save#save)(EditableDocument, Stream, ISaveOptions) | Konverterar specificerat redigerat dokument, representerat som instans av '[`EditableDocument`](../editabledocument) , till det resulterande dokumentet av specificerat format och sparar dess innehåll till specificerad stream |
| [Save](../../groupdocs.editor/editor/save#save_1)(EditableDocument, string, ISaveOptions) | Konverterar specificerat redigerat dokument, representerat som instans av '[`EditableDocument`](../editabledocument) , till det resulterande dokumentet av angivet format och sparar dess innehåll till fil med angiven fil path |

## evenemang

| namn | Beskrivning |
| --- | --- |
| event [Disposed](../../groupdocs.editor/editor/disposed) | Händelse, som inträffar när den här Editor-instansen kasseras med alla dess interna resurser |

### Anmärkningar

Editor-klassen bör betraktas som en ingångspunkt och rotobjektet för GroupDocs.Editor. Alla operationer utförs med denna klass. Typisk användning av Editor-klassen för att utföra en fullständig dokumentredigeringspipeline är nästa:

1. Ladda ett dokument i Editor-instansen genom dess konstruktor.
2. Alternativt kan du hitta en dokumenttyp med hjälp av en[`GetDocumentInfo`](./getdocumentinfo) metod.
3. Öppna ett dokument för redigering genom att anropa en[`Edit`](./edit) metod och få en instans av[`EditableDocument`](../editabledocument) klass från det.
4. Redigera ett dokumentinnehåll på klientsidan med valfri WYSIWYG HTML-redigerare.
5. Skapa en ny instans av[`EditableDocument`](../editabledocument) från redigerat dokumentinnehåll.
6. Spara ett redigerat dokument till något utdataformat genom att anropa a[`Save`](./save) metod.
7. Avyttra en instans av Editor-klassen genom att använda operatorn eller manuellt.

### Se även

* interface [IAuxDisposable](../../groupdocs.editor.htmlcss.resources/iauxdisposable)
* namnutrymme [GroupDocs.Editor](../../groupdocs.editor)
* hopsättning [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->
