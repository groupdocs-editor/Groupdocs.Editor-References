---
title: WoffFont
second_title: GroupDocs.Editor für .NET-API-Referenz
description: Stellt eine Schriftart im WOFFFormat Web Open Font Format dar
type: docs
weight: 420
url: /de/net/groupdocs.editor.htmlcss.resources.fonts/wofffont/
---
## WoffFont class

Stellt eine Schriftart im WOFF-Format (Web Open Font Format) dar

```csharp
public sealed class WoffFont : FontResourceBase
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [WoffFont](wofffont#constructor)(string, Stream) | Erstellt eine neue WoffFont-Klasse aus Inhalt, dargestellt als Byte-Stream, und mit dem angegebenen Namen |
| [WoffFont](wofffont#constructor_1)(string, string) | Erstellt eine neue WoffFont-Klasse aus Inhalt, dargestellt als base64-codierte Zeichenfolge und mit dem angegebenen Namen |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [ByteContent](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/bytecontent) { get; } | Gibt den Inhalt dieser Schriftart als Bytestream zurück |
| [FilenameWithExtension](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/filenamewithextension) { get; } | Gibt den korrekten Dateinamen dieser Schriftartressource zurück, der aus Name und Erweiterung besteht. Kann theoretisch vom Namen abweichen. |
| [IsDisposed](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/isdisposed) { get; } | Legt fest, ob diese Schriftart entsorgt wird oder nicht |
| [Name](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/name) { get; } | Gibt den Namen dieser Schriftartressource zurück. Enthält normalerweise keine Dateinamenerweiterung und kann theoretisch von Dateiname abweichen. |
| [TextContent](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/textcontent) { get; } | Gibt den Inhalt dieser Schriftart als base64-codierten String zurück. Dieser Wert wird nach dem ersten Aufruf zwischengespeichert. |
| override [Type](../../groupdocs.editor.htmlcss.resources.fonts/wofffont/type) { get; } | Gibt FontType zurück.Woff |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [Dispose](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/dispose)() | Löscht diese Schriftartressource, löscht ihren Inhalt und macht die meisten Methoden und Eigenschaften nicht funktionsfähig |
| [Equals](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/equals)(FontResourceBase) | Prüft diese Instanz mit der angegebenen Schriftartressource auf Referenzgleichheit |
| [Equals](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/equals)(IHtmlResource) | Prüft diese Instanz mit angegebener HTML-Ressource auf Referenzgleichheit |
| [Save](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/save)(string) | Speichert diese Schriftart in der angegebenen Datei |
| static [IsValid](../../groupdocs.editor.htmlcss.resources.fonts/wofffont/isvalid#isvalid)(Stream) | Überprüft, ob der angegebene Stream eine gültige WOFF-Schriftart ist |
| static [IsValid](../../groupdocs.editor.htmlcss.resources.fonts/wofffont/isvalid#isvalid_1)(string) | Überprüft, ob die angegebene base64-codierte Zeichenfolge eine gültige WOFF-Schriftart ist |

## Felder

| Name | Beschreibung |
| --- | --- |
| const [RequiredHeaderSize](../../groupdocs.editor.htmlcss.resources.fonts/wofffont/requiredheadersize) | Größe des WOFF-Headers (in Bytes), die für seine Validierung erforderlich ist |

## Veranstaltungen

| Name | Beschreibung |
| --- | --- |
| event [Disposed](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/disposed) | Ereignis, das eintritt, wenn diese Schriftart entsorgt wird |

### Siehe auch

* class [FontResourceBase](../fontresourcebase)
* namensraum [GroupDocs.Editor.HtmlCss.Resources.Fonts](../../groupdocs.editor.htmlcss.resources.fonts)
* Montage [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->
