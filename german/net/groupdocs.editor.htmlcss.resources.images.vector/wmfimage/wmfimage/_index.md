---
title: WmfImage
second_title: GroupDocs.Editor für .NET-API-Referenz
description: Erstellt eine neue WmfImageInstanz aus Inhalt dargestellt als base64codierte Zeichenfolge und mit dem angegebenen Namen
type: docs
weight: 10
url: /de/net/groupdocs.editor.htmlcss.resources.images.vector/wmfimage/wmfimage/
---
## WmfImage(string, string) {#constructor_1}

Erstellt eine neue WmfImage-Instanz aus Inhalt, dargestellt als base64-codierte Zeichenfolge und mit dem angegebenen Namen

```csharp
public WmfImage(string name, string contentInBase64)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| name | String | Name des WMF-Bildes. Darf nicht null, leer oder Leerzeichen sein. |
| contentInBase64 | String | Inhalt als base64-codierter String. Darf nicht null, leer oder Leerzeichen sein. Wenn es kein WMF-Inhalt ist, wird eine Ausnahme ausgelöst. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentException |  |
| [InvalidImageFormatException](../../../groupdocs.editor.htmlcss.exceptions/invalidimageformatexception) |  |

### Siehe auch

* class [WmfImage](../../wmfimage)
* namensraum [GroupDocs.Editor.HtmlCss.Resources.Images.Vector](../../wmfimage)
* Montage [GroupDocs.Editor](../../../)

---

## WmfImage(string, Stream) {#constructor}

Erstellt eine neue WmfImage-Instanz aus Inhalt, dargestellt als Byte-Stream, und mit dem angegebenen Namen

```csharp
public WmfImage(string name, Stream binaryContent)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| name | String | Name des WMF-Bildes. Darf nicht null, leer oder Leerzeichen sein. |
| binaryContent | Stream | Inhalt als Bytestrom. Das Lesen beginnt an der ursprünglichen Position. Kann nicht Null sein. Sollte lesbar und suchbar sein. Wenn diese Instanz verworfen wird, wird dieser Stream ebenfalls verworfen. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentException |  |
| [InvalidImageFormatException](../../../groupdocs.editor.htmlcss.exceptions/invalidimageformatexception) |  |

### Siehe auch

* class [WmfImage](../../wmfimage)
* namensraum [GroupDocs.Editor.HtmlCss.Resources.Images.Vector](../../wmfimage)
* Montage [GroupDocs.Editor](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->