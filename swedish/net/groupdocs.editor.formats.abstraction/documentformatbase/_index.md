---
title: "DocumentFormatBase"
second_title: "GroupDocs.Editor för .NET API-referens"
description: "Representerar basklassen för dokumentformat som tillhandahåller gemensam funktionalitet för formatinstanser."
type: docs
weight: 50
url: /sv/net/groupdocs.editor.formats.abstraction/documentformatbase/
---
## DocumentFormatBase class

Representerar basklassen för dokumentformat och tillhandahåller gemensam funktionalitet för formatinstanser.

```csharp
public abstract class DocumentFormatBase : FormatFamilyBase, IDocumentFormat
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [Extension](../../groupdocs.editor.formats.abstraction/documentformatbase/extension) { get; } | Hämtar filändelsen för dokumentformatet. |
| [FormatFamily](../../groupdocs.editor.formats.abstraction/documentformatbase/formatfamily) { get; } | Hämtar formatfamiljen som dokumentformatet tillhör. |
| [Id](../../groupdocs.editor.formats.abstraction/formatfamilybase/id) { get; } | Hämtar det unika identifieraren för formatfamiljen. |
| [Mime](../../groupdocs.editor.formats.abstraction/documentformatbase/mime) { get; } | Hämtar MIME-typen för dokumentformatet. |
| [Name](../../groupdocs.editor.formats.abstraction/formatfamilybase/name) { get; } | Hämtar namnet på formatfamiljen. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [Equals](../../groupdocs.editor.formats.abstraction/formatfamilybase/equals)(FormatFamilyBase) | Bestämmer om denna instans är lika med den angivna [`FormatFamilyBase`](../formatfamilybase)-instansen. |
| [Equals](../../groupdocs.editor.formats.abstraction/documentformatbase/equals#equals_1)(IDocumentFormat) | Bestämmer om denna instans är lika med den angivna [`IDocumentFormat`](../idocumentformat)-instansen. |
| override [Equals](../../groupdocs.editor.formats.abstraction/documentformatbase/equals#equals_2)(object) | Bestämmer om denna instans är lika med den angivna [`DocumentFormatBase`](../documentformatbase)-instansen. |
| override [GetHashCode](../../groupdocs.editor.formats.abstraction/documentformatbase/gethashcode)() | Returnerar en hashkod för det aktuella objektet. |
| override [ToString](../../groupdocs.editor.formats.abstraction/formatfamilybase/tostring)() | Returnerar en sträng som representerar det aktuella objektet. |
| static [FromMime&lt;T&gt;](../../groupdocs.editor.formats.abstraction/documentformatbase/frommime)(string) | Hämtar en instans av den angivna typen *T* som har den angivna MIME-typen. |
| [implicit operator](../../groupdocs.editor.formats.abstraction/documentformatbase/op_implicit) | Konverterar en [`DocumentFormatBase`](../documentformatbase)-instans till en sträng implicit. |

### Se även

* class [FormatFamilyBase](../formatfamilybase)
* interface [IDocumentFormat](../idocumentformat)
* namespace [GroupDocs.Editor.Formats.Abstraction](../../groupdocs.editor.formats.abstraction)
* assembly [GroupDocs.Editor](../../)

<!-- REDIGERA INTE: genererad av xmldocmd för GroupDocs.editor.dll -->
