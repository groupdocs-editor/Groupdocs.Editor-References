---
title: "FixedLayoutFormats"
second_title: "GroupDocs.Editor för Node.js via Java API-referens"
description: "Innesluter alla fast layout-format, även kända som fast-sidformat, som inkluderar PDF och XPS; detta inkluderar inte rasterbilder."
type: docs
weight: 12
url: /sv/nodejs-java/com.groupdocs.editor.formats/fixedlayoutformats/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.formats.abstraction.FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase), [com.groupdocs.editor.formats.abstraction.DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase)
```
public class FixedLayoutFormats extends DocumentFormatBase
```

Innesluter alla fast‑layout (även känt som \"fixed-page\")-format, som inkluderar PDF och XPS (detta inkluderar inte rasterbilder).

<br />

*** ** * ** ***

Olika dokumentvisnings- eller publiceringsprogram låter användare öppna (Adobe Acrobat, XPS Viewer) och ibland redigera (Adobe InDesign) dokument av specifika format. Dessa program producerar vanligtvis så kallade “fixed-page”-formatdokument. Ett sådant dokumentformat beskriver exakt var ett dokuments innehåll placeras på varje sida. Internt innehåller PDF- eller XPS-formatet en beskrivning av varje sida samt ritinstruktioner som specificerar layouten för innehållet på sidan. Detta liknar bildformat, som beskriver var innehållet visas antingen i raster- eller vektorform.

<br />


## Fält

| Fält | Beskrivning |
| --- | --- |
|  | [Pdf](#Pdf) | Portable Document Format (PDF) är en dokumenttyp som skapades av Adobe på 1990-talet. |
|
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getAll()](#getAll--) | Hämtar en uppräkningssamling av alla [FixedLayoutFormats](../../com.groupdocs.editor.formats/fixedlayoutformats). |
|
|  | [fromExtension(String extension)](#fromExtension-java.lang.String-) | Hämtar en instans av den angivna typen [FixedLayoutFormats](../../com.groupdocs.editor.formats/fixedlayoutformats) som har den angivna filändelsen. |
|
|  | [fromString(String extension)](#fromString-java.lang.String-) | Konverterar en sträng som representerar en filändelse till ett [FixedLayoutFormats](../../com.groupdocs.editor.formats/fixedlayoutformats)-objekt. |
|
### Pdf {#Pdf}
```
public static final FixedLayoutFormats Pdf
```


Portable Document Format (PDF) är en dokumenttyp som skapades av Adobe på 1990-talet. Syftet med detta filformat var att införa en standard för representation av dokument och annat referensmaterial i ett format som är oberoende av programvara, hårdvara samt operativsystem.
Läs mer om detta filformat
[here](../https://docs.fileformat.com/pdf/)
.


### getAll() {#getAll--}
```
public static List<FixedLayoutFormats> getAll()
```


Hämtar en uppräkningssamling av alla [FixedLayoutFormats](../../com.groupdocs.editor.formats/fixedlayoutformats).
Värde: En IEnumerable{FixedLayoutFormats} som innehåller alla instanser av [FixedLayoutFormats](../../com.groupdocs.editor.formats/fixedlayoutformats).


**Returns:**
java.util.List<com.groupdocs.editor.formats.FixedLayoutFormats>
### fromExtension(String extension) {#fromExtension-java.lang.String-}
```
public static FixedLayoutFormats fromExtension(String extension)
```


Hämtar en instans av den angivna typen [FixedLayoutFormats](../../com.groupdocs.editor.formats/fixedlayoutformats) som har den angivna filändelsen.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | filändelse | java.lang.String | Filändelsen för dokumentformatet. |
|

**Returns:**
[FixedLayoutFormats](../../com.groupdocs.editor.formats/fixedlayoutformats) - An instance of the specified type [FixedLayoutFormats](../../com.groupdocs.editor.formats/fixedlayoutformats) with the specified file extension.

### fromString(String extension) {#fromString-java.lang.String-}
```
public static FixedLayoutFormats fromString(String extension)
```


Konverterar en sträng som representerar en filändelse till ett [FixedLayoutFormats](../../com.groupdocs.editor.formats/fixedlayoutformats)-objekt.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | filändelse | java.lang.String | Filändelsen att konvertera. Om filändelsen innehåller flera punkter används delen efter den sista punkten. |
|

**Returns:**
[FixedLayoutFormats](../../com.groupdocs.editor.formats/fixedlayoutformats) - A [FixedLayoutFormats](../../com.groupdocs.editor.formats/fixedlayoutformats) object corresponding to the specified file extension.

