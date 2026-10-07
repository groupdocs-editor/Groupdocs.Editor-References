---
title: "QuoteType"
second_title: "GroupDocs.Editor Java için API Referansı"
description: "Tek tırnak ve çift tırnak karakterlerini temsil eder."
type: docs
weight: 10
url: /tr/java/com.groupdocs.editor.htmlcss.serialization/quotetype/
---
**Inheritance:**
java.lang.Object
```
public class QuoteType
```

Tek tırnak (') ve çift tırnak (\") karakterlerini temsil eder.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [QuoteType()](#QuoteType--) |  |
## Alanlar

| Alan | Açıklama |
| --- | --- |
|  | [SingleQuote](#SingleQuote) | Tek tırnak (U+0027 APOSTROPHE karakteri) |
|
|  | [DoubleQuote](#DoubleQuote) | Çift tırnak (U+0022 QUOTATION MARK karakteri) |
|
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [getCode()](#getCode--) | Geçerli karakterin kod noktası (U+0027 veya U+0022) |
|
|  | [getCharacter()](#getCharacter--) | Alıntılanacak karakter |
|
|  | [getHtmlEncoded()](#getHtmlEncoded--) | HTML kodlu karakter |
|
|  | [toString()](#toString--) | Geçerli değere bağlı olarak "SingleQuote" veya "DoubleQuote" dizesi döndürür. |
|
|  | [equals(QuoteType other)](#equals-com.groupdocs.editor.htmlcss.serialization.QuoteType-) | Bu alıntı tipi örneğinin belirtilen ile eşit olup olmadığını gösterir. |
|
|  | [equals(Object obj)](#equals-java.lang.Object-) | Bu alıntı tipi örneğinin belirtilen dönüştürülmemiş değerle eşit olup olmadığını gösterir. |
|
|  | [hashCode()](#hashCode--) | Bu karakter için bir hash kodu döndürür. |
|
|  | [op_Equality(QuoteType first, QuoteType second)](#op-Equality-com.groupdocs.editor.htmlcss.serialization.QuoteType-com.groupdocs.editor.htmlcss.serialization.QuoteType-) | İki "QuoteType" değerinin eşit olup olmadığını denetler. |
|
|  | [op_Inequality(QuoteType first, QuoteType second)](#op-Inequality-com.groupdocs.editor.htmlcss.serialization.QuoteType-com.groupdocs.editor.htmlcss.serialization.QuoteType-) | İki "QuoteType" değerinin eşit olmamasını kontrol eder |
|
|  | [to_Char(QuoteType quote)](#to-Char-com.groupdocs.editor.htmlcss.serialization.QuoteType-) | Belirtilen [QuoteType](../../com.groupdocs.editor.htmlcss.serialization/quotetype) örneğini char tipine dönüştürür |
|
|  | [to_QuoteType(char character)](#to-QuoteType-char-) | Belirli char değerini karşılık gelen [QuoteType](../../com.groupdocs.editor.htmlcss.serialization/quotetype) tipine dönüştürür, dönüşüm geçersizse istisna fırlatır |
|
### QuoteType() {#QuoteType--}
```
public QuoteType()
```


### SingleQuote {#SingleQuote}
```
public static final QuoteType SingleQuote
```


Tek tırnak (U+0027 APOSTROPHE karakteri)


### DoubleQuote {#DoubleQuote}
```
public static final QuoteType DoubleQuote
```


Çift tırnak (U+0022 QUOTATION MARK karakteri)


### getCode() {#getCode--}
```
public final int getCode()
```


Geçerli karakterin kod noktası (U+0027 veya U+0022)


**Returns:**
int
### getCharacter() {#getCharacter--}
```
public final char getCharacter()
```


Alıntılanacak karakter


**Returns:**
char
### getHtmlEncoded() {#getHtmlEncoded--}
```
public final String getHtmlEncoded()
```


HTML kodlu karakter


**Returns:**
java.lang.String
### toString() {#toString--}
```
public String toString()
```


Geçerli değere bağlı olarak "SingleQuote" veya "DoubleQuote" dizesi döndürür.


**Returns:**
java.lang.String -
### equals(QuoteType other) {#equals-com.groupdocs.editor.htmlcss.serialization.QuoteType-}
```
public final boolean equals(QuoteType other)
```


Bu alıntı tipi örneğinin belirtilen ile eşit olup olmadığını gösterir.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | other | [QuoteType](../../com.groupdocs.editor.htmlcss.serialization/quotetype) | Kontrol edilecek QuoteType'ın diğer örneği |
|

**Returns:**
boolean - eşitse true, eşit değilse false

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Bu alıntı tipi örneğinin belirtilen dönüştürülmemiş değerle eşit olup olmadığını gösterir.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | obj | java.lang.Object | Dönüştürülmemiş nesne, [QuoteType](../../com.groupdocs.editor.htmlcss.serialization/quotetype) tipinde olması beklenir |
|

**Returns:**
boolean - eşitse true, eşit değilse false

### hashCode() {#hashCode--}
```
public int hashCode()
```


Bu karakter için bir hash kodu döndürür.


**Returns:**
int - imzalı bir tam sayı olarak hash kodu

### op_Equality(QuoteType first, QuoteType second) {#op-Equality-com.groupdocs.editor.htmlcss.serialization.QuoteType-com.groupdocs.editor.htmlcss.serialization.QuoteType-}
```
public static boolean op_Equality(QuoteType first, QuoteType second)
```


İki "QuoteType" değerinin eşit olup olmadığını denetler.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | first | [QuoteType](../../com.groupdocs.editor.htmlcss.serialization/quotetype) | Kontrol edilecek ilk değer |
|
|  | second | [QuoteType](../../com.groupdocs.editor.htmlcss.serialization/quotetype) | Kontrol edilecek ikinci değer |
|

**Returns:**
boolean - eşitse doğru, aksi takdirde yanlış

### op_Inequality(QuoteType first, QuoteType second) {#op-Inequality-com.groupdocs.editor.htmlcss.serialization.QuoteType-com.groupdocs.editor.htmlcss.serialization.QuoteType-}
```
public static boolean op_Inequality(QuoteType first, QuoteType second)
```


İki "QuoteType" değerinin eşit olmamasını kontrol eder


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | first | [QuoteType](../../com.groupdocs.editor.htmlcss.serialization/quotetype) | Kontrol edilecek ilk değer |
|
|  | second | [QuoteType](../../com.groupdocs.editor.htmlcss.serialization/quotetype) | Kontrol edilecek ikinci değer |
|

**Returns:**
boolean - eşitse yanlış, aksi takdirde doğru

### to_Char(QuoteType quote) {#to-Char-com.groupdocs.editor.htmlcss.serialization.QuoteType-}
```
public static char to_Char(QuoteType quote)
```


Belirtilen [QuoteType](../../com.groupdocs.editor.htmlcss.serialization/quotetype) örneğini char tipine dönüştürür


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | quote | [QuoteType](../../com.groupdocs.editor.htmlcss.serialization/quotetype) | Dönüştürülecek Quote type örneği |
|

**Returns:**
char
### to_QuoteType(char character) {#to-QuoteType-char-}
```
public static QuoteType to_QuoteType(char character)
```


Belirli char değerini karşılık gelen [QuoteType](../../com.groupdocs.editor.htmlcss.serialization/quotetype) tipine dönüştürür, dönüşüm geçersizse istisna fırlatır


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | karakter | char | Tek tırnak (U+0027 APOSTROPHE) veya çift tırnak (U+0022 QUOTATION MARK) karakteri. Başka bir karakter belirtilirse istisna fırlatılır. |
|

**Returns:**
[QuoteType](../../com.groupdocs.editor.htmlcss.serialization/quotetype)
