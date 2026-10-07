---
title: "EotFont"
second_title: "GroupDocs.Editor per Java Riferimento API"
description: "Rappresenta un font nel formato EOT Embedded OpenType"
type: docs
weight: 10
url: /it/java/com.groupdocs.editor.htmlcss.resources.fonts/eotfont/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.htmlcss.resources.fonts.FontResourceBase](../../com.groupdocs.editor.htmlcss.resources.fonts/fontresourcebase)
```
public final class EotFont extends FontResourceBase
```

Rappresenta un font nel formato EOT (Embedded OpenType).

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
|  | [EotFont(String name, String contentInBase64)](#EotFont-java.lang.String-java.lang.String-) | Crea una nuova classe EotFont dal contenuto, rappresentato come base64-encoded |
stringa, e con nome specificato
|
|  | [EotFont(String name, InputStream binaryContent)](#EotFont-java.lang.String-java.io.InputStream-) | Crea una nuova classe EotFont dal contenuto, rappresentato come flusso di byte, e |
con nome specificato
|
## Campi

| Campo | Descrizione |
| --- | --- |
|  | [RequiredHeaderSize](#RequiredHeaderSize) | Dimensione dell'intestazione EOT (in byte), necessaria per la sua validazione |
|
## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [isValid(InputStream binaryContent)](#isValid-java.io.InputStream-) | Verifica se il flusso specificato è un font EOT valido |
|
|  | [isValid(String contentInBase64)](#isValid-java.lang.String-) | Verifica se la stringa codificata base64 specificata è un font EOT valido |
|
|  | [getType()](#getType--) | Restituisce FontType.Eot |
|
### EotFont(String name, String contentInBase64) {#EotFont-java.lang.String-java.lang.String-}
```
public EotFont(String name, String contentInBase64)
```


Crea una nuova classe EotFont dal contenuto, rappresentato come base64-encoded
stringa, e con nome specificato


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | nome | java.lang.String | Nome del font EOT. Non può essere nullo, vuoto o contenere spazi. |
|
|  | contentInBase64 | java.lang.String | Contenuto come stringa codificata base64. Non può essere nullo, vuoto o contenere spazi. Se non è un contenuto EOT, verrà generata un'eccezione. |
|

### EotFont(String name, InputStream binaryContent) {#EotFont-java.lang.String-java.io.InputStream-}
```
public EotFont(String name, InputStream binaryContent)
```


Crea una nuova classe EotFont dal contenuto, rappresentato come flusso di byte, e
con nome specificato


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | nome | java.lang.String | Nome del font EOT. Non può essere nullo, vuoto o contenere spazi. |
|
|  | binaryContent | java.io.InputStream | Contenuto come flusso di byte. La lettura inizia dalla posizione originale. Non può essere nullo. Deve essere leggibile e ricercabile. Se questa istanza verrà rilasciata, anche questo flusso verrà rilasciato. |
|

### RequiredHeaderSize {#RequiredHeaderSize}
```
public static final int RequiredHeaderSize
```


Dimensione dell'intestazione EOT (in byte), necessaria per la sua validazione


### isValid(InputStream binaryContent) {#isValid-java.io.InputStream-}
```
public static boolean isValid(InputStream binaryContent)
```


Verifica se il flusso specificato è un font EOT valido


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | binaryContent | java.io.InputStream | Flusso di byte, che presumibilmente contiene una risorsa EOT |
|

**Returns:**
boolean - True se il flusso specificato contiene un font EOT valido, false altrimenti

### isValid(String contentInBase64) {#isValid-java.lang.String-}
```
public static boolean isValid(String contentInBase64)
```


Verifica se la stringa codificata base64 specificata è un font EOT valido


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | contentInBase64 | java.lang.String | Contenuto del presumibile font EOT in forma di stringa codificata base64 |
|

**Returns:**
boolean - True se la stringa specificata contiene un font EOT valido, false altrimenti

### getType() {#getType--}
```
public FontType getType()
```


Restituisce FontType.Eot


**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype)
