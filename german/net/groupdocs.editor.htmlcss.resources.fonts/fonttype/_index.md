---
title: FontType
second_title: GroupDocs.Editor für .NET-API-Referenz
description: Stellt eine unterstützte Schriftart dar
type: docs
weight: 280
url: /de/net/groupdocs.editor.htmlcss.resources.fonts/fonttype/
---
## FontType structure

Stellt eine unterstützte Schriftart dar

```csharp
public struct FontType : IEquatable<FontType>, IResourceType
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| static [Eot](../../groupdocs.editor.htmlcss.resources.fonts/fonttype/eot) { get; } | Stellt eine EOT-Schriftart (Embedded OpenType) dar |
| static [Otf](../../groupdocs.editor.htmlcss.resources.fonts/fonttype/otf) { get; } | Stellt eine OTF-Schriftart (OpenType Font) dar |
| static [Ttf](../../groupdocs.editor.htmlcss.resources.fonts/fonttype/ttf) { get; } | Stellt eine TTF-Schriftart (TrueType Font) dar |
| static [Undefined](../../groupdocs.editor.htmlcss.resources.fonts/fonttype/undefined) { get; } | Sonderwert, der eine undefinierte, unbekannte oder nicht unterstützte Schriftart-Ressource markiert |
| static [Woff](../../groupdocs.editor.htmlcss.resources.fonts/fonttype/woff) { get; } | Stellt eine WOFF-Schriftart (Web Open Font Format) dar |
| static [Woff2](../../groupdocs.editor.htmlcss.resources.fonts/fonttype/woff2) { get; } | Stellt eine WOFF2-Schriftart (Web Open Font Format Version 2) dar |
| [CssName](../../groupdocs.editor.htmlcss.resources.fonts/fonttype/cssname) { get; } | Gibt einen CSS-kompatiblen Namen dieser Schriftart zurück, der in @font-face at-rule verwendet wird |
| [FileExtension](../../groupdocs.editor.htmlcss.resources.fonts/fonttype/fileextension) { get; } | Dateinamenerweiterung (ohne Punkt) für diese Schriftart |
| [FontFormat](../../groupdocs.editor.htmlcss.resources.fonts/fonttype/fontformat) { get; } | Schriftformat für @font-face format |
| [FormalName](../../groupdocs.editor.htmlcss.resources.fonts/fonttype/formalname) { get; } | Gibt einen formalen Namen dieser Schriftart zurück |
| [MimeCode](../../groupdocs.editor.htmlcss.resources.fonts/fonttype/mimecode) { get; } | MIME-Code einer bestimmten Schriftart |

## Methoden

| Name | Beschreibung |
| --- | --- |
| static [GetFirstDefined](../../groupdocs.editor.htmlcss.resources.fonts/fonttype/getfirstdefined)(params FontType[]) | Gibt einen ersten Schriftarttyp aus dem angegebenen Satz zurück, der kein „Undefinierter“ Wert ist, oder andernfalls „Undefinierter“ Schriftarttyp (wenn alle Elemente „Undefiniert“ sind) |
| static [ParseFromCssName](../../groupdocs.editor.htmlcss.resources.fonts/fonttype/parsefromcssname)(string) | Gibt den FontType-Wert zurück, der dem angegebenen CSS-kompatiblen Namen des Schriftarttyps entspricht. |
| static [ParseFromFilenameWithExtension](../../groupdocs.editor.htmlcss.resources.fonts/fonttype/parsefromfilenamewithextension)(string) | Gibt den FontType-Wert zurück, der der Dateinamenerweiterung entspricht, die aus dem angegebenen Dateinamen extrahiert wird |
| static [ParseFromMime](../../groupdocs.editor.htmlcss.resources.fonts/fonttype/parsefrommime)(string) | Gibt den FontType-Wert zurück, der dem angegebenen MIME-Code entspricht |
| [Equals](../../groupdocs.editor.htmlcss.resources.fonts/fonttype/equals#equals)(FontType) | Bestimmt, ob diese Instanz gleich dem angegebenen "FontType" ist instance |
| override [Equals](../../groupdocs.editor.htmlcss.resources.fonts/fonttype/equals#equals_1)(object) | Bestimmt, ob diese Instanz gleich dem angegebenen nicht umgewandelten Objekt ist, das vermutlich eine andere "FontType"-Instanz ist |
| override [GetHashCode](../../groupdocs.editor.htmlcss.resources.fonts/fonttype/gethashcode)() | Gibt einen Hash-Code zurück, der eine konstante Zahl für diesen spezifischen Wert ist type |
| [operator ==](../../groupdocs.editor.htmlcss.resources.fonts/fonttype/op_equality) | Überprüft, ob zwei „FontType“-Werte gleich sind |
| [operator !=](../../groupdocs.editor.htmlcss.resources.fonts/fonttype/op_inequality) | Prüft, ob zwei „FontType“-Werte ungleich sind |

### Siehe auch

* interface [IResourceType](../../groupdocs.editor.htmlcss.resources/iresourcetype)
* namensraum [GroupDocs.Editor.HtmlCss.Resources.Fonts](../../groupdocs.editor.htmlcss.resources.fonts)
* Montage [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->