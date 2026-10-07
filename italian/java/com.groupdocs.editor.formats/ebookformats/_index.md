---
title: "EBookFormats"
second_title: "GroupDocs.Editor per Java Riferimento API"
description: "Incapsula tutti i formati eBook."
type: docs
weight: 10
url: /it/java/com.groupdocs.editor.formats/ebookformats/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.formats.abstraction.FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase), [com.groupdocs.editor.formats.abstraction.DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase)
```
public class EBookFormats extends DocumentFormatBase
```

Incapsula tutti i formati eBook. Include i seguenti tipi di file:
[Mobi](../../com.groupdocs.editor.formats/ebookformats#Mobi),
[Epub](../../com.groupdocs.editor.formats/ebookformats#Epub)
Maggiori informazioni sul formato Mobi [qui](../https://docs.fileformat.com/ebook/mobi/), e sul formato ePub [qui](../https://docs.fileformat.com/ebook/epub/).

## Campi

| Campo | Descrizione |
| --- | --- |
|  | [Mobi](#Mobi) | MOBI è il nome attribuito al formato sviluppato per il lettore MobiPocket. |
|
|  | [Epub](#Epub) | Il formato Electronic Publication (IDPF ePub) è un formato di file e-book che fornisce un formato di pubblicazione digitale standard per editori e consumatori. |
|
|  | [Azw3](#Azw3) | AZW3, noto anche come Kindle Format 8 (KF8), è la versione modificata del formato di file digitale AZW per ebook sviluppato per i dispositivi Amazon Kindle. |
|
## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [getAll()](#getAll--) | Ottiene una collezione enumerabile di tutti i [EBookFormats](../../com.groupdocs.editor.formats/ebookformats). |
|
|  | [fromExtension(String extension)](#fromExtension-java.lang.String-) | Recupera un'istanza del tipo specificato [EBookFormats](../../com.groupdocs.editor.formats/ebookformats) che ha l'estensione di file specificata. |
|
|  | [fromString(String extension)](#fromString-java.lang.String-) | Converte una stringa che rappresenta un'estensione di file in un oggetto [EBookFormats](../../com.groupdocs.editor.formats/ebookformats). |
|
### Mobi {#Mobi}
```
public static final EBookFormats Mobi
```


MOBI è il nome attribuito al formato sviluppato per il lettore MobiPocket. È anche chiamato PRC, AZW.
È attualmente utilizzato da Amazon con uno schema DRM leggermente diverso ed è chiamato AZW.
Maggiori informazioni su questo formato di file
[here](../https://docs.fileformat.com/ebook/mobi/)
.


### Epub {#Epub}
```
public static final EBookFormats Epub
```


Il formato Electronic Publication (IDPF ePub) è un formato di file e-book che fornisce un formato di pubblicazione digitale standard per editori e consumatori.
Maggiori informazioni su questo formato di file
[here](../https://docs.fileformat.com/ebook/epub/)
.


### Azw3 {#Azw3}
```
public static final EBookFormats Azw3
```


AZW3, noto anche come Kindle Format 8 (KF8), è la versione modificata del formato di file digitale AZW per ebook sviluppato per i dispositivi Amazon Kindle.
Il formato è un miglioramento rispetto ai vecchi file AZW.
Maggiori informazioni su questo formato di file
[here](../https://docs.fileformat.com/ebook/azw3/)
.


### getAll() {#getAll--}
```
public static List<EBookFormats> getAll()
```


Ottiene una collezione enumerabile di tutti i [EBookFormats](../../com.groupdocs.editor.formats/ebookformats).
Valore: Un IEnumerable{EBookFormats} contenente tutte le istanze di [EBookFormats](../../com.groupdocs.editor.formats/ebookformats).


**Returns:**
java.util.List<com.groupdocs.editor.formats.EBookFormats>
### fromExtension(String extension) {#fromExtension-java.lang.String-}
```
public static EBookFormats fromExtension(String extension)
```


Recupera un'istanza del tipo specificato [EBookFormats](../../com.groupdocs.editor.formats/ebookformats) che ha l'estensione di file specificata.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | estensione | java.lang.String | L'estensione del file del formato del documento. |
|

**Returns:**
[EBookFormats](../../com.groupdocs.editor.formats/ebookformats) - An instance of the specified type [EBookFormats](../../com.groupdocs.editor.formats/ebookformats) with the specified file extension.

### fromString(String extension) {#fromString-java.lang.String-}
```
public static EBookFormats fromString(String extension)
```


Converte una stringa che rappresenta un'estensione di file in un oggetto [EBookFormats](../../com.groupdocs.editor.formats/ebookformats).


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | estensione | java.lang.String | L'estensione del file da convertire. Se l'estensione contiene più punti, viene utilizzata la parte dopo l'ultimo punto. |
|

**Returns:**
[EBookFormats](../../com.groupdocs.editor.formats/ebookformats) - A [EBookFormats](../../com.groupdocs.editor.formats/ebookformats) object corresponding to the specified file extension.

