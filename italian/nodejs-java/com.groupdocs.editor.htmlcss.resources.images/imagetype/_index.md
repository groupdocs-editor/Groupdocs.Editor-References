---
title: "ImageType"
second_title: "Riferimento API di GroupDocs.Editor per Node.js via Java"
description: "Rappresenta un formato di tipo immagine supportabile che supporta sia formati raster che vettoriali"
type: docs
weight: 11
url: /it/nodejs-java/com.groupdocs.editor.htmlcss.resources.images/imagetype/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.resources.IResourceType](../../com.groupdocs.editor.htmlcss.resources/iresourcetype)
```
public class ImageType implements IResourceType
```

Rappresenta un tipo di immagine supportabile (formato), supporta sia formati raster che vettoriali.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [ImageType()](#ImageType--) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [getUndefined()](#getUndefined--) | Tipo di immagine non definito - valore speciale, che normalmente non dovrebbe verificarsi |
|
|  | [getJpeg()](#getJpeg--) | Tipo immagine JPEG |
|
|  | [getPng()](#getPng--) | Tipo immagine PNG |
|
|  | [getBmp()](#getBmp--) | Tipo immagine BMP |
|
|  | [getGif()](#getGif--) | Tipo immagine GIF |
|
|  | [getIcon()](#getIcon--) | Tipo immagine ICON |
|
|  | [getSvg()](#getSvg--) | Tipo di immagine vettoriale SVG |
|
|  | [getWmf()](#getWmf--) | Tipo di immagine vettoriale WMF (Windows MetaFile) |
|
|  | [getEmf()](#getEmf--) | Tipo di immagine vettoriale EMF (Enhanced MetaFile) |
|
|  | [getTiff()](#getTiff--) | Tipo di immagine raster TIFF (Tagged Image File Format) |
|
|  | [getFormalName()](#getFormalName--) | Restituisce un nome formale di questo formato immagine. |
|
|  | [isVector()](#isVector--) | Indica se questo formato particolare è vettoriale (true) o raster |
(false)
|
|  | [getFileExtension()](#getFileExtension--) | Estensione file (senza il carattere punto iniziale) di un tipo di immagine particolare |
in minuscolo.
|
|  | [toString()](#toString--) | Restituisce la proprietà FormalName |
|
|  | [getMimeCode()](#getMimeCode--) | Codice MIME di un tipo di immagine particolare come stringa. |
|
|  | [equals(ImageType other)](#equals-com.groupdocs.editor.htmlcss.resources.images.ImageType-) | Determina se questa istanza è uguale a "ImageType" specificato |
istanza
|
|  | [equals(Object obj)](#equals-java.lang.Object-) | Determina se questa istanza è uguale a un oggetto non convertito specificato, |
che presumibilmente è un'altra istanza di "ImageType"
|
|  | [op_Equality(ImageType first, ImageType second)](#op-Equality-com.groupdocs.editor.htmlcss.resources.images.ImageType-com.groupdocs.editor.htmlcss.resources.images.ImageType-) | Definisce se due specifiche istanze di ImageType sono uguali |
|
|  | [op_Inequality(ImageType first, ImageType second)](#op-Inequality-com.groupdocs.editor.htmlcss.resources.images.ImageType-com.groupdocs.editor.htmlcss.resources.images.ImageType-) | Definisce se due specifiche istanze di ImageType non sono uguali |
|
|  | [hashCode()](#hashCode--) | Restituisce un hash-code, che è un numero immutabile per questo specifico |
istanza
|
|  | [parseFromFilenameWithExtension(String filename)](#parseFromFilenameWithExtension-java.lang.String-) | Restituisce il valore ImageType, che è equivalente all'estensione del nome file, che |
viene estratto dal nome file specificato
|
|  | [parseFromMime(String mimeCode)](#parseFromMime-java.lang.String-) | Restituisce il valore ImageType, che è equivalente al codice MIME specificato |
|
### ImageType() {#ImageType--}
```
public ImageType()
```


### getUndefined() {#getUndefined--}
```
public static ImageType getUndefined()
```


Tipo di immagine non definito - valore speciale, che normalmente non dovrebbe verificarsi


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype)
### getJpeg() {#getJpeg--}
```
public static ImageType getJpeg()
```


Tipo immagine JPEG


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype)
### getPng() {#getPng--}
```
public static ImageType getPng()
```


Tipo immagine PNG


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype)
### getBmp() {#getBmp--}
```
public static ImageType getBmp()
```


Tipo immagine BMP


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype)
### getGif() {#getGif--}
```
public static ImageType getGif()
```


Tipo immagine GIF


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype)
### getIcon() {#getIcon--}
```
public static ImageType getIcon()
```


Tipo immagine ICON


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype)
### getSvg() {#getSvg--}
```
public static ImageType getSvg()
```


Tipo di immagine vettoriale SVG


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype)
### getWmf() {#getWmf--}
```
public static ImageType getWmf()
```


Tipo di immagine vettoriale WMF (Windows MetaFile)


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype)
### getEmf() {#getEmf--}
```
public static ImageType getEmf()
```


Tipo di immagine vettoriale EMF (Enhanced MetaFile)


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype)
### getTiff() {#getTiff--}
```
public static ImageType getTiff()
```


Tipo di immagine raster TIFF (Tagged Image File Format)


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype)
### getFormalName() {#getFormalName--}
```
public final String getFormalName()
```


Restituisce un nome formale di questo formato immagine. Non restituisce mai NULL. Se
l'istanza non è corrotta, non genera mai un'eccezione.


**Returns:**
java.lang.String
### isVector() {#isVector--}
```
public final boolean isVector()
```


Indica se questo formato particolare è vettoriale (true) o raster
(false)


**Returns:**
boolean
### getFileExtension() {#getFileExtension--}
```
public final String getFileExtension()
```


Estensione file (senza il carattere punto iniziale) di un tipo di immagine particolare
in minuscolo. Per il tipo Undefined restituisce la stringa 'unsefined'.


**Returns:**
java.lang.String
### toString() {#toString--}
```
public String toString()
```


Restituisce la proprietà FormalName


**Returns:**
java.lang.String -
### getMimeCode() {#getMimeCode--}
```
public final String getMimeCode()
```


Codice MIME di un tipo di immagine particolare come stringa. Per il tipo Undefined
restituisce la stringa 'unsefined'.


**Returns:**
java.lang.String
### equals(ImageType other) {#equals-com.groupdocs.editor.htmlcss.resources.images.ImageType-}
```
public final boolean equals(ImageType other)
```


Determina se questa istanza è uguale a "ImageType" specificato
istanza


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | other | [ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype) | Altra istanza di ImageType da verificare per uguaglianza con questa |
|

**Returns:**
boolean - True se sono uguali, false se sono diversi

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Determina se questa istanza è uguale a un oggetto non convertito specificato,
che presumibilmente è un'altra istanza di "ImageType"


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | obj | java.lang.Object | Altra istanza di System.Object, presumibilmente di tipo ImageType, da verificare per uguaglianza con questa |
|

**Returns:**
boolean - True se sono uguali, false se sono diversi

### op_Equality(ImageType first, ImageType second) {#op-Equality-com.groupdocs.editor.htmlcss.resources.images.ImageType-com.groupdocs.editor.htmlcss.resources.images.ImageType-}
```
public static boolean op_Equality(ImageType first, ImageType second)
```


Definisce se due specifiche istanze di ImageType sono uguali


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | first | [ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype) | Prima istanza di ImageType da verificare |
|
|  | second | [ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype) | Seconda istanza di ImageType da verificare |
|

**Returns:**
boolean - True se sono uguali, false se sono diversi

### op_Inequality(ImageType first, ImageType second) {#op-Inequality-com.groupdocs.editor.htmlcss.resources.images.ImageType-com.groupdocs.editor.htmlcss.resources.images.ImageType-}
```
public static boolean op_Inequality(ImageType first, ImageType second)
```


Definisce se due specifiche istanze di ImageType non sono uguali


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | first | [ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype) | Prima istanza di ImageType da verificare |
|
|  | second | [ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype) | Seconda istanza di ImageType da verificare |
|

**Returns:**
boolean - True se sono diversi, false se sono uguali

### hashCode() {#hashCode--}
```
public int hashCode()
```


Restituisce un hash-code, che è un numero immutabile per questo specifico
istanza


**Returns:**
int - Intero con segno a 4 byte

### parseFromFilenameWithExtension(String filename) {#parseFromFilenameWithExtension-java.lang.String-}
```
public static ImageType parseFromFilenameWithExtension(String filename)
```


Restituisce il valore ImageType, che è equivalente all'estensione del nome file, che
viene estratto dal nome file specificato


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | nome file | java.lang.String | Nome file arbitrario, può essere un percorso relativo o completo |
|

**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype) - ImageType value. Returns ImageType.Undefined, if extension cannot be recognized.

### parseFromMime(String mimeCode) {#parseFromMime-java.lang.String-}
```
public static ImageType parseFromMime(String mimeCode)
```


Restituisce il valore ImageType, che è equivalente al codice MIME specificato


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | mimeCode | java.lang.String | Codice MIME arbitrario |
|

**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype) - ImageType value. Returns ImageType.Undefined, if extension cannot be recognized.

