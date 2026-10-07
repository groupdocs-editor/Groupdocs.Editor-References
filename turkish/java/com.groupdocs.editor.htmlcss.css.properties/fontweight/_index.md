---
title: "FontWeight"
second_title: "GroupDocs.Editor Java için API Referansı"
description: "Font-weight özelliği, yazı tipinin ağırlığını veya kalınlığını ayarlar."
type: docs
weight: 12
url: /tr/java/com.groupdocs.editor.htmlcss.css.properties/fontweight/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.groupdocs.editor.htmlcss.css.properties.ICssProperty
```
public class FontWeight implements ICssProperty
```

Font-weight özelliği, yazı tipinin ağırlığını (veya kalınlığını) ayarlar. Mevcut ayarlı font-family'ye bağlı olarak kullanılabilir ağırlıklar değişir.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [FontWeight()](#FontWeight--) |  |
## Alanlar

| Alan | Açıklama |
| --- | --- |
|  | [Lighter](#Lighter) | Üst öğeden bir derece daha hafif bir göreceli yazı tipi ağırlığı |
|
|  | [Bolder](#Bolder) | Üst öğeden bir derece daha ağır bir göreceli yazı tipi ağırlığı |
|
|  | [Normal](#Normal) | Normal yazı tipi ağırlığı. |
|
|  | [Bold](#Bold) | Kalın yazı tipi ağırlığı. |
|
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [isInitial()](#isInitial--) | Bu yazı tipi boyutunun (Medium) bir başlangıç değeri olup olmadığını gösterir |
|
|  | [getNumber()](#getNumber--) | 1 ile 1000 arasında, dahil olmak üzere bir tam sayı döndürür; bu sayı yazı tipinin kalınlığını tanımlar veya mevcut kalınlık mutlak değil, göreceli ise bir istisna fırlatır. |
|
|  | [isAbsolute()](#isAbsolute--) | Bu font-weight örneğinin, yazı tipinin ağırlığının (kalınlığının) mutlak değerini tam sayı olarak saklayıp saklamadığını gösterir. |
|
|  | [isRelative()](#isRelative--) | Bu font-weight örneğinin, yazı tipinin ağırlığının (kalınlığının) göreceli bir değerini - üst öğenin kalınlığıyla karşılaştırarak - saklayıp saklamadığını gösterir. |
|
|  | [getValue()](#getValue--) | Bu font-weight değerini bir dize olarak döndürür. |
|
|  | [equals(FontWeight other)](#equals-com.groupdocs.editor.htmlcss.css.properties.FontWeight-) | Belirtilen FontWeight örneklerinin eşit olup olmadığını belirler. |
|
|  | [equals(Object obj)](#equals-java.lang.Object-) | Bu FontWeight örneğinin belirtilen uncasted ile eşit olup olmadığını belirler. |
|
|  | [hashCode()](#hashCode--) | Bu örnek için bir hash kodu döndürür. |
|
|  | [op_Equality(FontWeight first, FontWeight second)](#op-Equality-com.groupdocs.editor.htmlcss.css.properties.FontWeight-com.groupdocs.editor.htmlcss.css.properties.FontWeight-) | İki \"FontWeight\" değerinin eşit olup olmadığını kontrol eder. |
|
|  | [op_Inequality(FontWeight first, FontWeight second)](#op-Inequality-com.groupdocs.editor.htmlcss.css.properties.FontWeight-com.groupdocs.editor.htmlcss.css.properties.FontWeight-) | İki \"FontWeight\" değerinin eşit olmama durumunu kontrol eder. |
|
|  | [fromNumber(int number)](#fromNumber-int-) | Belirtilen sayıdan bir font-weight oluşturur. |
|
|  | [tryParse(String input, FontWeight[] result)](#tryParse-java.lang.String-com.groupdocs.editor.htmlcss.css.properties.FontWeight---) | Belirtilen dizeyi ayrıştırmayı dener ve başarılı olursa geçerli bir FontWeight örneği döndürür. |
|
### FontWeight() {#FontWeight--}
```
public FontWeight()
```


### Lighter {#Lighter}
```
public static final FontWeight Lighter
```


Üst öğeden bir derece daha hafif bir göreceli yazı tipi ağırlığı


### Bolder {#Bolder}
```
public static final FontWeight Bolder
```


Üst öğeden bir derece daha ağır bir göreceli yazı tipi ağırlığı


### Normal {#Normal}
```
public static final FontWeight Normal
```


Normal font ağırlığı. 400 ile aynı.


### Bold {#Bold}
```
public static final FontWeight Bold
```


Kalın font ağırlığı. 700 ile aynı.


### isInitial() {#isInitial--}
```
public final boolean isInitial()
```


Bu yazı tipi boyutunun (Medium) bir başlangıç değeri olup olmadığını gösterir


**Returns:**
boolean
### getNumber() {#getNumber--}
```
public final int getNumber()
```


1 ile 1000 arasında, dahil olmak üzere bir tam sayı döndürür; bu sayı yazı tipinin kalınlığını tanımlar veya mevcut kalınlık mutlak değil, göreceli ise bir istisna fırlatır.


**Returns:**
int
### isAbsolute() {#isAbsolute--}
```
public final boolean isAbsolute()
```


Bu font-weight örneğinin, yazı tipinin ağırlığının (kalınlığının) mutlak değerini tam sayı olarak saklayıp saklamadığını gösterir.


**Returns:**
boolean
### isRelative() {#isRelative--}
```
public final boolean isRelative()
```


Bu font-weight örneğinin, yazı tipinin ağırlığının (kalınlığının) göreceli bir değerini - üst öğenin kalınlığıyla karşılaştırarak - saklayıp saklamadığını gösterir.


**Returns:**
boolean
### getValue() {#getValue--}
```
public final String getValue()
```


Bu font-weight değerini bir dize olarak döndürür.


**Returns:**
java.lang.String
### equals(FontWeight other) {#equals-com.groupdocs.editor.htmlcss.css.properties.FontWeight-}
```
public final boolean equals(FontWeight other)
```


Belirtilen FontWeight örneklerinin eşit olup olmadığını belirler.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | other | [FontWeight](../../com.groupdocs.editor.htmlcss.css.properties/fontweight) | Eşitliği kontrol etmek için diğer FontWeight örneği. |
|

**Returns:**
boolean - eşitse true, eşit değilse false

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Bu FontWeight örneğinin belirtilen uncasted ile eşit olup olmadığını belirler.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | obj | java.lang.Object | Diğer uncasted FontWeight örneği, null olabilir. |
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

### op_Equality(FontWeight first, FontWeight second) {#op-Equality-com.groupdocs.editor.htmlcss.css.properties.FontWeight-com.groupdocs.editor.htmlcss.css.properties.FontWeight-}
```
public static boolean op_Equality(FontWeight first, FontWeight second)
```


İki \"FontWeight\" değerinin eşit olup olmadığını kontrol eder.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | first | [FontWeight](../../com.groupdocs.editor.htmlcss.css.properties/fontweight) | Kontrol edilecek ilk değer |
|
|  | second | [FontWeight](../../com.groupdocs.editor.htmlcss.css.properties/fontweight) | Kontrol edilecek ikinci değer |
|

**Returns:**
boolean - eşitse doğru, aksi takdirde yanlış

### op_Inequality(FontWeight first, FontWeight second) {#op-Inequality-com.groupdocs.editor.htmlcss.css.properties.FontWeight-com.groupdocs.editor.htmlcss.css.properties.FontWeight-}
```
public static boolean op_Inequality(FontWeight first, FontWeight second)
```


İki \"FontWeight\" değerinin eşit olmama durumunu kontrol eder.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | first | [FontWeight](../../com.groupdocs.editor.htmlcss.css.properties/fontweight) | Kontrol edilecek ilk değer |
|
|  | second | [FontWeight](../../com.groupdocs.editor.htmlcss.css.properties/fontweight) | Kontrol edilecek ikinci değer |
|

**Returns:**
boolean - eşitse yanlış, aksi takdirde doğru

### fromNumber(int number) {#fromNumber-int-}
```
public static FontWeight fromNumber(int number)
```


Belirtilen sayıdan bir font-weight oluşturur.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | number | int | İşaretsiz tam sayı, [1..1000] aralığında olmalıdır. |
|

**Returns:**
[FontWeight](../../com.groupdocs.editor.htmlcss.css.properties/fontweight) - New FontWeight instance or exception

### tryParse(String input, FontWeight[] result) {#tryParse-java.lang.String-com.groupdocs.editor.htmlcss.css.properties.FontWeight---}
```
public static boolean tryParse(String input, FontWeight[] result)
```


Belirtilen dizeyi ayrıştırmayı dener ve başarılı olursa geçerli bir FontWeight örneği döndürür.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | girdi | java.lang.String | Ayrıştırılacak girdi dizesi. |
|
|  | result | [FontWeight\[\]](../../com.groupdocs.editor.htmlcss.css.properties/fontweight) | Başarılı olduğunda geçerli FontWeight değeri, başarısız olduğunda #Normal.Normal. |
|

**Returns:**
boolean - Ayrıştırmanın başarısı (true) veya başarısızlığı (false).

