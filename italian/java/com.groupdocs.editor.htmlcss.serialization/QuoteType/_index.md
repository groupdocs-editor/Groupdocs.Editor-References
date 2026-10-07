---
title: "QuoteType"
second_title: "GroupDocs.Editor per Java Riferimento API"
description: "Rappresenta i caratteri di virgolette - virgolette singole e virgolette doppie"
type: docs
weight: 10
url: /it/java/com.groupdocs.editor.htmlcss.serialization/quotetype/
---
**Inheritance:**
java.lang.Object
```
public class QuoteType
```

Rappresenta i caratteri di virgolette - virgolette singole (') e virgolette doppie (\")

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [QuoteType()](#QuoteType--) |  |
## Campi

| Campo | Descrizione |
| --- | --- |
|  | [SingleQuote](#SingleQuote) | Virgoletta singola (carattere U+0027 APOSTROPHE) |
|
|  | [DoubleQuote](#DoubleQuote) | Virgoletta doppia (carattere U+0022 QUOTATION MARK) |
|
## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [getCode()](#getCode--) | Punto di codice del carattere corrente (U+0027 o U+0022) |
|
|  | [getCharacter()](#getCharacter--) | Carattere da citare |
|
|  | [getHtmlEncoded()](#getHtmlEncoded--) | Carattere codificato HTML |
|
|  | [toString()](#toString--) | Restituisce una stringa "SingleQuote" o "DoubleQuote" a seconda del valore corrente |
|
|  | [equals(QuoteType other)](#equals-com.groupdocs.editor.htmlcss.serialization.QuoteType-) | Indica se questa istanza del tipo di virgolette è uguale a quella specificata |
|
|  | [equals(Object obj)](#equals-java.lang.Object-) | Indica se questa istanza del tipo di virgolette è uguale a quella specificata non convertita |
|
|  | [hashCode()](#hashCode--) | Restituisce un codice hash per questo carattere |
|
|  | [op_Equality(QuoteType first, QuoteType second)](#op-Equality-com.groupdocs.editor.htmlcss.serialization.QuoteType-com.groupdocs.editor.htmlcss.serialization.QuoteType-) | Verifica se due valori "QuoteType" sono uguali |
|
|  | [op_Inequality(QuoteType first, QuoteType second)](#op-Inequality-com.groupdocs.editor.htmlcss.serialization.QuoteType-com.groupdocs.editor.htmlcss.serialization.QuoteType-) | Verifica se due valori "QuoteType" non sono uguali |
|
|  | [to_Char(QuoteType quote)](#to-Char-com.groupdocs.editor.htmlcss.serialization.QuoteType-) | Converte l'istanza specificata di [QuoteType](../../com.groupdocs.editor.htmlcss.serialization/quotetype) in char |
|
|  | [to_QuoteType(char character)](#to-QuoteType-char-) | Converte il carattere specifico nel corrispondente [QuoteType](../../com.groupdocs.editor.htmlcss.serialization/quotetype), lancia un'eccezione se la conversione è invalida |
|
### QuoteType() {#QuoteType--}
```
public QuoteType()
```


### SingleQuote {#SingleQuote}
```
public static final QuoteType SingleQuote
```


Virgoletta singola (carattere U+0027 APOSTROPHE)


### DoubleQuote {#DoubleQuote}
```
public static final QuoteType DoubleQuote
```


Virgoletta doppia (carattere U+0022 QUOTATION MARK)


### getCode() {#getCode--}
```
public final int getCode()
```


Punto di codice del carattere corrente (U+0027 o U+0022)


**Returns:**
int
### getCharacter() {#getCharacter--}
```
public final char getCharacter()
```


Carattere da citare


**Returns:**
char
### getHtmlEncoded() {#getHtmlEncoded--}
```
public final String getHtmlEncoded()
```


Carattere codificato HTML


**Returns:**
java.lang.String
### toString() {#toString--}
```
public String toString()
```


Restituisce una stringa "SingleQuote" o "DoubleQuote" a seconda del valore corrente


**Returns:**
java.lang.String -
### equals(QuoteType other) {#equals-com.groupdocs.editor.htmlcss.serialization.QuoteType-}
```
public final boolean equals(QuoteType other)
```


Indica se questa istanza del tipo di virgolette è uguale a quella specificata


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | other | [QuoteType](../../com.groupdocs.editor.htmlcss.serialization/quotetype) | Altra istanza di QuoteType da verificare |
|

**Returns:**
boolean - true se sono uguali, false se sono diversi

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Indica se questa istanza del tipo di virgolette è uguale a quella specificata non convertita


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | obj | java.lang.Object | Oggetto non convertito, previsto di tipo [QuoteType](../../com.groupdocs.editor.htmlcss.serialization/quotetype) |
|

**Returns:**
boolean - true se sono uguali, false se sono diversi

### hashCode() {#hashCode--}
```
public int hashCode()
```


Restituisce un codice hash per questo carattere


**Returns:**
int - Hash-code come intero con segno

### op_Equality(QuoteType first, QuoteType second) {#op-Equality-com.groupdocs.editor.htmlcss.serialization.QuoteType-com.groupdocs.editor.htmlcss.serialization.QuoteType-}
```
public static boolean op_Equality(QuoteType first, QuoteType second)
```


Verifica se due valori "QuoteType" sono uguali


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | first | [QuoteType](../../com.groupdocs.editor.htmlcss.serialization/quotetype) | Primo valore da verificare |
|
|  | second | [QuoteType](../../com.groupdocs.editor.htmlcss.serialization/quotetype) | Secondo valore da verificare |
|

**Returns:**
boolean - true se sono uguali, false altrimenti

### op_Inequality(QuoteType first, QuoteType second) {#op-Inequality-com.groupdocs.editor.htmlcss.serialization.QuoteType-com.groupdocs.editor.htmlcss.serialization.QuoteType-}
```
public static boolean op_Inequality(QuoteType first, QuoteType second)
```


Verifica se due valori "QuoteType" non sono uguali


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | first | [QuoteType](../../com.groupdocs.editor.htmlcss.serialization/quotetype) | Primo valore da verificare |
|
|  | second | [QuoteType](../../com.groupdocs.editor.htmlcss.serialization/quotetype) | Secondo valore da verificare |
|

**Returns:**
boolean - false se sono uguali, true altrimenti

### to_Char(QuoteType quote) {#to-Char-com.groupdocs.editor.htmlcss.serialization.QuoteType-}
```
public static char to_Char(QuoteType quote)
```


Converte l'istanza specificata di [QuoteType](../../com.groupdocs.editor.htmlcss.serialization/quotetype) in char


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | quote | [QuoteType](../../com.groupdocs.editor.htmlcss.serialization/quotetype) | Istanza di tipo Quote da convertire |
|

**Returns:**
char
### to_QuoteType(char character) {#to-QuoteType-char-}
```
public static QuoteType to_QuoteType(char character)
```


Converte il carattere specifico nel corrispondente [QuoteType](../../com.groupdocs.editor.htmlcss.serialization/quotetype), lancia un'eccezione se la conversione è invalida


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | carattere | char | Un carattere di apice singolo (U+0027 APOSTROPHE) o di apice doppio (U+0022 QUOTATION MARK). Verrà lanciata un'eccezione se verrà specificato qualsiasi altro carattere. |
|

**Returns:**
[QuoteType](../../com.groupdocs.editor.htmlcss.serialization/quotetype)
