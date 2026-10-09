---
title: "WmfImage"
second_title: "Riferimento API di GroupDocs.Editor per Node.js via Java"
description: "Rappresenta un'immagine vettoriale in formato WMF Windows MetaFile con i suoi metadati e metodi aggiuntivi"
type: docs
weight: 14
url: /it/nodejs-java/com.groupdocs.editor.htmlcss.resources.images.vector/wmfimage/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.htmlcss.resources.images.vector.VectorImageResourceBase](../../com.groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase), [com.groupdocs.editor.htmlcss.resources.images.vector.MetaImageBase](../../com.groupdocs.editor.htmlcss.resources.images.vector/metaimagebase)
```
public final class WmfImage extends MetaImageBase
```

Rappresenta un'immagine vettoriale in formato WMF (Windows MetaFile) con i suoi
metadati e metodi aggiuntivi

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
|  | [WmfImage(String name, String contentInBase64)](#WmfImage-java.lang.String-java.lang.String-) | Crea una nuova istanza di WmfImage dal contenuto, rappresentato come codificato in base64 |
stringa, e con nome specificato
|
|  | [WmfImage(String name, InputStream binaryContent)](#WmfImage-java.lang.String-java.io.InputStream-) | Crea una nuova istanza di WmfImage dal contenuto, rappresentato come flusso di byte, |
e con il nome specificato
|
## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [isValid(InputStream binaryContent)](#isValid-java.io.InputStream-) | Verifica se lo stream specificato è un'immagine WMF valida |
|
|  | [isValid(String contentInBase64)](#isValid-java.lang.String-) | Verifica se la stringa codificata in base64 specificata è un'immagine WMF valida |
|
|  | [getType()](#getType--) | Restituisce ImageType.Wmf |
|
|  | [getByteContent()](#getByteContent--) | Restituisce il contenuto di questa immagine WMF come flusso binario |
|
|  | [getTextContent()](#getTextContent--) | Restituisce il contenuto di questa immagine WMF come testo semplice |
|
|  | [save(String fullPathToFile)](#save-java.lang.String-) | Salva questa immagine WMF nel file |
|
|  | [saveToPng(OutputStream outputPngContent)](#saveToPng-java.io.OutputStream-) | Salva questa immagine vettoriale WMF in un'immagine raster PNG |
|
|  | [saveToSvg(OutputStream outputSvgContent)](#saveToSvg-java.io.OutputStream-) | Salva questa immagine vettoriale WMF in un'immagine vettoriale SVG |
|
|  | [dispose()](#dispose--) | Elimina questa immagine WMF eliminando il suo contenuto e rendendo la maggior parte dei suoi |
metodi e proprietà non funzionanti
|
### WmfImage(String name, String contentInBase64) {#WmfImage-java.lang.String-java.lang.String-}
```
public WmfImage(String name, String contentInBase64)
```


Crea una nuova istanza di WmfImage dal contenuto, rappresentato come codificato in base64
stringa, e con nome specificato


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | nome | java.lang.String | Nome dell'immagine WMF. Non può essere nullo, vuoto o contenere solo spazi. |
|
|  | contentInBase64 | java.lang.String | Contenuto come stringa codificata in base64. Non può essere nullo, vuoto o contenere solo spazi. Se non è un contenuto WMF, verrà sollevata un'eccezione. |
|

### WmfImage(String name, InputStream binaryContent) {#WmfImage-java.lang.String-java.io.InputStream-}
```
public WmfImage(String name, InputStream binaryContent)
```


Crea una nuova istanza di WmfImage dal contenuto, rappresentato come flusso di byte,
e con il nome specificato


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | nome | java.lang.String | Nome dell'immagine WMF. Non può essere nullo, vuoto o contenere solo spazi. |
|
|  | binaryContent | java.io.InputStream | Contenuto come flusso di byte. La lettura inizia dalla posizione originale. Non può essere nullo. Deve essere leggibile e ricercabile. Se questa istanza verrà eliminata, anche questo flusso verrà eliminato. |
|

### isValid(InputStream binaryContent) {#isValid-java.io.InputStream-}
```
public static boolean isValid(InputStream binaryContent)
```


Verifica se lo stream specificato è un'immagine WMF valida


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | binaryContent | java.io.InputStream | Flusso di byte in ingresso. Non può essere NULL, dovrebbe supportare lettura e ricerca. |
|

**Returns:**
boolean - True se lo stream specificato contiene un'immagine WMF valida, false altrimenti

### isValid(String contentInBase64) {#isValid-java.lang.String-}
```
public static boolean isValid(String contentInBase64)
```


Verifica se la stringa codificata in base64 specificata è un'immagine WMF valida


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | contentInBase64 | java.lang.String | Stringa di input, dove il contenuto dell'immagine WMF è memorizzato in codifica base64. Non può essere NULL o vuota. |
|

**Returns:**
boolean - True se la stringa specificata contiene un'immagine WMF valida, false altrimenti

### getType() {#getType--}
```
public ImageType getType()
```


Restituisce ImageType.Wmf


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype) - 
### getByteContent() {#getByteContent--}
```
public InputStream getByteContent()
```


Restituisce il contenuto di questa immagine WMF come flusso binario


**Returns:**
java.io.InputStream -
### getTextContent() {#getTextContent--}
```
public String getTextContent()
```


Restituisce il contenuto di questa immagine WMF come testo semplice


**Returns:**
java.lang.String -
### save(String fullPathToFile) {#save-java.lang.String-}
```
public void save(String fullPathToFile)
```


Salva questa immagine WMF nel file


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | fullPathToFile | java.lang.String | Percorso completo al file, che sarà creato (se non esiste) o sovrascritto (se esiste) con il contenuto di questa immagine WMF |
|

### saveToPng(OutputStream outputPngContent) {#saveToPng-java.io.OutputStream-}
```
public void saveToPng(OutputStream outputPngContent)
```


Salva questa immagine vettoriale WMF in un'immagine raster PNG


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | outputPngContent | java.io.OutputStream | Flusso di output, nel quale verrà scritto il contenuto dell'immagine PNG. Non può essere NULL e dovrebbe essere scrivibile. |
|

### saveToSvg(OutputStream outputSvgContent) {#saveToSvg-java.io.OutputStream-}
```
public void saveToSvg(OutputStream outputSvgContent)
```


Salva questa immagine vettoriale WMF in un'immagine vettoriale SVG


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | outputSvgContent | java.io.OutputStream | Flusso di output, nel quale verrà scritto il contenuto dell'immagine SVG. Non può essere NULL e dovrebbe essere scrivibile. |
|

### dispose() {#dispose--}
```
public void dispose()
```


Elimina questa immagine WMF eliminando il suo contenuto e rendendo la maggior parte dei suoi
metodi e proprietà non funzionanti


