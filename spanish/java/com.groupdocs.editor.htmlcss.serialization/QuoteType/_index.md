---
title: "QuoteType"
second_title: "GroupDocs.Editor for Java API Reference"
description: "Representa los caracteres de comilla - comilla simple y comilla doble"
type: docs
weight: 10
url: /es/java/com.groupdocs.editor.htmlcss.serialization/quotetype/
---
**Inheritance:**
java.lang.Object
```
public class QuoteType
```

Representa los caracteres de comilla - comilla simple (') y comilla doble (\")

## Constructores

| Constructor | Descripción |
| --- | --- |
| [QuoteType()](#QuoteType--) |  |
## Campos

| Campo | Descripción |
| --- | --- |
|  | [SingleQuote](#SingleQuote) | Comilla simple (carácter U+0027 APOSTROPHE) |
|
|  | [DoubleQuote](#DoubleQuote) | Comilla doble (carácter U+0022 QUOTATION MARK) |
|
## Métodos

| Método | Descripción |
| --- | --- |
|  | [getCode()](#getCode--) | Punto de código del carácter actual (U+0027 o U+0022) |
|
|  | [getCharacter()](#getCharacter--) | Carácter a entrecomillar |
|
|  | [getHtmlEncoded()](#getHtmlEncoded--) | Carácter codificado en HTML |
|
|  | [toString()](#toString--) | Devuelve una cadena "SingleQuote" o "DoubleQuote" según el valor actual |
|
|  | [equals(QuoteType other)](#equals-com.groupdocs.editor.htmlcss.serialization.QuoteType-) | Indica si esta instancia del tipo de comilla es igual a la especificada |
|
|  | [equals(Object obj)](#equals-java.lang.Object-) | Indica si esta instancia del tipo de comilla es igual a la especificada sin convertir |
|
|  | [hashCode()](#hashCode--) | Devuelve un código hash para este carácter |
|
|  | [op_Equality(QuoteType first, QuoteType second)](#op-Equality-com.groupdocs.editor.htmlcss.serialization.QuoteType-com.groupdocs.editor.htmlcss.serialization.QuoteType-) | Comprueba si dos valores "QuoteType" son iguales |
|
|  | [op_Inequality(QuoteType first, QuoteType second)](#op-Inequality-com.groupdocs.editor.htmlcss.serialization.QuoteType-com.groupdocs.editor.htmlcss.serialization.QuoteType-) | Comprueba si dos valores "QuoteType" no son iguales |
|
|  | [to_Char(QuoteType quote)](#to-Char-com.groupdocs.editor.htmlcss.serialization.QuoteType-) | Convierte la instancia especificada de [QuoteType](../../com.groupdocs.editor.htmlcss.serialization/quotetype) al char |
|
|  | [to_QuoteType(char character)](#to-QuoteType-char-) | Convierte el char específico al [QuoteType](../../com.groupdocs.editor.htmlcss.serialization/quotetype) correspondiente, lanza una excepción si la conversión es inválida |
|
### QuoteType() {#QuoteType--}
```
public QuoteType()
```


### SingleQuote {#SingleQuote}
```
public static final QuoteType SingleQuote
```


Comilla simple (carácter U+0027 APOSTROPHE)


### DoubleQuote {#DoubleQuote}
```
public static final QuoteType DoubleQuote
```


Comilla doble (carácter U+0022 QUOTATION MARK)


### getCode() {#getCode--}
```
public final int getCode()
```


Punto de código del carácter actual (U+0027 o U+0022)


**Returns:**
int
### getCharacter() {#getCharacter--}
```
public final char getCharacter()
```


Carácter a entrecomillar


**Returns:**
char
### getHtmlEncoded() {#getHtmlEncoded--}
```
public final String getHtmlEncoded()
```


Carácter codificado en HTML


**Returns:**
java.lang.String
### toString() {#toString--}
```
public String toString()
```


Devuelve una cadena "SingleQuote" o "DoubleQuote" según el valor actual


**Returns:**
java.lang.String -
### equals(QuoteType other) {#equals-com.groupdocs.editor.htmlcss.serialization.QuoteType-}
```
public final boolean equals(QuoteType other)
```


Indica si esta instancia del tipo de comilla es igual a la especificada


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | other | [QuoteType](../../com.groupdocs.editor.htmlcss.serialization/quotetype) | Otra instancia de QuoteType para verificar |
|

**Returns:**
boolean - verdadero si son iguales, falso si son diferentes

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Indica si esta instancia del tipo de comilla es igual a la especificada sin convertir


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | obj | java.lang.Object | Objeto no convertido, se espera que sea del tipo [QuoteType](../../com.groupdocs.editor.htmlcss.serialization/quotetype) |
|

**Returns:**
boolean - verdadero si son iguales, falso si son diferentes

### hashCode() {#hashCode--}
```
public int hashCode()
```


Devuelve un código hash para este carácter


**Returns:**
int - Hash-code como un entero con signo

### op_Equality(QuoteType first, QuoteType second) {#op-Equality-com.groupdocs.editor.htmlcss.serialization.QuoteType-com.groupdocs.editor.htmlcss.serialization.QuoteType-}
```
public static boolean op_Equality(QuoteType first, QuoteType second)
```


Comprueba si dos valores "QuoteType" son iguales


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | first | [QuoteType](../../com.groupdocs.editor.htmlcss.serialization/quotetype) | Primer valor a comprobar |
|
|  | second | [QuoteType](../../com.groupdocs.editor.htmlcss.serialization/quotetype) | Segundo valor a comprobar |
|

**Returns:**
boolean - true si son iguales, false de lo contrario

### op_Inequality(QuoteType first, QuoteType second) {#op-Inequality-com.groupdocs.editor.htmlcss.serialization.QuoteType-com.groupdocs.editor.htmlcss.serialization.QuoteType-}
```
public static boolean op_Inequality(QuoteType first, QuoteType second)
```


Comprueba si dos valores "QuoteType" no son iguales


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | first | [QuoteType](../../com.groupdocs.editor.htmlcss.serialization/quotetype) | Primer valor a comprobar |
|
|  | second | [QuoteType](../../com.groupdocs.editor.htmlcss.serialization/quotetype) | Segundo valor a comprobar |
|

**Returns:**
boolean - false si son iguales, true de lo contrario

### to_Char(QuoteType quote) {#to-Char-com.groupdocs.editor.htmlcss.serialization.QuoteType-}
```
public static char to_Char(QuoteType quote)
```


Convierte la instancia especificada de [QuoteType](../../com.groupdocs.editor.htmlcss.serialization/quotetype) al char


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | quote | [QuoteType](../../com.groupdocs.editor.htmlcss.serialization/quotetype) | Instancia de QuoteType para convertir |
|

**Returns:**
char
### to_QuoteType(char character) {#to-QuoteType-char-}
```
public static QuoteType to_QuoteType(char character)
```


Convierte el char específico al [QuoteType](../../com.groupdocs.editor.htmlcss.serialization/quotetype) correspondiente, lanza una excepción si la conversión es inválida


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | character | char | Un carácter de comilla simple (U+0027 APOSTROPHE) o comilla doble (U+0022 QUOTATION MARK). Se lanzará una excepción si se especifica cualquier otro carácter. |
|

**Returns:**
[QuoteType](../../com.groupdocs.editor.htmlcss.serialization/quotetype)
