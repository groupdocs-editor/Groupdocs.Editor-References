---
title: "FontType"
second_title: "Riferimento API di GroupDocs.Editor per Node.js via Java"
description: "Rappresenta un tipo di font supportabile."
type: docs
weight: 12
url: /it/nodejs-java/com.groupdocs.editor.htmlcss.resources.fonts/fonttype/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.resources.IResourceType](../../com.groupdocs.editor.htmlcss.resources/iresourcetype)
```
public class FontType implements IResourceType
```

Rappresenta un tipo di font supportabile.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [FontType()](#FontType--) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [getUndefined()](#getUndefined--) | Valore speciale che indica un font non definito, sconosciuto o non supportato |
resource
|
|  | [getWoff()](#getWoff--) | Rappresenta un tipo di font WOFF (Web Open Font Format) |
|
|  | [getWoff2()](#getWoff2--) | Rappresenta un tipo di font WOFF2 (Web Open Font Format versione 2) |
|
|  | [getTtf()](#getTtf--) | Rappresenta un tipo di font TTF (TrueType Font) |
|
|  | [getOtf()](#getOtf--) | Rappresenta un tipo di font OTF (OpenType Font) |
|
|  | [getTtc()](#getTtc--) | Rappresenta un font TrueType Collection (TTC) |
|
|  | [getEot()](#getEot--) | Rappresenta un tipo di font EOT (Embedded OpenType) |
|
|  | [getCssName()](#getCssName--) | Restituisce il nome compatibile CSS di questo tipo di font, utilizzato nel |
|
|  | [getFormalName()](#getFormalName--) | Restituisce un nome formale di questo tipo di font |
|
|  | [getFileExtension()](#getFileExtension--) | Estensione del nome file (senza il carattere punto) per questo tipo di font |
|
|  | [getFontFormat()](#getFontFormat--) | Formato del font per il formato @font-face |
|
|  | [getMimeCode()](#getMimeCode--) | Codice MIME di un tipo di font specifico |
|
|  | [parseFromCssName(String name)](#parseFromCssName-java.lang.String-) | Restituisce il valore FontType, che è equivalente al CSS compatibile specificato |
nome del tipo di font
|
|  | [parseFromFilenameWithExtension(String filename)](#parseFromFilenameWithExtension-java.lang.String-) | Restituisce il valore FontType, che è equivalente all'estensione del nome file, che |
viene estratto dal nome file specificato
|
|  | [parseFromMime(String mimeCode)](#parseFromMime-java.lang.String-) | Restituisce il valore FontType, che è equivalente al MIME-code specificato |
|
|  | [getFirstDefined(FontType[] fonts)](#getFirstDefined-com.groupdocs.editor.htmlcss.resources.fonts.FontType...-) | Restituisce il primo tipo di font dal set specificato, che non è un "Undefined" |
valore, o tipo di font "Undefined" altrimenti (quando tutti gli elementi sono
"Undefined")
|
|  | [equals(FontType other)](#equals-com.groupdocs.editor.htmlcss.resources.fonts.FontType-) | Determina se questa istanza è uguale a "FontType" specificato |
istanza
|
|  | [equals(Object obj)](#equals-java.lang.Object-) | Determina se questa istanza è uguale a un oggetto non convertito specificato, |
che presumibilmente è un'altra istanza di "FontType"
|
|  | [op_Equality(FontType first, FontType second)](#op-Equality-com.groupdocs.editor.htmlcss.resources.fonts.FontType-com.groupdocs.editor.htmlcss.resources.fonts.FontType-) | Verifica se due valori "FontType" sono uguali |
|
|  | [op_Inequality(FontType first, FontType second)](#op-Inequality-com.groupdocs.editor.htmlcss.resources.fonts.FontType-com.groupdocs.editor.htmlcss.resources.fonts.FontType-) | Verifica se due valori "FontType" non sono uguali |
|
|  | [hashCode()](#hashCode--) | Restituisce un hash-code, che è un numero costante per questo valore specifico |
tipo
|
### FontType() {#FontType--}
```
public FontType()
```


### getUndefined() {#getUndefined--}
```
public static FontType getUndefined()
```


Valore speciale che indica un font non definito, sconosciuto o non supportato
resource


**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) - 
### getWoff() {#getWoff--}
```
public static FontType getWoff()
```


Rappresenta un tipo di font WOFF (Web Open Font Format)


**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) - 
### getWoff2() {#getWoff2--}
```
public static FontType getWoff2()
```


Rappresenta un tipo di font WOFF2 (Web Open Font Format versione 2)


**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) - 
### getTtf() {#getTtf--}
```
public static FontType getTtf()
```


Rappresenta un tipo di font TTF (TrueType Font)


**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) - 
### getOtf() {#getOtf--}
```
public static FontType getOtf()
```


Rappresenta un tipo di font OTF (OpenType Font)


**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) - 
### getTtc() {#getTtc--}
```
public static FontType getTtc()
```


Rappresenta un font TrueType Collection (TTC)


**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) - 
### getEot() {#getEot--}
```
public static FontType getEot()
```


Rappresenta un tipo di font EOT (Embedded OpenType)


**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) - 
### getCssName() {#getCssName--}
```
public final String getCssName()
```


Restituisce il nome compatibile CSS di questo tipo di font, utilizzato nel


**Returns:**
java.lang.String -
### getFormalName() {#getFormalName--}
```
public final String getFormalName()
```


Restituisce un nome formale di questo tipo di font


**Returns:**
java.lang.String -
### getFileExtension() {#getFileExtension--}
```
public final String getFileExtension()
```


Estensione del nome file (senza il carattere punto) per questo tipo di font


**Returns:**
java.lang.String -
### getFontFormat() {#getFontFormat--}
```
public final String getFontFormat()
```


Formato del font per il formato @font-face


**Returns:**
java.lang.String -
### getMimeCode() {#getMimeCode--}
```
public final String getMimeCode()
```


Codice MIME di un tipo di font specifico


**Returns:**
java.lang.String -
### parseFromCssName(String name) {#parseFromCssName-java.lang.String-}
```
public static FontType parseFromCssName(String name)
```


Restituisce il valore FontType, che è equivalente al CSS compatibile specificato
nome del tipo di font


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | nome | java.lang.String | Nome compatibile CSS del tipo di font |
|

**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) - Valid FontType value on success or FontType.Undefined on failure

### parseFromFilenameWithExtension(String filename) {#parseFromFilenameWithExtension-java.lang.String-}
```
public static FontType parseFromFilenameWithExtension(String filename)
```


Restituisce il valore FontType, che è equivalente all'estensione del nome file, che
viene estratto dal nome file specificato


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | nome file | java.lang.String | Nome file con estensione, può essere un nome completo |
|

**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) - Valid FontType value on success or FontType.Undefined on failure

### parseFromMime(String mimeCode) {#parseFromMime-java.lang.String-}
```
public static FontType parseFromMime(String mimeCode)
```


Restituisce il valore FontType, che è equivalente al MIME-code specificato


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | mimeCode | java.lang.String | Codice MIME |
|

**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) - Valid FontType value on success or FontType.Undefined on failure

### getFirstDefined(FontType[] fonts) {#getFirstDefined-com.groupdocs.editor.htmlcss.resources.fonts.FontType...-}
```
public static FontType getFirstDefined(FontType[] fonts)
```


Restituisce il primo tipo di font dal set specificato, che non è un "Undefined"
valore, o tipo di font "Undefined" altrimenti (quando tutti gli elementi sono
"Undefined")


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | fonts | [FontType\[\]](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) | Uno o più valori FontType, NULL o collezione vuota non sono consentiti |
|

**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) - First FontType value from specified collection, that is not Undefined, or Undefined, if all items are Undefined

### equals(FontType other) {#equals-com.groupdocs.editor.htmlcss.resources.fonts.FontType-}
```
public final boolean equals(FontType other)
```


Determina se questa istanza è uguale a "FontType" specificato
istanza


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | other | [FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) | Altra istanza FontType da confrontare con questa |
|

**Returns:**
boolean - True se sono uguali, false se sono diversi

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Determina se questa istanza è uguale a un oggetto non convertito specificato,
che presumibilmente è un'altra istanza di "FontType"


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | obj | java.lang.Object | Altra istanza presumibilmente della struct FontType, che è stata incapsulata in System.Object |
|

**Returns:**
boolean - True se sono uguali, false se sono diversi

### op_Equality(FontType first, FontType second) {#op-Equality-com.groupdocs.editor.htmlcss.resources.fonts.FontType-com.groupdocs.editor.htmlcss.resources.fonts.FontType-}
```
public static boolean op_Equality(FontType first, FontType second)
```


Verifica se due valori "FontType" sono uguali


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | first | [FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) | Primo FontType da verificare |
|
|  | second | [FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) | Secondo FontType da verificare |
|

**Returns:**
boolean - True se sono uguali, false se sono diversi

### op_Inequality(FontType first, FontType second) {#op-Inequality-com.groupdocs.editor.htmlcss.resources.fonts.FontType-com.groupdocs.editor.htmlcss.resources.fonts.FontType-}
```
public static boolean op_Inequality(FontType first, FontType second)
```


Verifica se due valori "FontType" non sono uguali


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | first | [FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) | Primo FontType da verificare |
|
|  | second | [FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) | Secondo FontType da verificare |
|

**Returns:**
boolean - True se sono uguali, false se sono diversi

### hashCode() {#hashCode--}
```
public int hashCode()
```


Restituisce un hash-code, che è un numero costante per questo valore specifico
tipo


**Returns:**
int - intero con segno a 4 byte, 0 per valore Undefined

