---
title: "Woff2Font"
second_title: "Riferimento API di GroupDocs.Editor per Node.js via Java"
description: "Rappresenta un font nel formato WOFF2 Web Open Font Format"
type: docs
weight: 16
url: /it/nodejs-java/com.groupdocs.editor.htmlcss.resources.fonts/woff2font/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.htmlcss.resources.fonts.FontResourceBase](../../com.groupdocs.editor.htmlcss.resources.fonts/fontresourcebase)
```
public final class Woff2Font extends FontResourceBase
```

Rappresenta un font nel formato WOFF2 (Web Open Font Format).

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
|  | [Woff2Font(String name, String contentInBase64)](#Woff2Font-java.lang.String-java.lang.String-) | Crea una nuova classe Woff2Font dal contenuto, rappresentato come codificato in base64 |
stringa, e con nome specificato
|
|  | [Woff2Font(String name, InputStream binaryContent)](#Woff2Font-java.lang.String-java.io.InputStream-) | Crea una nuova classe Woff2Font dal contenuto, rappresentato come flusso di byte, e |
con nome specificato
|
## Campi

| Campo | Descrizione |
| --- | --- |
|  | [RequiredHeaderSize](#RequiredHeaderSize) | Dimensione dell'intestazione WOFF2 (in byte), necessaria per la sua validazione |
|
## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [isValid(InputStream binaryContent)](#isValid-java.io.InputStream-) | Verifica se lo stream specificato è un font WOFF2 valido |
|
|  | [isValid(String contentInBase64)](#isValid-java.lang.String-) | Verifica se la stringa codificata in base64 specificata è un font WOFF2 valido |
|
|  | [getType()](#getType--) | Restituisce FontType.Woff2 |
|
### Woff2Font(String name, String contentInBase64) {#Woff2Font-java.lang.String-java.lang.String-}
```
public Woff2Font(String name, String contentInBase64)
```


Crea una nuova classe Woff2Font dal contenuto, rappresentato come codificato in base64
stringa, e con nome specificato


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | nome | java.lang.String | Nome del font WOFF2. Non può essere nullo, vuoto o contenere solo spazi. |
|
|  | contentInBase64 | java.lang.String | Contenuto come stringa codificata in base64. Non può essere nullo, vuoto o contenere spazi. Se non è un contenuto WOFF2, verrà generata un'eccezione. |
|

### Woff2Font(String name, InputStream binaryContent) {#Woff2Font-java.lang.String-java.io.InputStream-}
```
public Woff2Font(String name, InputStream binaryContent)
```


Crea una nuova classe Woff2Font dal contenuto, rappresentato come flusso di byte, e
con nome specificato


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | nome | java.lang.String | Nome del font WOFF2. Non può essere nullo, vuoto o contenere solo spazi. |
|
|  | binaryContent | java.io.InputStream | Contenuto come flusso di byte. La lettura inizia dalla posizione originale. Non può essere nullo. Deve essere leggibile e ricercabile. Se questa istanza verrà eliminata, anche questo flusso verrà eliminato. |
|

### RequiredHeaderSize {#RequiredHeaderSize}
```
public static final int RequiredHeaderSize
```


Dimensione dell'intestazione WOFF2 (in byte), necessaria per la sua validazione


### isValid(InputStream binaryContent) {#isValid-java.io.InputStream-}
```
public static boolean isValid(InputStream binaryContent)
```


Verifica se lo stream specificato è un font WOFF2 valido


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | binaryContent | java.io.InputStream | Flusso di byte, che presumibilmente contiene una risorsa WOFF2 |
|

**Returns:**
boolean - True se il flusso specificato contiene un font WOFF2 valido, false altrimenti

### isValid(String contentInBase64) {#isValid-java.lang.String-}
```
public static boolean isValid(String contentInBase64)
```


Verifica se la stringa codificata in base64 specificata è un font WOFF2 valido


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | contentInBase64 | java.lang.String | Contenuto del presumibile font WOFF2 in forma di stringa codificata in base64 |
|

**Returns:**
boolean - True se la stringa specificata contiene un font WOFF2 valido, false altrimenti

### getType() {#getType--}
```
public FontType getType()
```


Restituisce FontType.Woff2


**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype)
