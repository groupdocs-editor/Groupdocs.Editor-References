---
title: "IconImage"
second_title: "GroupDocs.Editor per Java Riferimento API"
description: "Rappresenta un'immagine in formato ICON con i suoi metadata e metodi aggiuntivi"
type: docs
weight: 12
url: /it/java/com.groupdocs.editor.htmlcss.resources.images.raster/iconimage/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.htmlcss.resources.images.raster.RasterImageResourceBase](../../com.groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase)
```
public final class IconImage extends RasterImageResourceBase
```

Rappresenta un'immagine in formato ICON con i suoi metadata e metodi aggiuntivi

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
|  | [IconImage(String name, String contentInBase64)](#IconImage-java.lang.String-java.lang.String-) | Crea una nuova istanza di IconImage dal contenuto, rappresentato come |
stringa codificata in base64, e con il nome specificato
|
|  | [IconImage(String name, InputStream binaryContent)](#IconImage-java.lang.String-java.io.InputStream-) | Crea una nuova istanza di IconImage dal contenuto, rappresentato come flusso di byte, |
e con nome specificato
|
## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [isValid(InputStream binaryContent)](#isValid-java.io.InputStream-) | Verifica se il flusso specificato è un'immagine ICON valida |
|
|  | [isValid(String contentInBase64)](#isValid-java.lang.String-) | Verifica se la stringa codificata in base64 specificata è un'immagine ICON valida |
|
|  | [getType()](#getType--) | Restituisce ImageType.Icon |
|
|  | [getNumberOfImages()](#getNumberOfImages--) | Restituisce il numero di immagini presenti in questo file ICON |
|
### IconImage(String name, String contentInBase64) {#IconImage-java.lang.String-java.lang.String-}
```
public IconImage(String name, String contentInBase64)
```


Crea una nuova istanza di IconImage dal contenuto, rappresentato come
stringa codificata in base64, e con il nome specificato


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | nome | java.lang.String | Nome dell'immagine ICON. Non può essere nullo, vuoto o contenere spazi. |
|
|  | contentInBase64 | java.lang.String | Contenuto come stringa codificata in base64. Non può essere nullo, vuoto o contenere spazi. Se non è un contenuto ICON, verrà sollevata un'eccezione. |
|

### IconImage(String name, InputStream binaryContent) {#IconImage-java.lang.String-java.io.InputStream-}
```
public IconImage(String name, InputStream binaryContent)
```


Crea una nuova istanza di IconImage dal contenuto, rappresentato come flusso di byte,
e con nome specificato


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | nome | java.lang.String | Nome dell'immagine ICON. Non può essere nullo, vuoto o contenere spazi. |
|
|  | binaryContent | java.io.InputStream | Contenuto come flusso di byte. La lettura inizia dalla posizione originale. Non può essere nullo. Deve essere leggibile e ricercabile. Se questa istanza verrà rilasciata, anche questo flusso verrà rilasciato. |
|

### isValid(InputStream binaryContent) {#isValid-java.io.InputStream-}
```
public static boolean isValid(InputStream binaryContent)
```


Verifica se il flusso specificato è un'immagine ICON valida


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | binaryContent | java.io.InputStream | Flusso di byte, che presumibilmente contiene un'immagine ICON |
|

**Returns:**
boolean - True se il flusso specificato contiene un'immagine ICON valida, false altrimenti

### isValid(String contentInBase64) {#isValid-java.lang.String-}
```
public static boolean isValid(String contentInBase64)
```


Verifica se la stringa codificata in base64 specificata è un'immagine ICON valida


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | contentInBase64 | java.lang.String | Contenuto dell'immagine ICON presumibilmente in forma di stringa codificata in base64 |
|

**Returns:**
boolean - True se la stringa specificata contiene un'immagine ICON valida, false altrimenti

### getType() {#getType--}
```
public ImageType getType()
```


Restituisce ImageType.Icon


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype)
### getNumberOfImages() {#getNumberOfImages--}
```
public final int getNumberOfImages()
```


Restituisce il numero di immagini presenti in questo file ICON


**Returns:**
int
