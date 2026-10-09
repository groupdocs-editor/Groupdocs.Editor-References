---
title: "TtfFont"
second_title: "Riferimento API di GroupDocs.Editor per Node.js via Java"
description: "Rappresenta un font nel formato TTF TrueType Font"
type: docs
weight: 15
url: /it/nodejs-java/com.groupdocs.editor.htmlcss.resources.fonts/ttffont/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.htmlcss.resources.fonts.FontResourceBase](../../com.groupdocs.editor.htmlcss.resources.fonts/fontresourcebase)
```
public final class TtfFont extends FontResourceBase
```

Rappresenta un font nel formato TTF (TrueType Font).

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
|  | [TtfFont(String name, String contentInBase64)](#TtfFont-java.lang.String-java.lang.String-) | Crea una nuova classe TtfFont dal contenuto, rappresentato come base64-encoded |
stringa, e con nome specificato
|
|  | [TtfFont(String name, InputStream binaryContent)](#TtfFont-java.lang.String-java.io.InputStream-) | Crea una nuova classe TtfFont dal contenuto, rappresentato come flusso di byte, e |
con nome specificato
|
## Campi

| Campo | Descrizione |
| --- | --- |
|  | [RequiredHeaderSize](#RequiredHeaderSize) | Dimensione dell'intestazione TTF (in byte), necessaria per la sua validazione |
|
## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [isValid(InputStream binaryContent)](#isValid-java.io.InputStream-) | Verifica se lo stream specificato è un font TTF valido |
|
|  | [isValid(String contentInBase64)](#isValid-java.lang.String-) | Verifica se la stringa base64-encoded specificata è un font TTF valido |
|
|  | [getType()](#getType--) | Restituisce FontType.Ttf |
|
### TtfFont(String name, String contentInBase64) {#TtfFont-java.lang.String-java.lang.String-}
```
public TtfFont(String name, String contentInBase64)
```


Crea una nuova classe TtfFont dal contenuto, rappresentato come base64-encoded
stringa, e con nome specificato


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | nome | java.lang.String | Nome del font TTF. Non può essere null, vuoto o contenere spazi |
|
|  | contentInBase64 | java.lang.String | Contenuto come stringa base64-encoded. Non può essere null, vuoto o contenere spazi. Se non è un contenuto TTF, verrà sollevata un'eccezione. |
|

### TtfFont(String name, InputStream binaryContent) {#TtfFont-java.lang.String-java.io.InputStream-}
```
public TtfFont(String name, InputStream binaryContent)
```


Crea una nuova classe TtfFont dal contenuto, rappresentato come flusso di byte, e
con nome specificato


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | nome | java.lang.String | Nome del font TTF. Non può essere null, vuoto o contenere spazi |
|
|  | binaryContent | java.io.InputStream | Contenuto come flusso di byte. La lettura inizia dalla posizione originale. Non può essere nullo. Deve essere leggibile e ricercabile. Se questa istanza verrà eliminata, anche questo flusso verrà eliminato. |
|

### RequiredHeaderSize {#RequiredHeaderSize}
```
public static final int RequiredHeaderSize
```


Dimensione dell'intestazione TTF (in byte), necessaria per la sua validazione


### isValid(InputStream binaryContent) {#isValid-java.io.InputStream-}
```
public static boolean isValid(InputStream binaryContent)
```


Verifica se lo stream specificato è un font TTF valido


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | binaryContent | java.io.InputStream | Flusso di byte, che presumibilmente contiene una risorsa TTF |
|

**Returns:**
boolean - True se lo stream specificato contiene un font TTF valido, false altrimenti

### isValid(String contentInBase64) {#isValid-java.lang.String-}
```
public static boolean isValid(String contentInBase64)
```


Verifica se la stringa base64-encoded specificata è un font TTF valido


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | contentInBase64 | java.lang.String | Contenuto del presumibile font TTF in forma di stringa base64-encoded |
|

**Returns:**
boolean - True se la stringa specificata contiene un font TTF valido, false altrimenti

### getType() {#getType--}
```
public FontType getType()
```


Restituisce FontType.Ttf


**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype)
