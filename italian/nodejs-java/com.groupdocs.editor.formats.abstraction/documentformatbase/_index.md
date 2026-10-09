---
title: "DocumentFormatBase"
second_title: "Riferimento API di GroupDocs.Editor per Node.js via Java"
description: "Rappresenta la classe base per i formati di documento che fornisce funzionalità comuni per le istanze di formato."
type: docs
weight: 10
url: /it/nodejs-java/com.groupdocs.editor.formats.abstraction/documentformatbase/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.formats.abstraction.FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase)

**All Implemented Interfaces:**
[com.groupdocs.editor.formats.abstraction.IDocumentFormat](../../com.groupdocs.editor.formats.abstraction/idocumentformat)
```
public abstract class DocumentFormatBase extends FormatFamilyBase implements IDocumentFormat
```

Rappresenta la classe base per i formati di documento, fornendo funzionalità comuni per le istanze di formato.

## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [getMime()](#getMime--) | Ottiene il tipo MIME del formato di documento. |
|
|  | [getExtension()](#getExtension--) | Ottiene l'estensione del file del formato di documento. |
|
|  | [getFormatFamily()](#getFormatFamily--) | Ottiene la famiglia di formati a cui appartiene il formato del documento. |
|
|  | [<T>fromMime(Class<T> clazz, String mime)](#-T-fromMime-java.lang.Class-T--java.lang.String-) | Recupera un'istanza del tipo specificato |
T
che ha il tipo MIME specificato.
|
|  | [hashCode()](#hashCode--) | Restituisce un codice hash per l'oggetto corrente. |
|
|  | [equals(IDocumentFormat other)](#equals-com.groupdocs.editor.formats.abstraction.IDocumentFormat-) | Determina se questa istanza è uguale all'istanza [IDocumentFormat](../../com.groupdocs.editor.formats.abstraction/idocumentformat) specificata. |
|
|  | [equals(Object obj)](#equals-java.lang.Object-) | Determina se questa istanza è uguale all'istanza [DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase) specificata. |
|
|  | [toString(DocumentFormatBase extension)](#toString-com.groupdocs.editor.formats.abstraction.DocumentFormatBase-) | Converte implicitamente un'istanza [DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase) in una stringa. |
|
### getMime() {#getMime--}
```
public final String getMime()
```


Ottiene il tipo MIME del formato di documento.


**Returns:**
java.lang.String
### getExtension() {#getExtension--}
```
public final String getExtension()
```


Ottiene l'estensione del file del formato di documento.


**Returns:**
java.lang.String
### getFormatFamily() {#getFormatFamily--}
```
public final FormatFamilies getFormatFamily()
```


Ottiene la famiglia di formati a cui appartiene il formato del documento.


**Returns:**
[FormatFamilies](../../com.groupdocs.editor.formats/formatfamilies)
### <T>fromMime(Class<T> clazz, String mime) {#-T-fromMime-java.lang.Class-T--java.lang.String-}
```
public static T <T>fromMime(Class<T> clazz, String mime)
```


Recupera un'istanza del tipo specificato
T
che ha il tipo MIME specificato.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| clazz | java.lang.Class<T> |  |
|  | mime | java.lang.String | Il tipo MIME del formato del documento. |


T
: Il tipo di formato del documento.
|

**Returns:**
T - Un'istanza del tipo specificato  T  con il tipo MIME specificato.

### hashCode() {#hashCode--}
```
public int hashCode()
```


Restituisce un codice hash per l'oggetto corrente.


**Returns:**
int - Un codice hash per l'oggetto corrente, combinando i codici hash dell'oggetto base, del tipo MIME, dell'estensione del file e della famiglia di formati.

### equals(IDocumentFormat other) {#equals-com.groupdocs.editor.formats.abstraction.IDocumentFormat-}
```
public final boolean equals(IDocumentFormat other)
```


Determina se questa istanza è uguale all'istanza [IDocumentFormat](../../com.groupdocs.editor.formats.abstraction/idocumentformat) specificata.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | other | [IDocumentFormat](../../com.groupdocs.editor.formats.abstraction/idocumentformat) | L'istanza [IDocumentFormat](../../com.groupdocs.editor.formats.abstraction/idocumentformat) da confrontare con l'istanza corrente. |
|

**Returns:**
boolean -  true  se l'[IDocumentFormat](../../com.groupdocs.editor.formats.abstraction/idocumentformat) specificato è uguale all'istanza corrente; altrimenti,  false .

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Determina se questa istanza è uguale all'istanza [DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase) specificata.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | obj | java.lang.Object | L'istanza [DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase) da confrontare con l'istanza corrente. |
|

**Returns:**
boolean -  true  se il [DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase) specificato è uguale all'istanza corrente; altrimenti,  false .

### toString(DocumentFormatBase extension) {#toString-com.groupdocs.editor.formats.abstraction.DocumentFormatBase-}
```
public static String toString(DocumentFormatBase extension)
```


Converte implicitamente un'istanza [DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase) in una stringa.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | extension | [DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase) | L'istanza [DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase) da convertire. |
|

**Returns:**
java.lang.String - L'estensione del file dell'istanza [DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase).

