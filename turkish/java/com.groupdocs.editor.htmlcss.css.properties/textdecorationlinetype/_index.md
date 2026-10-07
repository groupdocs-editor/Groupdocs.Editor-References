---
title: "TextDecorationLineType"
second_title: "GroupDocs.Editor Java için API Referansı"
description: "Metin süsleme çizgi türlerini (alt çizgi, alt tire, üst çizgi ve üzerinden çizgi (çizgi üzeri)) temsil eder."
type: docs
weight: 13
url: /tr/java/com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.groupdocs.editor.htmlcss.css.properties.ICssProperty
```
public class TextDecorationLineType implements ICssProperty
```

Metin süslemesi çizgi türlerini temsil eder: alt çizgi (underscore), üst çizgi ve üstten çizgi (strikethrough).

<br />

*** ** * ** ***

Değiştirilemez struct. https://developer.mozilla.org/en-US/docs/Web/CSS/text-decoration-line adresine benzer.

<br />


## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [TextDecorationLineType()](#TextDecorationLineType--) |  |
| [TextDecorationLineType(int value)](#TextDecorationLineType-int-) |  |
## Alanlar

| Alan | Açıklama |
| --- | --- |
|  | [None](#None) | Metin dekorasyonu üretmez. |
|
|  | [Underline](#Underline) | Metnin her satırı altı çizili. |
|
|  | [Overline](#Overline) | Metnin her satırının üstünde bir çizgi vardır. |
|
|  | [LineThrough](#LineThrough) | Metnin her satırının ortasından bir çizgi geçer. |
|
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [isInitial()](#isInitial--) | Bu örnek başlangıç değerine sahip olup olmadığını gösterir \\u2014 Yok |
|
|  | [isUnderline()](#isUnderline--) | Alt çizginin (alt tire) etkin olup olduğunu gösterir |
|
|  | [isOverline()](#isOverline--) | Üst çizginin etkin olup olduğunu gösterir |
|
|  | [isLineThrough()](#isLineThrough--) | Üstü çizili (strikethrough) özelliğinin etkin olup olduğunu gösterir |
|
|  | [getValue()](#getValue--) | Bu örnekteki tüm bayrakların değerini metin olarak döndürür |
|
|  | [toString()](#toString--) | Bu örnekteki tüm bayrakların değerini metin olarak döndürür |
|
|  | [equals(TextDecorationLineType other)](#equals-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-) | Bu [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) örneğinin belirtilenle eşit olup olmadığını gösterir |
|
|  | [equals(Object other)](#equals-java.lang.Object-) | Bu [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) örneğinin belirtilen, tip dönüşümü yapılmamış haliyle eşit olup olmadığını gösterir |
|
|  | [hashCode()](#hashCode--) | Bu örneğin hash kodunu döndürür |
|
|  | [op_Equality(TextDecorationLineType first, TextDecorationLineType second)](#op-Equality-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-) | İki \"TextDecorationLineType\" değerinin eşit olup olmadığını denetler |
|
|  | [op_Inequality(TextDecorationLineType first, TextDecorationLineType second)](#op-Inequality-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-) | İki \"TextDecorationLineType\" değerinin eşit olmama durumunu denetler |
|
|  | [fromFlags(boolean isUnderline, boolean isOverline, boolean isLineThrough)](#fromFlags-boolean-boolean-boolean-) | Belirtilen parametrelerle tanımlanan bayraklarla bir [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) örneği oluşturur ve döndürür |
|
|  | [tryParse(String input, TextDecorationLineType[] output)](#tryParse-java.lang.String-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType---) | Belirtilen bir dizeyi ayrıştırmayı dener ve geçerli bir [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) örneği döndürür |
|
|  | [op_Addition(TextDecorationLineType first, TextDecorationLineType second)](#op-Addition-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-) | İki belirtilen satır tipini birleştirir (birleştirir) ve bayrakların birleştirildiği (birleşim) yeni bir sonuç satır tipi üretir |
|
|  | [op_Subtraction(TextDecorationLineType first, TextDecorationLineType second)](#op-Subtraction-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-) | İkinci belirtilen satır tipini birinci belirtilen satır tipinden çıkarır ve yalnızca birinci operanda bulunan, ikinci operanda bulunmayan bayrakların yer aldığı (fark) yeni bir sonuç satır tipi üretir |
|
|  | [op_Division(TextDecorationLineType first, TextDecorationLineType second)](#op-Division-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-) | İlk ve ikinci satır tipleri arasındaki kesişimi döndürür; yalnızca her iki operanda da aynı anda etkin olan bayraklar etkinleştirilir. |
|
|  | [to_TextDecorationLineType(byte octet)](#to-TextDecorationLineType-byte-) | Belirli bir baytı (8-bit oktet) ilgili [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) tipine dönüştürür, dönüşüm geçersizse istisna fırlatır |
|
### TextDecorationLineType() {#TextDecorationLineType--}
```
public TextDecorationLineType()
```


### TextDecorationLineType(int value) {#TextDecorationLineType-int-}
```
public TextDecorationLineType(int value)
```


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### None {#None}
```
public static final TextDecorationLineType None
```


Metin dekorasyonu üretmez. Başlangıç değeri.


### Underline {#Underline}
```
public static final TextDecorationLineType Underline
```


Metnin her satırı altı çizili.


### Overline {#Overline}
```
public static final TextDecorationLineType Overline
```


Metnin her satırının üstünde bir çizgi vardır.


### LineThrough {#LineThrough}
```
public static final TextDecorationLineType LineThrough
```


Metnin her satırının ortasından bir çizgi geçer.


### isInitial() {#isInitial--}
```
public final boolean isInitial()
```


Bu örnek başlangıç değerine sahip olup olmadığını gösterir \\u2014 Yok


**Returns:**
boolean
### isUnderline() {#isUnderline--}
```
public final boolean isUnderline()
```


Alt çizginin (alt tire) etkin olup olduğunu gösterir


**Returns:**
boolean
### isOverline() {#isOverline--}
```
public final boolean isOverline()
```


Üst çizginin etkin olup olduğunu gösterir


**Returns:**
boolean
### isLineThrough() {#isLineThrough--}
```
public final boolean isLineThrough()
```


Üstü çizili (strikethrough) özelliğinin etkin olup olduğunu gösterir


**Returns:**
boolean
### getValue() {#getValue--}
```
public final String getValue()
```


Bu örnekteki tüm bayrakların değerini metin olarak döndürür


**Returns:**
java.lang.String
### toString() {#toString--}
```
public String toString()
```


Bu örnekteki tüm bayrakların değerini metin olarak döndürür


**Returns:**
java.lang.String
### equals(TextDecorationLineType other) {#equals-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-}
```
public final boolean equals(TextDecorationLineType other)
```


Bu [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) örneğinin belirtilenle eşit olup olmadığını gösterir


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | other | [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) | Diğer [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) örneği |
|

**Returns:**
boolean -  true  eşitse,  false  aksi takdirde

### equals(Object other) {#equals-java.lang.Object-}
```
public boolean equals(Object other)
```


Bu [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) örneğinin belirtilen, tip dönüşümü yapılmamış haliyle eşit olup olmadığını gösterir


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | other | java.lang.Object | Diğer [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) örneği, nesneye dönüştürülmüş |
|

**Returns:**
boolean -  true  eşitse,  false  aksi takdirde

### hashCode() {#hashCode--}
```
public int hashCode()
```


Bu örneğin hash kodunu döndürür


**Returns:**
int - İşaretli tamsayı karma kodu

### op_Equality(TextDecorationLineType first, TextDecorationLineType second) {#op-Equality-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-}
```
public static boolean op_Equality(TextDecorationLineType first, TextDecorationLineType second)
```


İki \"TextDecorationLineType\" değerinin eşit olup olmadığını denetler


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | first | [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) | Kontrol edilecek ilk işlenen |
|
|  | second | [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) | Kontrol edilecek ikinci işlenen |
|

**Returns:**
boolean -  true  eşitse,  false  aksi takdirde

### op_Inequality(TextDecorationLineType first, TextDecorationLineType second) {#op-Inequality-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-}
```
public static boolean op_Inequality(TextDecorationLineType first, TextDecorationLineType second)
```


İki \"TextDecorationLineType\" değerinin eşit olmama durumunu denetler


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | first | [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) | Kontrol edilecek ilk işlenen |
|
|  | second | [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) | Kontrol edilecek ikinci işlenen |
|

**Returns:**
boolean -  eşit değilse true,  aksi takdirde false

### fromFlags(boolean isUnderline, boolean isOverline, boolean isLineThrough) {#fromFlags-boolean-boolean-boolean-}
```
public static TextDecorationLineType fromFlags(boolean isUnderline, boolean isOverline, boolean isLineThrough)
```


Belirtilen parametrelerle tanımlanan bayraklarla bir [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) örneği oluşturur ve döndürür


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | isUnderline | boolean | Alt çizgi bayrağının etkin olup olmadığını belirler |
|
|  | isOverline | boolean | Üst çizgi bayrağının etkin olup olmadığını belirler |
|
|  | isLineThrough | boolean | Üstü çizili bayrağın etkin olup olmadığını belirler |
|

**Returns:**
[TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) - New [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) instance

### tryParse(String input, TextDecorationLineType[] output) {#tryParse-java.lang.String-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType---}
```
public static boolean tryParse(String input, TextDecorationLineType[] output)
```


Belirtilen bir dizeyi ayrıştırmayı dener ve geçerli bir [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) örneği döndürür


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | girdi | java.lang.String | Girdi dizesi |
|
|  | output | [TextDecorationLineType\[\]](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) | Sonuç. Ayrıştırma geçersizse, #None.None değeri olur |
|

**Returns:**
boolean -  ayrıştırma başarılıysa true,  başarısızlıkta false

### op_Addition(TextDecorationLineType first, TextDecorationLineType second) {#op-Addition-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-}
```
public static TextDecorationLineType op_Addition(TextDecorationLineType first, TextDecorationLineType second)
```


İki belirtilen satır tipini birleştirir (birleştirir) ve bayrakların birleştirildiği (birleşim) yeni bir sonuç satır tipi üretir


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | first | [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) | İlk satır tipi işlenen |
|
|  | second | [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) | İkinci satır tipi işlenen |
|

**Returns:**
[TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) - Result of the union between specified operands

### op_Subtraction(TextDecorationLineType first, TextDecorationLineType second) {#op-Subtraction-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-}
```
public static TextDecorationLineType op_Subtraction(TextDecorationLineType first, TextDecorationLineType second)
```


İkinci belirtilen satır tipini birinci belirtilen satır tipinden çıkarır ve yalnızca birinci operanda bulunan, ikinci operanda bulunmayan bayrakların yer aldığı (fark) yeni bir sonuç satır tipi üretir


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | first | [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) | İlk satır tipi işlenen |
|
|  | second | [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) | İkinci satır tipi işlenen |
|

**Returns:**
[TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) - Result of the difference between the first (minuend) and second (subtrahend) operands

### op_Division(TextDecorationLineType first, TextDecorationLineType second) {#op-Division-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-}
```
public static TextDecorationLineType op_Division(TextDecorationLineType first, TextDecorationLineType second)
```


İlk ve ikinci satır tipleri arasındaki kesişimi döndürür; yalnızca her iki işlenen içinde aynı anda etkin olan bayraklar etkinleştirilir. Tüm operatörler arasında en yüksek önceliğe sahiptir (birleşim ve fark işleminden daha yüksek)


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | first | [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) | İlk satır tipi işlenen |
|
|  | second | [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) | İkinci satır tipi işlenen |
|

**Returns:**
[TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) - Result of the intersection between specified operands

### to_TextDecorationLineType(byte octet) {#to-TextDecorationLineType-byte-}
```
public static TextDecorationLineType to_TextDecorationLineType(byte octet)
```


Belirli bir baytı (8-bit oktet) ilgili [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) tipine dönüştürür, dönüşüm geçersizse istisna fırlatır


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | oktet | bayt | 5 öncü biti sıfır, son 3 biti bayrakları gösteren 8-bit oktet (bit alanı) |
|

**Returns:**
[TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype)
