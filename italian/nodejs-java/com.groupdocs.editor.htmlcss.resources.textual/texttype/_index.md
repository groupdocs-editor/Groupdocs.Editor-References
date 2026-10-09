---
title: "TextType"
second_title: "Riferimento API di GroupDocs.Editor per Node.js via Java"
description: "Rappresenta un tipo di risorsa testuale supportabile"
type: docs
weight: 12
url: /it/nodejs-java/com.groupdocs.editor.htmlcss.resources.textual/texttype/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.resources.IResourceType](../../com.groupdocs.editor.htmlcss.resources/iresourcetype)
```
public class TextType implements IResourceType
```

Rappresenta un tipo di risorsa testuale supportabile

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [TextType()](#TextType--) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [getUndefined()](#getUndefined--) | Valore speciale, che contrassegna testo non definito, sconosciuto o non supportato. |
resource
|
|  | [getCss()](#getCss--) | Tipo CSS della risorsa testuale. |
|
|  | [getXml()](#getXml--) | Tipo XML della risorsa testuale. |
|
|  | [getFormalName()](#getFormalName--) | Restituisce un nome formale di questo tipo di risorsa testuale. |
|
|  | [getFileExtension()](#getFileExtension--) | Estensione del file (senza il carattere punto iniziale) di un particolare testo |
resource
|
|  | [getMimeCode()](#getMimeCode--) | Codice MIME di un particolare tipo di risorsa testuale |
|
|  | [equals(TextType other)](#equals-com.groupdocs.editor.htmlcss.resources.textual.TextType-) | Determina se questa istanza è uguale a "TextType" specificato |
istanza
|
|  | [equals(Object obj)](#equals-java.lang.Object-) | Determina se questa istanza è uguale a un oggetto non convertito specificato, |
che presumibilmente è un'altra istanza di "TextType"
|
|  | [op_Equality(TextType first, TextType second)](#op-Equality-com.groupdocs.editor.htmlcss.resources.textual.TextType-com.groupdocs.editor.htmlcss.resources.textual.TextType-) | Definisce se due specifiche istanze di "TextType" sono uguali |
|
|  | [op_Inequality(TextType first, TextType second)](#op-Inequality-com.groupdocs.editor.htmlcss.resources.textual.TextType-com.groupdocs.editor.htmlcss.resources.textual.TextType-) | Definisce se due specifiche istanze di "TextType" non sono uguali |
|
|  | [hashCode()](#hashCode--) | Restituisce un hash-code, che è un numero costante per questo valore specifico |
tipo
|
|  | [parseFromFilenameWithExtension(String filename)](#parseFromFilenameWithExtension-java.lang.String-) | Restituisce il valore TextType, che è equivalente all'estensione del nome file, estratta dal nome file specificato con estensione o dall'estensione pura |
|
### TextType() {#TextType--}
```
public TextType()
```


### getUndefined() {#getUndefined--}
```
public static TextType getUndefined()
```


Valore speciale, che contrassegna testo non definito, sconosciuto o non supportato.
resource


**Returns:**
[TextType](../../com.groupdocs.editor.htmlcss.resources.textual/texttype)
### getCss() {#getCss--}
```
public static TextType getCss()
```


Tipo CSS della risorsa testuale.


**Returns:**
[TextType](../../com.groupdocs.editor.htmlcss.resources.textual/texttype)
### getXml() {#getXml--}
```
public static TextType getXml()
```


Tipo XML della risorsa testuale.


**Returns:**
[TextType](../../com.groupdocs.editor.htmlcss.resources.textual/texttype)
### getFormalName() {#getFormalName--}
```
public final String getFormalName()
```


Restituisce un nome formale di questo tipo di risorsa testuale.


**Returns:**
java.lang.String
### getFileExtension() {#getFileExtension--}
```
public final String getFileExtension()
```


Estensione del file (senza il carattere punto iniziale) di un particolare testo
resource


**Returns:**
java.lang.String
### getMimeCode() {#getMimeCode--}
```
public final String getMimeCode()
```


Codice MIME di un particolare tipo di risorsa testuale


**Returns:**
java.lang.String
### equals(TextType other) {#equals-com.groupdocs.editor.htmlcss.resources.textual.TextType-}
```
public final boolean equals(TextType other)
```


Determina se questa istanza è uguale a "TextType" specificato
istanza


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | other | [TextType](../../com.groupdocs.editor.htmlcss.resources.textual/texttype) | Altra istanza di TextType, che dovrebbe essere confrontata con questa per l'uguaglianza |
|

**Returns:**
boolean - Restituisce true se sono uguali o false se sono diversi

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Determina se questa istanza è uguale a un oggetto non convertito specificato,
che presumibilmente è un'altra istanza di "TextType"


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | obj | java.lang.Object | Altra istanza di TextType, che è incapsulata in un oggetto |
|

**Returns:**
boolean - Restituisce true se sono uguali o false se sono diversi

### op_Equality(TextType first, TextType second) {#op-Equality-com.groupdocs.editor.htmlcss.resources.textual.TextType-com.groupdocs.editor.htmlcss.resources.textual.TextType-}
```
public static boolean op_Equality(TextType first, TextType second)
```


Definisce se due specifiche istanze di "TextType" sono uguali


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | first | [TextType](../../com.groupdocs.editor.htmlcss.resources.textual/texttype) | Prima istanza di TextType |
|
|  | second | [TextType](../../com.groupdocs.editor.htmlcss.resources.textual/texttype) | Seconda istanza di TextType |
|

**Returns:**
boolean - Restituisce true se sono uguali o false se sono diversi

### op_Inequality(TextType first, TextType second) {#op-Inequality-com.groupdocs.editor.htmlcss.resources.textual.TextType-com.groupdocs.editor.htmlcss.resources.textual.TextType-}
```
public static boolean op_Inequality(TextType first, TextType second)
```


Definisce se due specifiche istanze di "TextType" non sono uguali


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | first | [TextType](../../com.groupdocs.editor.htmlcss.resources.textual/texttype) | Prima istanza di TextType |
|
|  | second | [TextType](../../com.groupdocs.editor.htmlcss.resources.textual/texttype) | Seconda istanza di TextType |
|

**Returns:**
boolean - Restituisce true se sono diversi o false se sono uguali

### hashCode() {#hashCode--}
```
public int hashCode()
```


Restituisce un hash-code, che è un numero costante per questo valore specifico
tipo


**Returns:**
int - Numero intero con segno a 4 byte. Restituisce 0 se questa istanza ha valore predefinito.

### parseFromFilenameWithExtension(String filename) {#parseFromFilenameWithExtension-java.lang.String-}
```
public static TextType parseFromFilenameWithExtension(String filename)
```


Restituisce il valore TextType, che è equivalente all'estensione del nome file, estratta dal nome file specificato con estensione o dall'estensione pura


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | nome file | java.lang.String | Nome file con estensione, può essere un percorso relativo o assoluto, o l'estensione pura stessa |
|

**Returns:**
[TextType](../../com.groupdocs.editor.htmlcss.resources.textual/texttype) - Parsed TextType instance on success or TextType.Undefined on failure

