---
title: "FixedLayoutFormats"
second_title: "Riferimento API di GroupDocs.Editor per Node.js via Java"
description: "Incapsula tutti i formati a layout fisso, noti anche come formati a pagina fissa, che includono PDF e XPS; questo non include immagini raster."
type: docs
weight: 12
url: /it/nodejs-java/com.groupdocs.editor.formats/fixedlayoutformats/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.formats.abstraction.FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase), [com.groupdocs.editor.formats.abstraction.DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase)
```
public class FixedLayoutFormats extends DocumentFormatBase
```

Incapsula tutti i formati a layout fisso (conosciuti anche come "fixed-page"), che includono PDF e XPS (questi non includono immagini raster)

<br />

*** ** * ** ***

Vari applicazioni di visualizzazione o pubblicazione di documenti consentono agli utenti di aprire (Adobe Acrobat, XPS Viewer) e talvolta modificare (Adobe InDesign) documenti di formati specifici. Queste applicazioni tipicamente producono i cosiddetti \\u201cfixed-page\\u201d documenti di formato. Tale formato di documento descrive con precisione dove il contenuto di un documento\\u2019s è posizionato su ogni pagina. Internamente, il formato PDF o XPS contiene una descrizione di ogni pagina, nonché istruzioni di disegno, specificando il layout del contenuto sulla pagina. Questo è simile ai formati immagine, descrivendo dove il contenuto è mostrato sia in forma raster che vettoriale.

<br />


## Campi

| Campo | Descrizione |
| --- | --- |
|  | [Pdf](#Pdf) | Il Portable Document Format (PDF) è un tipo di documento creato da Adobe negli anni '90. |
|
## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [getAll()](#getAll--) | Ottiene una collezione enumerabile di tutti i [FixedLayoutFormats](../../com.groupdocs.editor.formats/fixedlayoutformats). |
|
|  | [fromExtension(String extension)](#fromExtension-java.lang.String-) | Recupera un'istanza del tipo specificato [FixedLayoutFormats](../../com.groupdocs.editor.formats/fixedlayoutformats) che ha l'estensione file specificata. |
|
|  | [fromString(String extension)](#fromString-java.lang.String-) | Converte una stringa che rappresenta un'estensione di file in un oggetto [FixedLayoutFormats](../../com.groupdocs.editor.formats/fixedlayoutformats). |
|
### Pdf {#Pdf}
```
public static final FixedLayoutFormats Pdf
```


Il Portable Document Format (PDF) è un tipo di documento creato da Adobe negli anni '90. Lo scopo di questo formato file era introdurre uno standard per la rappresentazione di documenti e altri materiali di riferimento in un formato indipendente dal software applicativo, dall'hardware e dal sistema operativo.
Scopri di più su questo formato di file
[here](../https://docs.fileformat.com/pdf/)
.


### getAll() {#getAll--}
```
public static List<FixedLayoutFormats> getAll()
```


Ottiene una collezione enumerabile di tutti i [FixedLayoutFormats](../../com.groupdocs.editor.formats/fixedlayoutformats).
Valore: Un IEnumerable{FixedLayoutFormats} contenente tutte le istanze di [FixedLayoutFormats](../../com.groupdocs.editor.formats/fixedlayoutformats).


**Returns:**
java.util.List<com.groupdocs.editor.formats.FixedLayoutFormats>
### fromExtension(String extension) {#fromExtension-java.lang.String-}
```
public static FixedLayoutFormats fromExtension(String extension)
```


Recupera un'istanza del tipo specificato [FixedLayoutFormats](../../com.groupdocs.editor.formats/fixedlayoutformats) che ha l'estensione file specificata.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | estensione | java.lang.String | L'estensione del file del formato del documento. |
|

**Returns:**
[FixedLayoutFormats](../../com.groupdocs.editor.formats/fixedlayoutformats) - An instance of the specified type [FixedLayoutFormats](../../com.groupdocs.editor.formats/fixedlayoutformats) with the specified file extension.

### fromString(String extension) {#fromString-java.lang.String-}
```
public static FixedLayoutFormats fromString(String extension)
```


Converte una stringa che rappresenta un'estensione di file in un oggetto [FixedLayoutFormats](../../com.groupdocs.editor.formats/fixedlayoutformats).


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | estensione | java.lang.String | L'estensione del file da convertire. Se l'estensione contiene più punti, viene utilizzata la parte dopo l'ultimo punto. |
|

**Returns:**
[FixedLayoutFormats](../../com.groupdocs.editor.formats/fixedlayoutformats) - A [FixedLayoutFormats](../../com.groupdocs.editor.formats/fixedlayoutformats) object corresponding to the specified file extension.

