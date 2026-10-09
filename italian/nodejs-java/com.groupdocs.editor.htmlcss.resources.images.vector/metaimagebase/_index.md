---
title: "MetaImageBase"
second_title: "Riferimento API di GroupDocs.Editor per Node.js via Java"
description: "Classe astratta base per i formati immagine WMF ed EMF"
type: docs
weight: 11
url: /it/nodejs-java/com.groupdocs.editor.htmlcss.resources.images.vector/metaimagebase/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.htmlcss.resources.images.vector.VectorImageResourceBase](../../com.groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase)
```
public abstract class MetaImageBase extends VectorImageResourceBase
```

Classe astratta base per i formati immagine WMF ed EMF

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
|  | [MetaImageBase(String name, String contentInBase64, boolean isWmf)](#MetaImageBase-java.lang.String-java.lang.String-boolean-) | Costruttore comune, che prepara la creazione di un'istanza WMF o EMF da |
stringa codificata base64
|
|  | [MetaImageBase(String name, InputStream binaryContent, boolean isWmf)](#MetaImageBase-java.lang.String-java.io.InputStream-boolean-) | Costruttore comune, che prepara la creazione di un'istanza WMF o EMF da |
flusso di byte
|
## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [isValidWmf(InputStream binaryContent)](#isValidWmf-java.io.InputStream-) | Determina se il flusso di byte specificato contiene un'immagine WMF valida |
|
|  | [isValidWmf(String contentInBase64)](#isValidWmf-java.lang.String-) | Determina se la stringa specificata contiene un'immagine WMF valida, che è |
codificata con base64
|
|  | [isValidEmf(InputStream binaryContent)](#isValidEmf-java.io.InputStream-) | Determina se il flusso di byte specificato contiene un'immagine EMF valida |
|
|  | [isValidEmf(String contentInBase64)](#isValidEmf-java.lang.String-) | Determina se la stringa specificata contiene un'immagine EMF valida, che è |
codificata con base64
|
|  | [saveToSvg(OutputStream outputSvgContent)](#saveToSvg-java.io.OutputStream-) | Nel tipo di implementazione dovrebbe salvare la meta-immagine vettoriale corrente nel |
formato SVG vettoriale nel flusso di byte specificato
|
### MetaImageBase(String name, String contentInBase64, boolean isWmf) {#MetaImageBase-java.lang.String-java.lang.String-boolean-}
```
public MetaImageBase(String name, String contentInBase64, boolean isWmf)
```


Costruttore comune, che prepara la creazione di un'istanza WMF o EMF da
stringa codificata base64


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | nome | java.lang.String | Nome obbligatorio |
|
|  | contentInBase64 | java.lang.String | Contenuto come stringa base64. Non deve essere NULL o vuoto. |
|
|  | isWmf | boolean | true per WMF, false per EMF |
|

### MetaImageBase(String name, InputStream binaryContent, boolean isWmf) {#MetaImageBase-java.lang.String-java.io.InputStream-boolean-}
```
public MetaImageBase(String name, InputStream binaryContent, boolean isWmf)
```


Costruttore comune, che prepara la creazione di un'istanza WMF o EMF da
flusso di byte


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | nome | java.lang.String | Nome obbligatorio |
|
|  | binaryContent | java.io.InputStream | Contenuto come flusso di byte. Deve essere valido. |
|
|  | isWmf | boolean | true per WMF, false per EMF |
|

### isValidWmf(InputStream binaryContent) {#isValidWmf-java.io.InputStream-}
```
public static boolean isValidWmf(InputStream binaryContent)
```


Determina se il flusso di byte specificato contiene un'immagine WMF valida


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | binaryContent | java.io.InputStream | Flusso di byte in ingresso. Deve essere valido. |
|

**Returns:**
boolean - Restituisce 'true' se valido e 'false' se non valido

### isValidWmf(String contentInBase64) {#isValidWmf-java.lang.String-}
```
public static boolean isValidWmf(String contentInBase64)
```


Determina se la stringa specificata contiene un'immagine WMF valida, che è
codificata con base64


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | contentInBase64 | java.lang.String | Stringa, che si presume contenga un'immagine WMF codificata base64 |
|

**Returns:**
boolean - Restituisce 'true' se valido e 'false' se non valido

### isValidEmf(InputStream binaryContent) {#isValidEmf-java.io.InputStream-}
```
public static boolean isValidEmf(InputStream binaryContent)
```


Determina se il flusso di byte specificato contiene un'immagine EMF valida


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | binaryContent | java.io.InputStream | Flusso di byte in ingresso. Deve essere valido. |
|

**Returns:**
boolean - Restituisce 'true' se valido e 'false' se non valido

### isValidEmf(String contentInBase64) {#isValidEmf-java.lang.String-}
```
public static boolean isValidEmf(String contentInBase64)
```


Determina se la stringa specificata contiene un'immagine EMF valida, che è
codificata con base64


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | contentInBase64 | java.lang.String | Stringa, che si presume contenga un'immagine EMF codificata base64 |
|

**Returns:**
boolean - Restituisce 'true' se valido e 'false' se non valido

### saveToSvg(OutputStream outputSvgContent) {#saveToSvg-java.io.OutputStream-}
```
public abstract void saveToSvg(OutputStream outputSvgContent)
```


Nel tipo di implementazione dovrebbe salvare la meta-immagine vettoriale corrente nel
formato SVG vettoriale nel flusso di byte specificato


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | outputSvgContent | java.io.OutputStream | Flusso di byte, nel quale verrà memorizzata la versione SVG di questa meta-immagine vettoriale. Non deve essere NULL e deve supportare la scrittura. |
|

