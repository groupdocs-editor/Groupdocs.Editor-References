---
title: "FontSize"
second_title: "GroupDocs.Editor Node.js için Java API Referansı"
description: "Font boyutunu özel bir birim veya uzunluk değeri olarak temsil eder; bu değer tarihsel olarak büyük M harfinin genişliğini belirtir."
type: docs
weight: 10
url: /tr/nodejs-java/com.groupdocs.editor.htmlcss.css.properties/fontsize/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.groupdocs.editor.htmlcss.css.properties.ICssProperty
```
public class FontSize implements ICssProperty
```

Bir yazı tipi boyutunu özel bir birim veya uzunluk değeri olarak temsil eder; bu, yazı tipinin boyutunu (tarihsel olarak büyük "M" harfinin genişliği) belirtir.

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
|  | [Small](#Small) | Genellikle küçük mutlak boyut |
|
|  | [Large](#Large) | Genellikle büyük mutlak boyut |
|
|  | [XLarge](#XLarge) | Orta derecede büyük mutlak boyut |
|
|  | [XxLarge](#XxLarge) | Çok büyük mutlak boyut |
|
|  | [Larger](#Larger) | Daha büyük relative-size - font, ebeveyn öğenin font-size'ına göre daha büyük olacaktır, yukarıdaki absolute-size anahtar kelimelerini ayırmak için kullanılan oranla yaklaşık olarak. |
|
|  | [Smaller](#Smaller) | Daha küçük relative-size - font, ebeveyn öğenin font-size'ına göre daha küçük olacaktır, yukarıdaki absolute-size anahtar kelimelerini ayırmak için kullanılan oranla yaklaşık olarak. |
|
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [isInitial()](#isInitial--) | Bu font-size'ın başlangıç değeri (Medium) olup olmadığını gösterir |
|
|  | [getValue()](#getValue--) | Bu font size değerini bir dize olarak döndürür |
|
|  | [isLengthDefined()](#isLengthDefined--) | Bu font-size'ın bir [Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) değeriyle tanımlanıp tanımlanmadığını gösterir |
|
|  | [getLength()](#getLength--) | Bu font-size bu değerle tanımlanmışsa bir uzunluk değeri, aksi takdirde bir istisna fırlatılır |
|
|  | [isAbsoluteSize()](#isAbsoluteSize--) | Bu font-size'ın mutlak bir boyut anahtar kelimesiyle, kullanıcının varsayılan font boyutuna (medium) dayanarak tanımlanıp tanımlanmadığını gösterir |
|
|  | [isRelativeSize()](#isRelativeSize--) | Bu font-size'ın göreceli bir boyut anahtar kelimesiyle tanımlanıp tanımlanmadığını gösterir. |
|
|  | [equals(FontSize other)](#equals-com.groupdocs.editor.htmlcss.css.properties.FontSize-) | Bu font-size örneğinin belirtilenle eşit olup olmadığını belirler |
|
|  | [equals(Object obj)](#equals-java.lang.Object-) | Bu font-size örneğinin belirtilen uncasted değerle eşit olup olmadığını belirler |
|
|  | [hashCode()](#hashCode--) | Bu örnek için bir hash kodu döndürür. |
|
|  | [op_Equality(FontSize first, FontSize second)](#op-Equality-com.groupdocs.editor.htmlcss.css.properties.FontSize-com.groupdocs.editor.htmlcss.css.properties.FontSize-) | İki \"FontSize\" değerinin eşit olup olmadığını kontrol eder |
|
|  | [op_Inequality(FontSize first, FontSize second)](#op-Inequality-com.groupdocs.editor.htmlcss.css.properties.FontSize-com.groupdocs.editor.htmlcss.css.properties.FontSize-) | İki \"FontSize\" değerinin eşit olmamasını kontrol eder |
|
|  | [fromLength(Length length)](#fromLength-com.groupdocs.editor.htmlcss.css.datatypes.Length-) | Belirtilen uzunluktan bir font-size oluşturur |
|
|  | [tryParse(String keyword, FontSize[] result)](#tryParse-java.lang.String-com.groupdocs.editor.htmlcss.css.properties.FontSize---) | Belirtilen anahtar kelimeyi 'font-size' için uygun bir anahtar kelime değeri olarak tanımaya çalışır ve başarılı olduğunda döndürür, başarısız olduğunda NULL döndürür. |
|
### FontSize() {#FontSize--}
```
public FontSize()
```


### Medium {#Medium}
```
public static final FontSize Medium
```


Medium boyut. Başlangıç değeri.


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


Genellikle küçük mutlak boyut


### Large {#Large}
```
public static final FontSize Large
```


Genellikle büyük mutlak boyut


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


Daha büyük relative-size - font, ebeveyn öğenin font-size'ına göre daha büyük olacaktır, yukarıdaki absolute-size anahtar kelimelerini ayırmak için kullanılan oranla yaklaşık olarak.


### Smaller {#Smaller}
```
public static final FontSize Smaller
```


Daha küçük relative-size - font, ebeveyn öğenin font-size'ına göre daha küçük olacaktır, yukarıdaki absolute-size anahtar kelimelerini ayırmak için kullanılan oranla yaklaşık olarak.


### isInitial() {#isInitial--}
```
public final boolean isInitial()
```


Bu font-size'ın başlangıç değeri (Medium) olup olmadığını gösterir


**Returns:**
boolean
### getValue() {#getValue--}
```
public final String getValue()
```


Bu font size değerini bir dize olarak döndürür


**Returns:**
java.lang.String
### isLengthDefined() {#isLengthDefined--}
```
public final boolean isLengthDefined()
```


Bu font-size'ın bir [Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) değeriyle tanımlanıp tanımlanmadığını gösterir


**Returns:**
boolean
### getLength() {#getLength--}
```
public final Length getLength()
```


Bu font-size bu değerle tanımlanmışsa bir uzunluk değeri, aksi takdirde bir istisna fırlatılır


**Returns:**
[Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length)
### isAbsoluteSize() {#isAbsoluteSize--}
```
public final boolean isAbsoluteSize()
```


Bu font-size'ın mutlak bir boyut anahtar kelimesiyle, kullanıcının varsayılan font boyutuna (medium) dayanarak tanımlanıp tanımlanmadığını gösterir


**Returns:**
boolean
### isRelativeSize() {#isRelativeSize--}
```
public final boolean isRelativeSize()
```


Bu font-size'ın göreceli bir boyut anahtar kelimesiyle tanımlanıp tanımlanmadığını gösterir. Font, ebeveyn öğenin font boyutuna göre daha büyük ya da daha küçük olacaktır, mutlak-boyut anahtar kelimelerini ayırmak için kullanılan oran kadar yaklaşık olarak.


**Returns:**
boolean
### equals(FontSize other) {#equals-com.groupdocs.editor.htmlcss.css.properties.FontSize-}
```
public final boolean equals(FontSize other)
```


Bu font-size örneğinin belirtilenle eşit olup olmadığını belirler


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | other | [FontSize](../../com.groupdocs.editor.htmlcss.css.properties/fontsize) | Diğer font-size örneği |
|

**Returns:**
boolean - eşit ise true, aksi takdirde false

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Bu font-size örneğinin belirtilen uncasted değerle eşit olup olmadığını belirler


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | obj | java.lang.Object | Diğer uncasted font-size örneği, null olabilir |
|

**Returns:**
boolean - eşit ise true, eşit değilse false, null veya farklı bir tipte

### hashCode() {#hashCode--}
```
public int hashCode()
```


Bu örnek için bir hash kodu döndürür.


**Returns:**
int - Hash-kod işaretli bir tam sayı olarak

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
boolean - eşit ise true, aksi takdirde false

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
boolean - eşit ise false, aksi takdirde true

### fromLength(Length length) {#fromLength-com.groupdocs.editor.htmlcss.css.datatypes.Length-}
```
public static FontSize fromLength(Length length)
```


Belirtilen uzunluktan bir font-size oluşturur


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


Belirtilen anahtar kelimeyi 'font-size' için uygun bir anahtar kelime değeri olarak tanımaya çalışır ve başarılı olduğunda döndürür, başarısız olduğunda NULL döndürür.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | keyword | java.lang.String | Parse edilecek bir keyword |
|
|  | result | [FontSize\[\]](../../com.groupdocs.editor.htmlcss.css.properties/fontsize) | Sonuç, ayrıştırma başarılıysa, aksi takdirde #Medium.Medium |
|

**Returns:**
boolean - parse başarılı ise true, aksi takdirde false

