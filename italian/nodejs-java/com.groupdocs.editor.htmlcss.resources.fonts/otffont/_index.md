---
title: "OtfFont"
second_title: "Riferimento API di GroupDocs.Editor per Node.js via Java"
description: "Rappresenta un font nel formato OTF Open Type Format"
type: docs
weight: 13
url: /it/nodejs-java/com.groupdocs.editor.htmlcss.resources.fonts/otffont/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.htmlcss.resources.fonts.FontResourceBase](../../com.groupdocs.editor.htmlcss.resources.fonts/fontresourcebase)
```
public final class OtfFont extends FontResourceBase
```

Rappresenta un font nel formato OTF (Open Type Format).

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
|  | [OtfFont(String name, String contentInBase64)](#OtfFont-java.lang.String-java.lang.String-) | Crea una nuova classe OtfFont dal contenuto, rappresentato come codificato in base64 |
stringa, e con nome specificato
|
|  | [OtfFont(String name, InputStream binaryContent)](#OtfFont-java.lang.String-java.io.InputStream-) | Crea una nuova classe OtfFont dal contenuto, rappresentato come flusso di byte, e |
con nome specificato
|
## Campi

| Campo | Descrizione |
| --- | --- |
|  | [RequiredHeaderSize](#RequiredHeaderSize) | Dimensione dell'intestazione OTF (in byte), necessaria per la sua convalida |
|
## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [isValid(InputStream binaryContent)](#isValid-java.io.InputStream-) | Verifica se il flusso specificato è un font OTF valido |
|
|  | [isValid(String contentInBase64)](#isValid-java.lang.String-) | Verifica se la stringa codificata in base64 specificata è un font OTF valido |
|
|  | [getType()](#getType--) | Restituisce |
FontType.Otf
([FontType.getOtf](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype#getOtf))
|
### OtfFont(String name, String contentInBase64) {#OtfFont-java.lang.String-java.lang.String-}
```
public OtfFont(String name, String contentInBase64)
```


Crea una nuova classe OtfFont dal contenuto, rappresentato come codificato in base64
stringa, e con nome specificato


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | nome | java.lang.String | Nome del font OTF. Non può essere nullo, vuoto o contenere solo spazi. |
|
|  | contentInBase64 | java.lang.String | Contenuto come stringa codificata in base64. Non può essere nullo, vuoto o contenere solo spazi. Se non è un contenuto OTF, verrà generata un'eccezione. |
|

### OtfFont(String name, InputStream binaryContent) {#OtfFont-java.lang.String-java.io.InputStream-}
```
public OtfFont(String name, InputStream binaryContent)
```


Crea una nuova classe OtfFont dal contenuto, rappresentato come flusso di byte, e
con nome specificato


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | nome | java.lang.String | Nome del font OTF. Non può essere nullo, vuoto o contenere solo spazi. |
|
|  | binaryContent | java.io.InputStream | Contenuto come flusso di byte. La lettura inizia dalla posizione originale. Non può essere nullo. Deve essere leggibile e ricercabile. Se questa istanza verrà eliminata, anche questo flusso verrà eliminato. |
|

### RequiredHeaderSize {#RequiredHeaderSize}
```
public static final int RequiredHeaderSize
```


Dimensione dell'intestazione OTF (in byte), necessaria per la sua convalida


### isValid(InputStream binaryContent) {#isValid-java.io.InputStream-}
```
public static boolean isValid(InputStream binaryContent)
```


Verifica se il flusso specificato è un font OTF valido


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | binaryContent | java.io.InputStream | Flusso di byte, che presumibilmente contiene una risorsa OTF |
|

**Returns:**
boolean - True se il flusso specificato contiene un font OTF valido, false altrimenti

### isValid(String contentInBase64) {#isValid-java.lang.String-}
```
public static boolean isValid(String contentInBase64)
```


Verifica se la stringa codificata in base64 specificata è un font OTF valido


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | contentInBase64 | java.lang.String | Contenuto del presunto font OTF in forma di stringa codificata in base64 |
|

**Returns:**
boolean - True se la stringa specificata contiene un font OTF valido, false altrimenti

### getType() {#getType--}
```
public FontType getType()
```


Restituisce
FontType.Otf
([FontType.getOtf](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype#getOtf))


**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) - 
