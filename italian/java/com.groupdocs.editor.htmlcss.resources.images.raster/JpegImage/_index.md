---
title: "JpegImage"
second_title: "GroupDocs.Editor per Java Riferimento API"
description: "Rappresenta un'immagine nel formato JPEG Joint Photographic Experts Group con i suoi metadati e metodi aggiuntivi"
type: docs
weight: 13
url: /it/java/com.groupdocs.editor.htmlcss.resources.images.raster/jpegimage/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.htmlcss.resources.images.raster.RasterImageResourceBase](../../com.groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase)
```
public final class JpegImage extends RasterImageResourceBase
```

Rappresenta un'immagine nel formato JPEG (Joint Photographic Experts Group) con
i suoi metadati e metodi aggiuntivi

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
|  | [JpegImage(String name, String contentInBase64)](#JpegImage-java.lang.String-java.lang.String-) | Crea una nuova istanza di JpegImage dal contenuto, rappresentata come |
stringa codificata in base64, e con il nome specificato
|
|  | [JpegImage(String name, InputStream binaryContent)](#JpegImage-java.lang.String-java.io.InputStream-) | Crea una nuova istanza di JpegImage dal contenuto, rappresentata come flusso di byte, |
e con nome specificato
|
## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [isValid(InputStream binaryContent)](#isValid-java.io.InputStream-) | Verifica se lo stream specificato è un'immagine JPEG valida |
|
|  | [isValid(String contentInBase64)](#isValid-java.lang.String-) | Verifica se la stringa specificata codificata in base64 è un'immagine JPEG valida |
|
|  | [getType()](#getType--) | Restituisce ImageType.Jpeg |
|
### JpegImage(String name, String contentInBase64) {#JpegImage-java.lang.String-java.lang.String-}
```
public JpegImage(String name, String contentInBase64)
```


Crea una nuova istanza di JpegImage dal contenuto, rappresentata come
stringa codificata in base64, e con il nome specificato


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | nome | java.lang.String | Nome dell'immagine JPEG. Non può essere nullo, vuoto o contenere spazi. |
|
|  | contentInBase64 | java.lang.String | Contenuto come stringa codificata in base64. Non può essere nullo, vuoto o contenere spazi. Se non è un contenuto JPEG, verrà generata un'eccezione. |
|

### JpegImage(String name, InputStream binaryContent) {#JpegImage-java.lang.String-java.io.InputStream-}
```
public JpegImage(String name, InputStream binaryContent)
```


Crea una nuova istanza di JpegImage dal contenuto, rappresentata come flusso di byte,
e con nome specificato


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | nome | java.lang.String | Nome dell'immagine JPEG. Non può essere nullo, vuoto o contenere spazi. |
|
|  | binaryContent | java.io.InputStream | Contenuto come flusso di byte. La lettura inizia dalla posizione originale. Non può essere nullo. Deve essere leggibile e ricercabile. Se questa istanza verrà rilasciata, anche questo flusso verrà rilasciato. |
|

### isValid(InputStream binaryContent) {#isValid-java.io.InputStream-}
```
public static boolean isValid(InputStream binaryContent)
```


Verifica se lo stream specificato è un'immagine JPEG valida


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | binaryContent | java.io.InputStream | Flusso di byte, che presumibilmente contiene un'immagine JPEG |
|

**Returns:**
boolean - True se il flusso specificato contiene un'immagine JPEG valida, false altrimenti

### isValid(String contentInBase64) {#isValid-java.lang.String-}
```
public static boolean isValid(String contentInBase64)
```


Verifica se la stringa specificata codificata in base64 è un'immagine JPEG valida


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | contentInBase64 | java.lang.String | Contenuto dell'immagine JPEG presumibilmente in forma di stringa codificata in base64 |
|

**Returns:**
boolean - True se la stringa specificata contiene un'immagine JPEG valida, false altrimenti

### getType() {#getType--}
```
public ImageType getType()
```


Restituisce ImageType.Jpeg


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype) - 
