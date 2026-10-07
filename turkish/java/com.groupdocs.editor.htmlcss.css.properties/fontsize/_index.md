---
title: "FontSize"
second_title: "GroupDocs.Editor Java için API Referansı"
description: "Bir font boyutunu özel bir birim veya uzunluk değeri olarak temsil eder; bu değer, tarihsel olarak büyük M harfinin genişliğini belirler."
type: docs
weight: 10
url: /tr/java/com.groupdocs.editor.htmlcss.css.properties/fontsize/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.groupdocs.editor.htmlcss.css.properties.ICssProperty
```
public class FontSize implements ICssProperty
```

Bir yazı tipi boyutunu özel bir birim veya uzunluk değeri olarak temsil eder, bu değer yazı tipinin boyutunu (tarihsel olarak büyük "M" harfinin genişliği) belirtir.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [FontSize()](#FontSize--) |  |
## Alanlar

| Alan | Açıklama |
| --- | --- |
|  | [Medium](#Medium) | Orta boyut. |
|
|  | [XxSmall](#XxSmall) | Çok küçük mutlak boyut |
|
|  | [XSmall](#XSmall) | Orta derecede küçük mutlak boyut |
|
|  | [Small](#Small) | Normal küçük mutlak boyut |
|
|  | [Large](#Large) | Normal büyük mutlak boyut |
|
|  | [XLarge](#XLarge) | Orta derecede büyük mutlak boyut |
|
|  | [XxLarge](#XxLarge) | Çok büyük mutlak boyut |
|
|  | [Larger](#Larger) | Daha büyük göreli boyut - font, üst öğenin font-boyutuna göre daha büyük olacak, yukarıdaki mutlak boyut anahtar kelimelerini ayırmak için kullanılan oranla yaklaşık olarak. |
|
|  | [Smaller](#Smaller) | Daha küçük göreli boyut - font, üst öğenin font-boyutuna göre daha küçük olacak, yukarıdaki mutlak boyut anahtar kelimelerini ayırmak için kullanılan oranla yaklaşık olarak. |
|
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [isInitial()](#isInitial--) | Bu yazı tipi boyutunun (Medium) bir başlangıç değeri olup olmadığını gösterir |
|
|  | [getValue()](#getValue--) | Bu yazı tipi boyutunun değerini dize olarak döndürür |
|
|  | [isLengthDefined()](#isLengthDefined--) | Bu yazı tipi boyutunun bir [Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) değeriyle tanımlanıp tanımlanmadığını gösterir |
|
|  | [getLength()](#getLength--) | Bu yazı tipi boyutu bununla tanımlanmışsa bir uzunluk değeri, aksi takdirde bir istisna fırlatır |
|
|  | [isAbsoluteSize()](#isAbsoluteSize--) | Bu yazı tipi boyutunun, kullanıcının varsayılan yazı tipi boyutuna (ortadır) dayalı olarak bir anahtar kelimeyle mutlak bir boyut olarak tanımlanıp tanımlanmadığını gösterir |
|
|  | [isRelativeSize()](#isRelativeSize--) | Bu yazı tipi boyutunun bir anahtar kelimeyle göreceli bir boyut olarak tanımlanıp tanımlanmadığını gösterir. |
|
|  | [equals(FontSize other)](#equals-com.groupdocs.editor.htmlcss.css.properties.FontSize-) | Bu yazı tipi boyutu örneğinin belirtilenle eşit olup olmadığını belirler |
|
|  | [equals(Object obj)](#equals-java.lang.Object-) | Bu yazı tipi boyutu örneğinin belirtilen dönüştürülmemiş değerle eşit olup olmadığını belirler |
|
|  | [hashCode()](#hashCode--) | Bu örnek için bir hash kodu döndürür. |
|
|  | [op_Equality(FontSize first, FontSize second)](#op-Equality-com.groupdocs.editor.htmlcss.css.properties.FontSize-com.groupdocs.editor.htmlcss.css.properties.FontSize-) | İki \"FontSize\" değerinin eşit olup olmadığını kontrol eder |
|
|  | [op_Inequality(FontSize first, FontSize second)](#op-Inequality-com.groupdocs.editor.htmlcss.css.properties.FontSize-com.groupdocs.editor.htmlcss.css.properties.FontSize-) | İki \"FontSize\" değerinin eşit olmamasını kontrol eder |
|
|  | [fromLength(Length length)](#fromLength-com.groupdocs.editor.htmlcss.css.datatypes.Length-) | Belirtilen uzunluktan bir yazı tipi boyutu oluşturur |
|
|  | [tryParse(String keyword, FontSize[] result)](#tryParse-java.lang.String-com.groupdocs.editor.htmlcss.css.properties.FontSize---) | Belirtilen bir anahtar kelimeyi 'font-size' için uygun bir anahtar kelime değeri olarak tanımaya çalışır ve başarılı olursa döndürür, başarısız olursa NULL döndürür. |
|
### FontSize() {#FontSize--}
```
public FontSize()
```


### Medium {#Medium}
```
public static final FontSize Medium
```


Orta boyut. Başlangıç değeri.


### XxSmall {#XxSmall}
```
public static final FontSize XxSmall
```


Çok küçük mutlak boyut


### XSmall {#XSmall}
```
public static final FontSize XSmall
```


Orta derecede küçük mutlak boyut


### Small {#Small}
```
public static final FontSize Small
```


Normal küçük mutlak boyut


### Large {#Large}
```
public static final FontSize Large
```


Normal büyük mutlak boyut


### XLarge {#XLarge}
```
public static final FontSize XLarge
```


Orta derecede büyük mutlak boyut


### XxLarge {#XxLarge}
```
public static final FontSize XxLarge
```


Çok büyük mutlak boyut


### Larger {#Larger}
```
public static final FontSize Larger
```


Daha büyük göreli boyut - font, üst öğenin font-boyutuna göre daha büyük olacak, yukarıdaki mutlak boyut anahtar kelimelerini ayırmak için kullanılan oranla yaklaşık olarak.


### Smaller {#Smaller}
```
public static final FontSize Smaller
```


Daha küçük göreli boyut - font, üst öğenin font-boyutuna göre daha küçük olacak, yukarıdaki mutlak boyut anahtar kelimelerini ayırmak için kullanılan oranla yaklaşık olarak.


### isInitial() {#isInitial--}
```
public final boolean isInitial()
```


Bu yazı tipi boyutunun (Medium) bir başlangıç değeri olup olmadığını gösterir


**Returns:**
boolean
### getValue() {#getValue--}
```
public final String getValue()
```


Bu yazı tipi boyutunun değerini dize olarak döndürür


**Returns:**
java.lang.String
### isLengthDefined() {#isLengthDefined--}
```
public final boolean isLengthDefined()
```


Bu yazı tipi boyutunun bir [Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) değeriyle tanımlanıp tanımlanmadığını gösterir


**Returns:**
boolean
### getLength() {#getLength--}
```
public final Length getLength()
```


Bu yazı tipi boyutu bununla tanımlanmışsa bir uzunluk değeri, aksi takdirde bir istisna fırlatır


**Returns:**
[Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length)
### isAbsoluteSize() {#isAbsoluteSize--}
```
public final boolean isAbsoluteSize()
```


Bu yazı tipi boyutunun, kullanıcının varsayılan yazı tipi boyutuna (ortadır) dayalı olarak bir anahtar kelimeyle mutlak bir boyut olarak tanımlanıp tanımlanmadığını gösterir


**Returns:**
boolean
### isRelativeSize() {#isRelativeSize--}
```
public final boolean isRelativeSize()
```


Bu yazı tipi boyutunun bir anahtar kelimeyle göreceli bir boyut olarak tanımlanıp tanımlanmadığını gösterir. Yazı tipi, üst öğenin yazı tipi boyutuna göre, mutlak boyut anahtar kelimelerini ayırmak için kullanılan oranla yaklaşık olarak daha büyük veya daha küçük olacaktır.


**Returns:**
boolean
### equals(FontSize other) {#equals-com.groupdocs.editor.htmlcss.css.properties.FontSize-}
```
public final boolean equals(FontSize other)
```


Bu yazı tipi boyutu örneğinin belirtilenle eşit olup olmadığını belirler


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | other | [FontSize](../../com.groupdocs.editor.htmlcss.css.properties/fontsize) | Diğer yazı tipi boyutu örneği |
|

**Returns:**
boolean - eşitse doğru, aksi takdirde yanlış

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Bu yazı tipi boyutu örneğinin belirtilen dönüştürülmemiş değerle eşit olup olmadığını belirler


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | obj | java.lang.Object | Diğer dönüştürülmemiş yazı tipi boyutu örneği, null olabilir |
|

**Returns:**
boolean - eşitse doğru, eşit değilse, null ise veya başka bir türde ise yanlış

### hashCode() {#hashCode--}
```
public int hashCode()
```


Bu örnek için bir hash kodu döndürür.


**Returns:**
int - imzalı bir tam sayı olarak hash kodu

### op_Equality(FontSize first, FontSize second) {#op-Equality-com.groupdocs.editor.htmlcss.css.properties.FontSize-com.groupdocs.editor.htmlcss.css.properties.FontSize-}
```
public static boolean op_Equality(FontSize first, FontSize second)
```


İki \"FontSize\" değerinin eşit olup olmadığını kontrol eder


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | first | [FontSize](../../com.groupdocs.editor.htmlcss.css.properties/fontsize) | Kontrol edilecek ilk değer |
|
|  | second | [FontSize](../../com.groupdocs.editor.htmlcss.css.properties/fontsize) | Kontrol edilecek ikinci değer |
|

**Returns:**
boolean - eşitse doğru, aksi takdirde yanlış

### op_Inequality(FontSize first, FontSize second) {#op-Inequality-com.groupdocs.editor.htmlcss.css.properties.FontSize-com.groupdocs.editor.htmlcss.css.properties.FontSize-}
```
public static boolean op_Inequality(FontSize first, FontSize second)
```


İki \"FontSize\" değerinin eşit olmamasını kontrol eder


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | first | [FontSize](../../com.groupdocs.editor.htmlcss.css.properties/fontsize) | Kontrol edilecek ilk değer |
|
|  | second | [FontSize](../../com.groupdocs.editor.htmlcss.css.properties/fontsize) | Kontrol edilecek ikinci değer |
|

**Returns:**
boolean - eşitse yanlış, aksi takdirde doğru

### fromLength(Length length) {#fromLength-com.groupdocs.editor.htmlcss.css.datatypes.Length-}
```
public static FontSize fromLength(Length length)
```


Belirtilen uzunluktan bir yazı tipi boyutu oluşturur


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | length | [Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) | Bir uzunluk değeri, birimsiz ya da negatif olamaz |
|

**Returns:**
[FontSize](../../com.groupdocs.editor.htmlcss.css.properties/fontsize) - New FontSize instance

### tryParse(String keyword, FontSize[] result) {#tryParse-java.lang.String-com.groupdocs.editor.htmlcss.css.properties.FontSize---}
```
public static boolean tryParse(String keyword, FontSize[] result)
```


Belirtilen bir anahtar kelimeyi 'font-size' için uygun bir anahtar kelime değeri olarak tanımaya çalışır ve başarılı olursa döndürür, başarısız olursa NULL döndürür.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | keyword | java.lang.String | Ayrıştırılacak bir anahtar kelime |
|
|  | result | [FontSize\[\]](../../com.groupdocs.editor.htmlcss.css.properties/fontsize) | Sonuç, ayrıştırma başarılıysa, aksi takdirde #Medium.Medium |
|

**Returns:**
boolean - ayrıştırma başarılıysa doğru, aksi takdirde yanlış

