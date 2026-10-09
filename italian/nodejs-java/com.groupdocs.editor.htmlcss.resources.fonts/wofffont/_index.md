---
title: "WoffFont"
second_title: "Riferimento API di GroupDocs.Editor per Node.js via Java"
description: "Rappresenta un font nel formato WOFF Web Open Font Format"
type: docs
weight: 17
url: /it/nodejs-java/com.groupdocs.editor.htmlcss.resources.fonts/wofffont/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.htmlcss.resources.fonts.FontResourceBase](../../com.groupdocs.editor.htmlcss.resources.fonts/fontresourcebase)
```
public final class WoffFont extends FontResourceBase
```

Rappresenta un font nel formato WOFF (Web Open Font Format).

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
|  | [WoffFont(String name, String contentInBase64)](#WoffFont-java.lang.String-java.lang.String-) | Crea una nuova classe WoffFont dal contenuto, rappresentato come base64 codificato |
stringa, e con nome specificato
|
|  | [WoffFont(String name, InputStream binaryContent)](#WoffFont-java.lang.String-java.io.InputStream-) | Crea una nuova classe WoffFont dal contenuto, rappresentato come flusso di byte, e |
con nome specificato
|
## Campi

| Campo | Descrizione |
| --- | --- |
|  | [RequiredHeaderSize](#RequiredHeaderSize) | Dimensione dell'intestazione WOFF (in byte), necessaria per la sua validazione |
|
## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [isValid(InputStream binaryContent)](#isValid-java.io.InputStream-) | Verifica se il flusso specificato è un font WOFF valido |
|
|  | [isValid(String contentInBase64)](#isValid-java.lang.String-) | Verifica se la stringa base64 codificata specificata è un font WOFF valido |
|
|  | [getType()](#getType--) | Restituisce FontType.Woff |
|
### WoffFont(String name, String contentInBase64) {#WoffFont-java.lang.String-java.lang.String-}
```
public WoffFont(String name, String contentInBase64)
```


Crea una nuova classe WoffFont dal contenuto, rappresentato come base64 codificato
stringa, e con nome specificato


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | nome | java.lang.String | Nome del font WOFF. Non può essere nullo, vuoto o contenere solo spazi. |
|
|  | contentInBase64 | java.lang.String | Contenuto come stringa base64 codificata. Non può essere nullo, vuoto o contenere solo spazi. Se non è un contenuto WOFF, verrà sollevata l'eccezione. |
|

### WoffFont(String name, InputStream binaryContent) {#WoffFont-java.lang.String-java.io.InputStream-}
```
public WoffFont(String name, InputStream binaryContent)
```


Crea una nuova classe WoffFont dal contenuto, rappresentato come flusso di byte, e
con nome specificato


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | nome | java.lang.String | Nome del font WOFF. Non può essere nullo, vuoto o contenere solo spazi. |
|
|  | binaryContent | java.io.InputStream | Contenuto come flusso di byte. La lettura inizia dalla posizione originale. Non può essere nullo. Deve essere leggibile e ricercabile. Se questa istanza verrà eliminata, anche questo flusso verrà eliminato. |
|

### RequiredHeaderSize {#RequiredHeaderSize}
```
public static final int RequiredHeaderSize
```


Dimensione dell'intestazione WOFF (in byte), necessaria per la sua validazione


### isValid(InputStream binaryContent) {#isValid-java.io.InputStream-}
```
public static boolean isValid(InputStream binaryContent)
```


Verifica se il flusso specificato è un font WOFF valido


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | binaryContent | java.io.InputStream | Flusso di byte che presumibilmente contiene una risorsa WOFF |
|

**Returns:**
boolean - True se il flusso specificato contiene un font WOFF valido, false altrimenti

### isValid(String contentInBase64) {#isValid-java.lang.String-}
```
public static boolean isValid(String contentInBase64)
```


Verifica se la stringa base64 codificata specificata è un font WOFF valido


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | contentInBase64 | java.lang.String | Contenuto del presumibile font WOFF in forma di stringa base64 codificata |
|

**Returns:**
boolean - True se la stringa specificata contiene un font WOFF valido, false altrimenti

### getType() {#getType--}
```
public FontType getType()
```


Restituisce FontType.Woff


**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype)
