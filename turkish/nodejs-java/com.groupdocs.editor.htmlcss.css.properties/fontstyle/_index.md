---
title: "FontStyle"
second_title: "GroupDocs.Editor Node.js için Java API Referansı"
description: "Yazı tipinin font-family'sinden normal, italik veya eğik bir yüzle nasıl stillendirileceğini tanımlar."
type: docs
weight: 11
url: /tr/nodejs-java/com.groupdocs.editor.htmlcss.css.properties/fontstyle/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.groupdocs.editor.htmlcss.css.properties.ICssProperty
```
public class FontStyle implements ICssProperty
```

Yazı tipinin font-family'sinden normal, italik veya eğik bir yüz ile nasıl biçimlendirilmesi gerektiğini tanımlar.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [FontStyle()](#FontStyle--) |  |
## Alanlar

| Alan | Açıklama |
| --- | --- |
|  | [Normal](#Normal) | Bir font-family içinde normal olarak sınıflandırılmış bir yazı tipini seçer. |
|
|  | [Italic](#Italic) | İtalik olarak sınıflandırılmış bir yazı tipini seçer. |
|
|  | [Oblique](#Oblique) | Eğik (oblique) olarak sınıflandırılmış bir yazı tipini seçer. |
|
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [isInitial()](#isInitial--) | Bu font-style'ın başlangıç değerine (Normal) sahip olup olmadığını gösterir. |
|
|  | [getValue()](#getValue--) | Bu font stilinin değerini bir dize olarak döndürür. |
|
|  | [equals(FontStyle other)](#equals-com.groupdocs.editor.htmlcss.css.properties.FontStyle-) | Bu font-style örneğinin belirtilenle eşit olup olmadığını belirler. |
|
|  | [equals(Object obj)](#equals-java.lang.Object-) | Bu font-style örneğinin belirtilen, tip dönüşümü yapılmamış değerle eşit olup olmadığını belirler. |
|
|  | [hashCode()](#hashCode--) | Bu örnek için bir hash kodu döndürür. |
|
|  | [op_Equality(FontStyle first, FontStyle second)](#op-Equality-com.groupdocs.editor.htmlcss.css.properties.FontStyle-com.groupdocs.editor.htmlcss.css.properties.FontStyle-) | İki "FontStyle" değerinin eşit olup olmadığını kontrol eder. |
|
|  | [op_Inequality(FontStyle first, FontStyle second)](#op-Inequality-com.groupdocs.editor.htmlcss.css.properties.FontStyle-com.groupdocs.editor.htmlcss.css.properties.FontStyle-) | İki "FontStyle" değerinin eşit olmama durumunu kontrol eder. |
|
|  | [tryParse(String keyword, FontStyle[] result)](#tryParse-java.lang.String-com.groupdocs.editor.htmlcss.css.properties.FontStyle---) | Belirtilen anahtar kelimeyi 'font-style' için uygun bir anahtar kelime değeri olarak tanımaya çalışır ve başarılı olursa döndürür, başarısız olursa NULL döndürür. |
|
### FontStyle() {#FontStyle--}
```
public FontStyle()
```


### Normal {#Normal}
```
public static final FontStyle Normal
```


Bir font-family içinde normal olarak sınıflandırılmış bir yazı tipini seçer. Başlangıç değeri.


### Italic {#Italic}
```
public static final FontStyle Italic
```


İtalik olarak sınıflandırılmış bir yazı tipini seçer. Eğer yüzün italik versiyonu mevcut değilse, bunun yerine eğik (oblique) olarak sınıflandırılmış bir versiyon kullanılır. Eğer hiçbiri mevcut değilse, stil yapay olarak simüle edilir.


### Oblique {#Oblique}
```
public static final FontStyle Oblique
```


Eğik (oblique) olarak sınıflandırılmış bir yazı tipini seçer. Eğer yüzün eğik versiyonu mevcut değilse, bunun yerine italik olarak sınıflandırılmış bir versiyon kullanılır. Eğer hiçbiri mevcut değilse, stil yapay olarak simüle edilir.


### isInitial() {#isInitial--}
```
public final boolean isInitial()
```


Bu font-style'ın başlangıç değerine (Normal) sahip olup olmadığını gösterir.


**Returns:**
boolean
### getValue() {#getValue--}
```
public final String getValue()
```


Bu font stilinin değerini bir dize olarak döndürür.


**Returns:**
java.lang.String
### equals(FontStyle other) {#equals-com.groupdocs.editor.htmlcss.css.properties.FontStyle-}
```
public final boolean equals(FontStyle other)
```


Bu font-style örneğinin belirtilenle eşit olup olmadığını belirler.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | other | [FontStyle](../../com.groupdocs.editor.htmlcss.css.properties/fontstyle) | Diğer font-style örneği |
|

**Returns:**
boolean - eşit ise true, aksi takdirde false

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Bu font-style örneğinin belirtilen, tip dönüşümü yapılmamış değerle eşit olup olmadığını belirler.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | obj | java.lang.Object | Diğer dönüştürülmemiş font-style örneği, null olabilir |
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

### op_Equality(FontStyle first, FontStyle second) {#op-Equality-com.groupdocs.editor.htmlcss.css.properties.FontStyle-com.groupdocs.editor.htmlcss.css.properties.FontStyle-}
```
public static boolean op_Equality(FontStyle first, FontStyle second)
```


İki "FontStyle" değerinin eşit olup olmadığını kontrol eder.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | first | [FontStyle](../../com.groupdocs.editor.htmlcss.css.properties/fontstyle) | Kontrol edilecek ilk değer |
|
|  | second | [FontStyle](../../com.groupdocs.editor.htmlcss.css.properties/fontstyle) | Kontrol edilecek ikinci değer |
|

**Returns:**
boolean - eşit ise true, aksi takdirde false

### op_Inequality(FontStyle first, FontStyle second) {#op-Inequality-com.groupdocs.editor.htmlcss.css.properties.FontStyle-com.groupdocs.editor.htmlcss.css.properties.FontStyle-}
```
public static boolean op_Inequality(FontStyle first, FontStyle second)
```


İki "FontStyle" değerinin eşit olmama durumunu kontrol eder.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | first | [FontStyle](../../com.groupdocs.editor.htmlcss.css.properties/fontstyle) | Kontrol edilecek ilk değer |
|
|  | second | [FontStyle](../../com.groupdocs.editor.htmlcss.css.properties/fontstyle) | Kontrol edilecek ikinci değer |
|

**Returns:**
boolean - eşit ise false, aksi takdirde true

### tryParse(String keyword, FontStyle[] result) {#tryParse-java.lang.String-com.groupdocs.editor.htmlcss.css.properties.FontStyle---}
```
public static boolean tryParse(String keyword, FontStyle[] result)
```


Belirtilen anahtar kelimeyi 'font-style' için uygun bir anahtar kelime değeri olarak tanımaya çalışır ve başarılı olursa döndürür, başarısız olursa NULL döndürür.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | keyword | java.lang.String | Parse edilecek bir keyword |
|
|  | result | [FontStyle\[\]](../../com.groupdocs.editor.htmlcss.css.properties/fontstyle) | Sonuç, parse başarılı ise, aksi takdirde #Normal.Normal |
|

**Returns:**
boolean - parse başarılı ise true, aksi takdirde false

