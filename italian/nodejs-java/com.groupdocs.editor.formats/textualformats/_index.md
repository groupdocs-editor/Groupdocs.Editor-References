---
title: "TextualFormats"
second_title: "Riferimento API di GroupDocs.Editor per Node.js via Java"
description: "Incapsula tutti i formati basati su testo, inclusi markup XML, HTML e altri."
type: docs
weight: 16
url: /it/nodejs-java/com.groupdocs.editor.formats/textualformats/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.formats.abstraction.FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase), [com.groupdocs.editor.formats.abstraction.DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase)
```
public class TextualFormats extends DocumentFormatBase
```

Incapsula tutti i formati testuali (basati su testo), inclusi markup (XML, HTML) e altri.
Include i seguenti formati:
[Html](../../com.groupdocs.editor.formats/textualformats#Html),
[Txt](../../com.groupdocs.editor.formats/textualformats#Txt),
[Xml](../../com.groupdocs.editor.formats/textualformats#Xml).
[Md](../../com.groupdocs.editor.formats/textualformats#Md),
[Json](../../com.groupdocs.editor.formats/textualformats#Json).

## Campi

| Campo | Descrizione |
| --- | --- |
|  | [Html](#Html) | Il documento HyperText Markup Language (HTML) è l'estensione per le pagine web create per la visualizzazione nei browser. |
|
|  | [Xml](#Xml) | Il documento eXtensible Markup Language (XML) è simile a HTML ma differente nell'uso dei tag per definire gli oggetti. |
|
|  | [Txt](#Txt) | Il documento Plain Text (TXT) rappresenta un documento di testo che contiene testo semplice sotto forma di righe. |
|
|  | [Md](#Md) | Markdown è un linguaggio di markup leggero per creare testo formattato usando un editor di testo semplice. |
|
|  | [Json](#Json) | JSON (JavaScript Object Notation) è un formato di file standard aperto per la condivisione di dati che utilizza testo leggibile dall'uomo per memorizzare e trasmettere i dati. |
|
|  | [Mhtml](#Mhtml) | L'incapsulamento MIME di documenti HTML aggregati è un formato di archivio di pagine web utilizzato per combinare, in un unico file informatico, il codice HTML e le sue risorse associate. |
|
|  | [Chm](#Chm) | Microsoft Compiled HTML Help è un formato binario di aiuto online proprietario di Microsoft, costituito da una raccolta di pagine HTML, un indice e altri strumenti di navigazione. |
|
## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [getAll()](#getAll--) | Ottiene una collezione enumerabile di tutti i [TextualFormats](../../com.groupdocs.editor.formats/textualformats). |
|
|  | [fromExtension(String extension)](#fromExtension-java.lang.String-) | Recupera un'istanza del tipo specificato [TextualFormats](../../com.groupdocs.editor.formats/textualformats) che ha l'estensione file specificata. |
|
|  | [fromString(String extension)](#fromString-java.lang.String-) | Converte una stringa che rappresenta un'estensione di file in un oggetto [TextualFormats](../../com.groupdocs.editor.formats/textualformats). |
|
### Html {#Html}
```
public static final TextualFormats Html
```


Il documento HyperText Markup Language (HTML) è l'estensione per le pagine web create per la visualizzazione nei browser.
Scopri di più su questo formato di file
[here](../https://wiki.fileformat.com/web/html)
.


### Xml {#Xml}
```
public static final TextualFormats Xml
```


Il documento eXtensible Markup Language (XML) è simile a HTML ma differente nell'uso dei tag per definire gli oggetti.
Scopri di più su questo formato di file
[here](../https://wiki.fileformat.com/web/xml)
.


### Txt {#Txt}
```
public static final TextualFormats Txt
```


Il documento Plain Text (TXT) rappresenta un documento di testo che contiene testo semplice sotto forma di righe.
Scopri di più su questo formato di file
[here](../https://wiki.fileformat.com/word-processing/txt)
.


### Md {#Md}
```
public static final TextualFormats Md
```


Markdown è un linguaggio di markup leggero per creare testo formattato usando un editor di testo semplice.
Scopri di più su questo formato di file
[here](../https://docs.fileformat.com/word-processing/md/)
.


### Json {#Json}
```
public static final TextualFormats Json
```


JSON (JavaScript Object Notation) è un formato di file standard aperto per la condivisione di dati che utilizza testo leggibile dall'uomo per memorizzare e trasmettere i dati.
Scopri di più su questo formato di file
[here](../https://docs.fileformat.com/web/json/)
.


### Mhtml {#Mhtml}
```
public static final TextualFormats Mhtml
```


L'incapsulamento MIME di documenti HTML aggregati è un formato di archivio di pagine web utilizzato per combinare, in un unico file informatico, il codice HTML e le sue risorse associate.
Scopri di più su questo formato di file
[here](../https://docs.fileformat.com/web/mhtml/)
.


### Chm {#Chm}
```
public static final TextualFormats Chm
```


Microsoft Compiled HTML Help è un formato binario di aiuto online proprietario di Microsoft, costituito da una raccolta di pagine HTML, un indice e altri strumenti di navigazione.
Scopri di più su questo formato di file
[here](../https://docs.fileformat.com/web/chm/)
.


### getAll() {#getAll--}
```
public static List<TextualFormats> getAll()
```


Ottiene una collezione enumerabile di tutti i [TextualFormats](../../com.groupdocs.editor.formats/textualformats).
Valore: Un  IEnumerable{TextualFormats}  contenente tutte le istanze di [TextualFormats](../../com.groupdocs.editor.formats/textualformats).


**Returns:**
java.util.List<com.groupdocs.editor.formats.TextualFormats>
### fromExtension(String extension) {#fromExtension-java.lang.String-}
```
public static TextualFormats fromExtension(String extension)
```


Recupera un'istanza del tipo specificato [TextualFormats](../../com.groupdocs.editor.formats/textualformats) che ha l'estensione file specificata.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | estensione | java.lang.String | L'estensione del file del formato del documento. |
|

**Returns:**
[TextualFormats](../../com.groupdocs.editor.formats/textualformats) - An instance of the specified type [TextualFormats](../../com.groupdocs.editor.formats/textualformats) with the specified file extension.

### fromString(String extension) {#fromString-java.lang.String-}
```
public static TextualFormats fromString(String extension)
```


Converte una stringa che rappresenta un'estensione di file in un oggetto [TextualFormats](../../com.groupdocs.editor.formats/textualformats).


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | estensione | java.lang.String | L'estensione del file da convertire. Se l'estensione contiene più punti, viene utilizzata la parte dopo l'ultimo punto. |
|

**Returns:**
[TextualFormats](../../com.groupdocs.editor.formats/textualformats) - A [TextualFormats](../../com.groupdocs.editor.formats/textualformats) object corresponding to the specified file extension.

