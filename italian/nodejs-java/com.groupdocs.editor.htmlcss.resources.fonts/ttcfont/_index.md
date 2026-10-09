---
title: "TtcFont"
second_title: "Riferimento API di GroupDocs.Editor per Node.js via Java"
description: "Rappresenta un font nel formato TTC TrueType Collection."
type: docs
weight: 14
url: /it/nodejs-java/com.groupdocs.editor.htmlcss.resources.fonts/ttcfont/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.htmlcss.resources.fonts.FontResourceBase](../../com.groupdocs.editor.htmlcss.resources.fonts/fontresourcebase)
```
public final class TtcFont extends FontResourceBase
```

Rappresenta un font nel formato TTC (TrueType Collection).


Vedi di più: https://docs.fileformat.com/font/ttc/

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
|  | [TtcFont(String name, String contentInBase64)](#TtcFont-java.lang.String-java.lang.String-) | Crea una nuova classe TtcFont dal contenuto, rappresentato come base64 codificato. |
stringa, e con nome specificato
|
|  | [TtcFont(String name, InputStream binaryContent)](#TtcFont-java.lang.String-java.io.InputStream-) | Crea una nuova classe TtcFont dal contenuto, rappresentato come flusso di byte, e |
con nome specificato
|
## Campi

| Campo | Descrizione |
| --- | --- |
|  | [RequiredHeaderSize](#RequiredHeaderSize) | Dimensione dell'intestazione TTC (in byte), necessaria per la sua convalida. |
|
## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [isValid(InputStream binaryContent)](#isValid-java.io.InputStream-) | Verifica se il flusso specificato è un font TTC valido. |
|
|  | [isValid(String contentInBase64)](#isValid-java.lang.String-) | Verifica se la stringa codificata in base64 specificata è un font TTC valido. |
|
|  | [getType()](#getType--) | Restituisce FontType.Ttc |
|
|  | [getHeaderVersion()](#getHeaderVersion--) | Versione dell'intestazione TTC, può essere "1" o "2". |
|
|  | [getFontsNumber()](#getFontsNumber--) | Numero di font in questo TTC. |
|
|  | [getHasDsigTable()](#getHasDsigTable--) | Indica se questo TTC contiene una tabella DSIG. |
|
### TtcFont(String name, String contentInBase64) {#TtcFont-java.lang.String-java.lang.String-}
```
public TtcFont(String name, String contentInBase64)
```


Crea una nuova classe TtcFont dal contenuto, rappresentato come base64 codificato.
stringa, e con nome specificato


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | nome | java.lang.String | Nome del font TTC. Non può essere null, vuoto o contenere solo spazi. |
|
|  | contentInBase64 | java.lang.String | Contenuto come stringa codificata in base64. Non può essere null, vuoto o contenere solo spazi. Se non è un contenuto TTC, verrà sollevata un'eccezione. |
|

### TtcFont(String name, InputStream binaryContent) {#TtcFont-java.lang.String-java.io.InputStream-}
```
public TtcFont(String name, InputStream binaryContent)
```


Crea una nuova classe TtcFont dal contenuto, rappresentato come flusso di byte, e
con nome specificato


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | nome | java.lang.String | Nome del font TTC. Non può essere null, vuoto o contenere solo spazi. |
|
|  | binaryContent | java.io.InputStream | Contenuto come flusso di byte. La lettura inizia dalla posizione originale. Non può essere nullo. Deve essere leggibile e ricercabile. Se questa istanza verrà eliminata, anche questo flusso verrà eliminato. |
|

### RequiredHeaderSize {#RequiredHeaderSize}
```
public static final int RequiredHeaderSize
```


Dimensione dell'intestazione TTC (in byte), necessaria per la sua convalida.


### isValid(InputStream binaryContent) {#isValid-java.io.InputStream-}
```
public static boolean isValid(InputStream binaryContent)
```


Verifica se il flusso specificato è un font TTC valido.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | binaryContent | java.io.InputStream | Flusso di byte, che presumibilmente contiene una risorsa TTC. |
|

**Returns:**
boolean - True se lo stream specificato contiene un font TTC valido, false altrimenti

### isValid(String contentInBase64) {#isValid-java.lang.String-}
```
public static boolean isValid(String contentInBase64)
```


Verifica se la stringa codificata in base64 specificata è un font TTC valido.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | contentInBase64 | java.lang.String | Contenuto del presumibile font TTC in forma di stringa codificata base64 |
|

**Returns:**
boolean - True se la stringa specificata contiene un font TTC valido, false altrimenti

### getType() {#getType--}
```
public FontType getType()
```


Restituisce FontType.Ttc


**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype)
### getHeaderVersion() {#getHeaderVersion--}
```
public byte getHeaderVersion()
```


Versione dell'intestazione TTC, può essere "1" o "2".


**Returns:**
byte
### getFontsNumber() {#getFontsNumber--}
```
public long getFontsNumber()
```


Numero di font in questo TTC.


**Returns:**
long
### getHasDsigTable() {#getHasDsigTable--}
```
public boolean getHasDsigTable()
```


Indica se questo TTC ha una tabella DSIG. La tabella DSIG può essere presente
solo se il TTC ha un Header versione 2.0.


**Returns:**
boolean
