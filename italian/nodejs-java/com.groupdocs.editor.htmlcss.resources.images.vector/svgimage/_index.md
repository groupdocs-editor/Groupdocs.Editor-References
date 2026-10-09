---
title: "SvgImage"
second_title: "Riferimento API di GroupDocs.Editor per Node.js via Java"
description: "Rappresenta un'immagine vettoriale in formato SVG Scalable Vector Graphics con i suoi metadati e metodi aggiuntivi"
type: docs
weight: 12
url: /it/nodejs-java/com.groupdocs.editor.htmlcss.resources.images.vector/svgimage/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.htmlcss.resources.images.vector.VectorImageResourceBase](../../com.groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase)
```
public final class SvgImage extends VectorImageResourceBase
```

Rappresenta un'immagine vettoriale in formato SVG (Scalable Vector Graphics) con i suoi
metadati e metodi aggiuntivi

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
|  | [SvgImage(String name, String content)](#SvgImage-java.lang.String-java.lang.String-) | Crea una nuova istanza di SvgImage dal contenuto, rappresentato come stringa normale, |
e con il nome specificato
|
|  | [SvgImage(String name, InputStream binaryContent)](#SvgImage-java.lang.String-java.io.InputStream-) | Crea una nuova istanza di SvgImage dal contenuto, rappresentato come flusso di byte, |
e con il nome specificato
|
## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [isValid(String content)](#isValid-java.lang.String-) | Esegue un controllo superficiale per verificare se il contenuto testuale specificato è conforme a XML |
rappresenta un'immagine SVG
|
|  | [getType()](#getType--) | Restituisce ImageType.Svg |
|
|  | [getByteContent()](#getByteContent--) | Restituisce il contenuto di questa immagine SVG come flusso binario |
|
|  | [getTextContent()](#getTextContent--) | Restituisce il contenuto di questa immagine SVG come testo semplice (in formato XML) |
|
|  | [getXmlContent()](#getXmlContent--) | Restituisce il contenuto di questa immagine SVG nella sua forma originale conforme a XML |
forma testuale
|
|  | [save(String fullPathToFile)](#save-java.lang.String-) | Salva questa immagine SVG nel file |
|
|  | [saveToPng(OutputStream outputPngContent)](#saveToPng-java.io.OutputStream-) | Salva questa immagine SVG vettoriale in un'immagine raster PNG |
|
|  | [dispose()](#dispose--) | Dispone di questa immagine raster, disponendo il suo contenuto e rendendo la maggior parte dei metodi |
e le proprietà non funzionanti
|
### SvgImage(String name, String content) {#SvgImage-java.lang.String-java.lang.String-}
```
public SvgImage(String name, String content)
```


Crea una nuova istanza di SvgImage dal contenuto, rappresentato come stringa normale,
e con il nome specificato


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | nome | java.lang.String | Nome dell'immagine SVG. Non può essere nullo, vuoto o contenere solo spazi. |
|
|  | contenuto | java.lang.String | Contenuto come una stringa normale, che contiene un contenuto valido conforme a XML di un'immagine SVG. Non può essere nullo, vuoto o contenere solo spazi. Se non è un contenuto SVG, verrà sollevata un'eccezione. |
|

### SvgImage(String name, InputStream binaryContent) {#SvgImage-java.lang.String-java.io.InputStream-}
```
public SvgImage(String name, InputStream binaryContent)
```


Crea una nuova istanza di SvgImage dal contenuto, rappresentato come flusso di byte,
e con il nome specificato


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | nome | java.lang.String | Nome dell'immagine SVG. Non può essere nullo, vuoto o contenere solo spazi. |
|
|  | binaryContent | java.io.InputStream | Contenuto come flusso di byte. La lettura inizia dalla posizione originale. Non può essere nullo. Deve essere leggibile e ricercabile. Se questa istanza verrà eliminata, anche questo flusso verrà eliminato. |
|

### isValid(String content) {#isValid-java.lang.String-}
```
public static boolean isValid(String content)
```


Esegue un controllo superficiale per verificare se il contenuto testuale specificato è conforme a XML
rappresenta un'immagine SVG


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | contenuto | java.lang.String | Contenuto XML di un'immagine SVG come testo semplice, non un contenuto codificato in base64 |
|

**Returns:**
boolean - True se la stringa specificata può essere considerata un SVG valido al primo sguardo, false se sicuramente non è un SVG

### getType() {#getType--}
```
public ImageType getType()
```


Restituisce ImageType.Svg


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype) - 
### getByteContent() {#getByteContent--}
```
public InputStream getByteContent()
```


Restituisce il contenuto di questa immagine SVG come flusso binario


**Returns:**
java.io.InputStream -
### getTextContent() {#getTextContent--}
```
public String getTextContent()
```


Restituisce il contenuto di questa immagine SVG come testo semplice (in formato XML)


**Returns:**
java.lang.String -
### getXmlContent() {#getXmlContent--}
```
public final String getXmlContent()
```


Restituisce il contenuto di questa immagine SVG nella sua forma originale conforme a XML
forma testuale


**Returns:**
java.lang.String -
### save(String fullPathToFile) {#save-java.lang.String-}
```
public void save(String fullPathToFile)
```


Salva questa immagine SVG nel file


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | fullPathToFile | java.lang.String | Percorso completo del file, che verrà creato (se non esiste) o sovrascritto (se esiste) con il contenuto di questa immagine SVG |
|

### saveToPng(OutputStream outputPngContent) {#saveToPng-java.io.OutputStream-}
```
public void saveToPng(OutputStream outputPngContent)
```


Salva questa immagine SVG vettoriale in un'immagine raster PNG


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | outputPngContent | java.io.OutputStream | Flusso di output, nel quale verrà scritto il contenuto dell'immagine PNG. Non può essere NULL e dovrebbe essere scrivibile. |
|

### dispose() {#dispose--}
```
public void dispose()
```


Dispone di questa immagine raster, disponendo il suo contenuto e rendendo la maggior parte dei metodi
e le proprietà non funzionanti


