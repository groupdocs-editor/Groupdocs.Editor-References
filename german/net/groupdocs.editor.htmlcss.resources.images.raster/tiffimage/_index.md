---
title: TiffImage
second_title: GroupDocs.Editor für .NET-API-Referenz
description: Repräsentiert ein Bild im TIFFFormat Tagged Image File Format mit seinen Metadaten und zusätzlichen Methoden
type: docs
weight: 460
url: /de/net/groupdocs.editor.htmlcss.resources.images.raster/tiffimage/
---
## TiffImage class

Repräsentiert ein Bild im TIFF-Format (Tagged Image File Format) mit seinen Metadaten und zusätzlichen Methoden

```csharp
public sealed class TiffImage : RasterImageResourceBase
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [TiffImage](tiffimage#constructor)(string, Stream) | Erstellt eine neue GifImage-Instanz aus Inhalt, dargestellt als Byte-Stream, und mit dem angegebenen Namen |
| [TiffImage](tiffimage#constructor_1)(string, string) | Erstellt eine neue TiffImage-Instanz aus Inhalt, dargestellt als base64-codierte Zeichenfolge und mit dem angegebenen Namen |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [AspectRatio](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/aspectratio) { get; } | Gibt ein Seitenverhältnis dieses Bildes als Verhältnis von Breite zu Höhe zurück |
| [ByteContent](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/bytecontent) { get; } | Gibt den Inhalt dieses Rasterbildes als Bytestream zurück |
| [FilenameWithExtension](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/filenamewithextension) { get; } | Gibt den korrekten Dateinamen dieses Rasterbildes zurück, der sich aus Name und Erweiterung zusammensetzt. Kann theoretisch vom Namen abweichen. |
| [FramesCount](../../groupdocs.editor.htmlcss.resources.images.raster/tiffimage/framescount) { get; } | Gibt eine Anzahl von Frames (Bildern) innerhalb dieses TIFF-Bildes zurück. Darf nicht kleiner als 1. sein |
| [IsDisposed](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/isdisposed) { get; } | Bestimmt, ob dieses Rasterbild verworfen wird oder nicht |
| [Length](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/length) { get; } | Gibt die Länge dieser Rasterbilddatei in Bytes zurück |
| [LinearDimensions](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/lineardimensions) { get; } | Gibt lineare Abmessungen dieses Rasterbildes zurück (Breite und Höhe) |
| [Name](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/name) { get; } | Gibt den Namen dieses Rasterbildes zurück. Enthält normalerweise keine Dateinamenerweiterung und kann theoretisch von Dateiname abweichen. |
| [TextContent](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/textcontent) { get; } | Gibt den Inhalt dieses Rasterbildes als base64-kodierten String zurück |
| override [Type](../../groupdocs.editor.htmlcss.resources.images.raster/tiffimage/type) { get; } | Gibt ImageType.Tiff zurück |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [Dispose](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/dispose)() | Löscht dieses Rasterbild, löscht seinen Inhalt und macht die meisten Methoden und Eigenschaften nicht funktionsfähig |
| [Equals](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/equals)(IHtmlResource) | Prüft diese Instanz mit Angabe auf Referenzgleichheit. |
| [GenerateBitmap](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/generatebitmap)() | Erzeugt und gibt eine neue Instanz der 'System.Drawing.Bitmap' aus diesem Rasterbild zurück. |
| [ReduceToNewHeight](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/reducetonewheight)(ushort) | Erstellt und gibt eine neue reduzierte Bildressource desselben Typs zurück, jedoch mit der angegebenen neuen reduzierten Höhe und proportional reduzierten Breite. |
| [Save](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/save)(string) | Speichert dieses Rasterbild in der angegebenen Datei |
| static [IsValid](../../groupdocs.editor.htmlcss.resources.images.raster/tiffimage/isvalid#isvalid)(Stream) | Überprüft, ob der angegebene Stream ein gültiges TIFF-Bild ist |
| static [IsValid](../../groupdocs.editor.htmlcss.resources.images.raster/tiffimage/isvalid#isvalid_1)(string) | Überprüft, ob die angegebene base64-codierte Zeichenfolge ein gültiges TIFF-Bild ist |

## Veranstaltungen

| Name | Beschreibung |
| --- | --- |
| event [Disposed](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/disposed) | Ereignis, das eintritt, wenn dieses Rasterbild entsorgt wird |

### Bemerkungen

Siehe https://en.wikipedia.org/wiki/TIFF für Details. In sehr seltenen Fällen ist TIFF in WordProcessing-Dokumenten vorhanden.

### Siehe auch

* class [RasterImageResourceBase](../rasterimageresourcebase)
* namensraum [GroupDocs.Editor.HtmlCss.Resources.Images.Raster](../../groupdocs.editor.htmlcss.resources.images.raster)
* Montage [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->
