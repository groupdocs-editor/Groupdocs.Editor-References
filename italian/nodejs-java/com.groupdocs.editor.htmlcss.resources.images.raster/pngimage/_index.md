---
title: "PngImage"
second_title: "Riferimento API di GroupDocs.Editor per Node.js via Java"
description: "Rappresenta un'immagine in formato PNG Portable Network Graphics con i relativi metadati e metodi aggiuntivi"
type: docs
weight: 14
url: /it/nodejs-java/com.groupdocs.editor.htmlcss.resources.images.raster/pngimage/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.htmlcss.resources.images.raster.RasterImageResourceBase](../../com.groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase)
```
public final class PngImage extends RasterImageResourceBase
```

Rappresenta un'immagine in formato PNG (Portable Network Graphics) con il suo
metadati e metodi aggiuntivi

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
|  | [PngImage(String name, String contentInBase64)](#PngImage-java.lang.String-java.lang.String-) | Crea una nuova istanza di PngImage dal contenuto, rappresentata come codificata in base64 |
stringa, e con nome specificato
|
|  | [PngImage(String name, InputStream binaryContent)](#PngImage-java.lang.String-java.io.InputStream-) | Crea una nuova istanza di PngImage dal contenuto, rappresentata come stream di byte, |
e con il nome specificato
|
## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [isValid(InputStream binaryContent)](#isValid-java.io.InputStream-) | Verifica se lo stream specificato è un'immagine PNG valida |
|
|  | [isValid(String contentInBase64)](#isValid-java.lang.String-) | Verifica se la stringa codificata in base64 specificata è un'immagine PNG valida |
|
|  | [getType()](#getType--) | Restituisce ImageType.Png |
|
### PngImage(String name, String contentInBase64) {#PngImage-java.lang.String-java.lang.String-}
```
public PngImage(String name, String contentInBase64)
```


Crea una nuova istanza di PngImage dal contenuto, rappresentata come codificata in base64
stringa, e con nome specificato


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | nome | java.lang.String | Nome dell'immagine PNG. Non può essere nullo, vuoto o contenere solo spazi. |
|
|  | contentInBase64 | java.lang.String | Contenuto come stringa codificata in base64. Non può essere nullo, vuoto o contenere solo spazi. Se non è un contenuto PNG, verrà sollevata un'eccezione. |
|

### PngImage(String name, InputStream binaryContent) {#PngImage-java.lang.String-java.io.InputStream-}
```
public PngImage(String name, InputStream binaryContent)
```


Crea una nuova istanza di PngImage dal contenuto, rappresentata come stream di byte,
e con il nome specificato


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | nome | java.lang.String | Nome dell'immagine PNG. Non può essere nullo, vuoto o contenere solo spazi. |
|
|  | binaryContent | java.io.InputStream | Contenuto come flusso di byte. La lettura inizia dalla posizione originale. Non può essere nullo. Deve essere leggibile e ricercabile. Se questa istanza verrà eliminata, anche questo flusso verrà eliminato. |
|

### isValid(InputStream binaryContent) {#isValid-java.io.InputStream-}
```
public static boolean isValid(InputStream binaryContent)
```


Verifica se lo stream specificato è un'immagine PNG valida


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | binaryContent | java.io.InputStream | Flusso di byte, che presumibilmente contiene un'immagine PNG |
|

**Returns:**
boolean - True se il flusso specificato contiene un'immagine PNG valida, false altrimenti

### isValid(String contentInBase64) {#isValid-java.lang.String-}
```
public static boolean isValid(String contentInBase64)
```


Verifica se la stringa codificata in base64 specificata è un'immagine PNG valida


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | contentInBase64 | java.lang.String | Contenuto dell'immagine PNG presumibilmente in forma di stringa codificata base64 |
|

**Returns:**
boolean - True se la stringa specificata contiene un'immagine PNG valida, false altrimenti

### getType() {#getType--}
```
public ImageType getType()
```


Restituisce ImageType.Png


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype) - 
