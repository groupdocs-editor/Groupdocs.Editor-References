---
title: RasterImageResourceBase
second_title: GroupDocs.Editor per Riferimento API .NET
description: Classe base per qualsiasi immagine raster supportata con nome dimensioni proporzioni tipo dimensione e contenuto fissi.
type: docs
weight: 550
url: /it/net/groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/
---
## RasterImageResourceBase class

Classe base per qualsiasi immagine raster supportata con nome, dimensioni, proporzioni, tipo, dimensione e contenuto fissi.

```csharp
public abstract class RasterImageResourceBase : IImageResource
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [AspectRatio](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/aspectratio) { get; } | Restituisce le proporzioni di questa immagine come relazione larghezza-altezza |
| [ByteContent](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/bytecontent) { get; } | Restituisce il contenuto di questa immagine raster come flusso di byte |
| [FilenameWithExtension](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/filenamewithextension) { get; } | Restituisce il nome file corretto di questa immagine raster, composto da nome ed estensione. Teoricamente può differire dal nome. |
| [IsDisposed](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/isdisposed) { get; } | Determina se questa immagine raster è eliminata o meno |
| [Length](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/length) { get; } | Restituisce la lunghezza di questo file immagine raster in byte |
| [LinearDimensions](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/lineardimensions) { get; } | Restituisce le dimensioni lineari di questa immagine raster (larghezza e altezza) |
| [Name](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/name) { get; } | Restituisce il nome di questa immagine raster. Di solito non contiene l'estensione del nome file e teoricamente può differire dal nome file. |
| [TextContent](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/textcontent) { get; } | Restituisce il contenuto di questa immagine raster come stringa con codifica Base64 |
| abstract [Type](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/type) { get; } | Nell'implementazione del tipo dovrebbe restituire informazioni sul tipo dell'immagine raster |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [Dispose](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/dispose)() | Elimina questa immagine raster, eliminandone il contenuto e rendendo la maggior parte dei metodi e delle proprietà non funzionanti |
| [Equals](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/equals#equals)(IHtmlResource) | Controlla questa istanza con l'uguaglianza dei riferimenti specificata. |
| [GenerateBitmap](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/generatebitmap)() | Genera e restituisce una nuova istanza di 'System.Drawing.Bitmap' da questa immagine raster. |
| [ReduceToNewHeight](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/reducetonewheight)(ushort) | Crea e restituisce una nuova risorsa immagine ridotta dello stesso tipo, ma con una nuova altezza ridotta specificata e una larghezza proporzionalmente ridotta. |
| [Save](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/save)(string) | Salva questa immagine raster nel file specificato |

## Eventi

| Nome | Descrizione |
| --- | --- |
| event [Disposed](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/disposed) | Evento che si verifica quando questa immagine raster viene eliminata |

### Guarda anche

* interface [IImageResource](../../groupdocs.editor.htmlcss.resources.images/iimageresource)
* spazio dei nomi [GroupDocs.Editor.HtmlCss.Resources.Images.Raster](../../groupdocs.editor.htmlcss.resources.images.raster)
* assemblea [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->
