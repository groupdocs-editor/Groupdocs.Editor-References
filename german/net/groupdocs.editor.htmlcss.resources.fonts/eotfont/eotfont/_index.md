---
title: EotFont
second_title: GroupDocs.Editor für .NET-API-Referenz
description: Erstellt eine neue EotFontKlasse aus Inhalt dargestellt als base64codierte Zeichenfolge und mit dem angegebenen Namen
type: docs
weight: 10
url: /de/net/groupdocs.editor.htmlcss.resources.fonts/eotfont/eotfont/
---
## EotFont(string, string) {#constructor_1}

Erstellt eine neue EotFont-Klasse aus Inhalt, dargestellt als base64-codierte Zeichenfolge und mit dem angegebenen Namen

```csharp
public EotFont(string name, string contentInBase64)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| name | String | Name der EOT-Schriftart. Darf nicht null, leer oder Leerzeichen sein. |
| contentInBase64 | String | Inhalt als base64-codierter String. Darf nicht null, leer oder Leerzeichen sein. Wenn es kein EOT-Inhalt ist, wird eine Ausnahme ausgelöst. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentException |  |
| [InvalidImageFormatException](../../../groupdocs.editor.htmlcss.exceptions/invalidimageformatexception) |  |

### Siehe auch

* class [EotFont](../../eotfont)
* namensraum [GroupDocs.Editor.HtmlCss.Resources.Fonts](../../eotfont)
* Montage [GroupDocs.Editor](../../../)

---

## EotFont(string, Stream) {#constructor}

Erstellt eine neue EotFont-Klasse aus Inhalt, dargestellt als Byte-Stream, und mit dem angegebenen Namen

```csharp
public EotFont(string name, Stream binaryContent)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| name | String | Name der EOT-Schriftart. Darf nicht null, leer oder Leerzeichen sein. |
| binaryContent | Stream | Inhalt als Bytestream. Das Lesen beginnt an der ursprünglichen Position. Kann nicht Null sein. Sollte lesbar und suchbar sein. Wenn diese Instanz verworfen wird, wird dieser Stream ebenfalls verworfen. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentException |  |
| [InvalidImageFormatException](../../../groupdocs.editor.htmlcss.exceptions/invalidimageformatexception) |  |

### Siehe auch

* class [EotFont](../../eotfont)
* namensraum [GroupDocs.Editor.HtmlCss.Resources.Fonts](../../eotfont)
* Montage [GroupDocs.Editor](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->