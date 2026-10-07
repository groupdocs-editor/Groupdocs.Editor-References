---
title: "TiffImage"
second_title: "GroupDocs.Editor per Java Riferimento API"
description: "Rappresenta un'immagine nel formato TIFF Tagged Image File Format con i suoi metadati e metodi aggiuntivi"
type: docs
weight: 16
url: /it/java/com.groupdocs.editor.htmlcss.resources.images.raster/tiffimage/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.htmlcss.resources.images.raster.RasterImageResourceBase](../../com.groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase)
```
public final class TiffImage extends RasterImageResourceBase
```

Rappresenta un'immagine nel formato TIFF (Tagged Image File Format) con i suoi
metadati e metodi aggiuntivi


*** ** * ** ***

Vedi https://en.wikipedia.org/wiki/TIFF per i dettagli. In casi molto rari TIFF è presente nei documenti WordProcessing.

<br />


## Costruttori

| Costruttore | Descrizione |
| --- | --- |
|  | [TiffImage(String name, String contentInBase64)](#TiffImage-java.lang.String-java.lang.String-) | Crea una nuova istanza di TiffImage dal contenuto, rappresentata come |
stringa codificata in base64, e con il nome specificato
|
|  | [TiffImage(String name, InputStream binaryContent)](#TiffImage-java.lang.String-java.io.InputStream-) | Crea una nuova istanza di GifImage dal contenuto, rappresentato come flusso di byte, |
e con nome specificato
|
| [TiffImage(String name, System.IO.Stream binaryContent)](#TiffImage-java.lang.String-com.aspose.ms.System.IO.Stream-) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [isValid(InputStream binaryContent)](#isValid-java.io.InputStream-) | Verifica se lo stream specificato è un'immagine TIFF valida |
|
|  | [isValid(String contentInBase64)](#isValid-java.lang.String-) | Verifica se la stringa specificata codificata in base64 è un'immagine TIFF valida |
|
|  | [getType()](#getType--) | Restituisce ImageType.Tiff |
|
|  | [getFramesCount()](#getFramesCount--) | Restituisce il numero di fotogrammi (immagini) all'interno di questa immagine TIFF. |
|
### TiffImage(String name, String contentInBase64) {#TiffImage-java.lang.String-java.lang.String-}
```
public TiffImage(String name, String contentInBase64)
```


Crea una nuova istanza di TiffImage dal contenuto, rappresentata come
stringa codificata in base64, e con il nome specificato


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | nome | java.lang.String | Nome dell'immagine TIFF. Non può essere nullo, vuoto o contenere spazi bianchi. |
|
|  | contentInBase64 | java.lang.String | Contenuto come stringa codificata in base64. Non può essere nullo, vuoto o contenere spazi bianchi. Se non è un contenuto TIFF, verrà sollevata un'eccezione. |
|

### TiffImage(String name, InputStream binaryContent) {#TiffImage-java.lang.String-java.io.InputStream-}
```
public TiffImage(String name, InputStream binaryContent)
```


Crea una nuova istanza di GifImage dal contenuto, rappresentato come flusso di byte,
e con nome specificato


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | nome | java.lang.String | Nome dell'immagine GIF. Non può essere nullo, vuoto o contenere spazi. |
|
|  | binaryContent | java.io.InputStream | Contenuto come flusso di byte. La lettura inizia dalla posizione originale. Non può essere nullo. Deve essere leggibile e ricercabile. Se questa istanza verrà rilasciata, anche questo flusso verrà rilasciato. |
|

### TiffImage(String name, System.IO.Stream binaryContent) {#TiffImage-java.lang.String-com.aspose.ms.System.IO.Stream-}
```
public TiffImage(String name, System.IO.Stream binaryContent)
```


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| nome | java.lang.String |  |
| binaryContent | com.aspose.ms.System.IO.Stream |  |

### isValid(InputStream binaryContent) {#isValid-java.io.InputStream-}
```
public static boolean isValid(InputStream binaryContent)
```


Verifica se lo stream specificato è un'immagine TIFF valida


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | binaryContent | java.io.InputStream | Flusso di byte, che presumibilmente contiene un'immagine TIFF |
|

**Returns:**
boolean - True se lo stream specificato contiene un'immagine TIFF valida, false altrimenti

### isValid(String contentInBase64) {#isValid-java.lang.String-}
```
public static boolean isValid(String contentInBase64)
```


Verifica se la stringa specificata codificata in base64 è un'immagine TIFF valida


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | contentInBase64 | java.lang.String | Contenuto dell'immagine presumibilmente TIFF in forma di stringa codificata in base64 |
|

**Returns:**
boolean - True se la stringa specificata contiene un'immagine TIFF valida, false altrimenti

### getType() {#getType--}
```
public ImageType getType()
```


Restituisce ImageType.Tiff


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype) - 
### getFramesCount() {#getFramesCount--}
```
public final int getFramesCount()
```


Restituisce il numero di fotogrammi (immagini) all'interno di questa immagine TIFF. Non può essere
inferiore a 1.


**Returns:**
int -
