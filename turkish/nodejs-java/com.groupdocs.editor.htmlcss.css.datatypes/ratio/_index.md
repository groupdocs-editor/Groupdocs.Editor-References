---
title: "Oran"
second_title: "GroupDocs.Editor Node.js için Java API Referansı"
description: "Oran CSS veri tipini temsil eder; bu tip, medya sorgularında en‑boy oranlarını tanımlamak ve raster görüntülerde pay (numerator) ve payda (denominator) olarak adlandırılan iki birimsiz değer arasındaki oranı belirtmek için kullanılır."
type: docs
weight: 14
url: /tr/nodejs-java/com.groupdocs.editor.htmlcss.css.datatypes/ratio/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.css.datatypes.ICssDataType](../../com.groupdocs.editor.htmlcss.css.datatypes/icssdatatype)
```
public class Ratio implements ICssDataType
```

"ratio" CSS veri tipini temsil eder, bu tip en‑boy oranlarını tanımlamak için kullanılır
medya sorgularında ve raster görüntülerde oranı belirterek
iki birimsiz değer arasında, "numerator" ve "denominator" olarak adlandırılan. Değişmez
yapı.


*** ** * ** ***

https://developer.mozilla.org/en-US/docs/Web/CSS/ratio

<br />


## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [Ratio()](#Ratio--) |  |
## Alanlar

| Alan | Açıklama |
| --- | --- |
|  | [Single](#Single) | Tek varsayılan oran 1/1 |
|
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [getNumerator()](#getNumerator--) | Bu oranın payını döndürür |
|
|  | [getDenominator()](#getDenominator--) | Bu oranın paydasını döndürür |
|
|  | [calculate()](#calculate--) | Bu oranı tek bir kayan nokta sayısı olarak hesaplar ve döndürür |
|
|  | [getInverseRatio()](#getInverseRatio--) | Bu oran için ters (karşılıklı) bir oran üretir ve döndürür |
|
|  | [serializeDefault()](#serializeDefault--) | Bu oranı dizeye serileştirir ve döndürür |
|
|  | [toString()](#toString--) | Bu oranın dize temsili döndürülür; aynı şekilde |
"SerializeDefault()"
|
|  | [isDefault()](#isDefault--) | Bu oranın varsayılan değere sahip olup olmadığını veya "1/1" (Tek) olup olmadığını belirler |
|
|  | [deepClone()](#deepClone--) | Bu oranının tam bir kopyasını döndürür |
|
|  | [equals(Ratio other)](#equals-com.groupdocs.editor.htmlcss.css.datatypes.Ratio-) | Bu örneğin belirtilen \"Ratio\" örneğiyle eşit olup olmadığını belirler |
|
|  | [equals(Object other)](#equals-java.lang.Object-) | Bu örneğin belirtilen tip dönüşümü yapılmamış nesne ile eşit olup olmadığını belirler, |
muhtemelen başka bir \"Ratio\" örneği
|
|  | [op_Equality(Ratio left, Ratio right)](#op-Equality-com.groupdocs.editor.htmlcss.css.datatypes.Ratio-com.groupdocs.editor.htmlcss.css.datatypes.Ratio-) | İki oranı karşılaştırır ve iki oranın eşleşip eşleşmediğini gösteren bir boolean döndürür. |
|
|  | [op_Inequality(Ratio left, Ratio right)](#op-Inequality-com.groupdocs.editor.htmlcss.css.datatypes.Ratio-com.groupdocs.editor.htmlcss.css.datatypes.Ratio-) | İki oranı karşılaştırır ve iki oranın eşleşmediğini gösteren bir boolean döndürür |
eşleşir.
|
|  | [hashCode()](#hashCode--) | Bu örnek için bir hashcode döndürür, bu hashcode örnek yaşam süresi boyunca değiştirilemez |
yaşam süresi
|
|  | [create(int numerator, int denominator)](#create-int-int-) | Belirtilen pay ve ... kullanarak bir Ratio örneği oluşturur ve döndürür |
payda
|
### Ratio() {#Ratio--}
```
public Ratio()
```


### Single {#Single}
```
public static final Ratio Single
```


Tek varsayılan oran 1/1


### getNumerator() {#getNumerator--}
```
public final int getNumerator()
```


Bu oranın payını döndürür


**Returns:**
int
### getDenominator() {#getDenominator--}
```
public final int getDenominator()
```


Bu oranın paydasını döndürür


**Returns:**
int
### calculate() {#calculate--}
```
public final double calculate()
```


Bu oranı tek bir kayan nokta sayısı olarak hesaplar ve döndürür


**Returns:**
double - Çift hassasiyetli kayan nokta sayısı

### getInverseRatio() {#getInverseRatio--}
```
public final Ratio getInverseRatio()
```


Bu oran için ters (karşılıklı) bir oran üretir ve döndürür


**Returns:**
[Ratio](../../com.groupdocs.editor.htmlcss.css.datatypes/ratio) - New Ratio instance, that is an inverse ratio for this one

### serializeDefault() {#serializeDefault--}
```
public final String serializeDefault()
```


Bu oranı dizeye serileştirir ve döndürür


**Returns:**
java.lang.String - \"pay/payda\" formatında dize

### toString() {#toString--}
```
public String toString()
```


Bu oranın dize temsili döndürülür; aynı şekilde
"SerializeDefault()"


**Returns:**
java.lang.String - \"pay/payda\" formatında dize

### isDefault() {#isDefault--}
```
public final boolean isDefault()
```


Bu oranın varsayılan değere sahip olup olmadığını veya "1/1" (Tek) olup olmadığını belirler


**Returns:**
boolean
### deepClone() {#deepClone--}
```
public final Ratio deepClone()
```


Bu oranının tam bir kopyasını döndürür


**Returns:**
[Ratio](../../com.groupdocs.editor.htmlcss.css.datatypes/ratio) - New Ratio instance, that is a full and deep copy of this one

### equals(Ratio other) {#equals-com.groupdocs.editor.htmlcss.css.datatypes.Ratio-}
```
public final boolean equals(Ratio other)
```


Bu örneğin belirtilen \"Ratio\" örneğiyle eşit olup olmadığını belirler


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | other | [Ratio](../../com.groupdocs.editor.htmlcss.css.datatypes/ratio) | Bu ile eşitliği kontrol etmek için diğer Ratio örneği |
|

**Returns:**
boolean - Eşitse True, eşit değilse false

### equals(Object other) {#equals-java.lang.Object-}
```
public boolean equals(Object other)
```


Bu örneğin belirtilen tip dönüşümü yapılmamış nesne ile eşit olup olmadığını belirler,
muhtemelen başka bir \"Ratio\" örneği


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | diğer | java.lang.Object | Bu ile eşitliği kontrol etmek için muhtemelen Ratio tipinde olan diğer System.Object örneği |
|

**Returns:**
boolean - Eşitse True, eşit değilse false

### op_Equality(Ratio left, Ratio right) {#op-Equality-com.groupdocs.editor.htmlcss.css.datatypes.Ratio-com.groupdocs.editor.htmlcss.css.datatypes.Ratio-}
```
public static boolean op_Equality(Ratio left, Ratio right)
```


İki oranı karşılaştırır ve iki oranın eşleşip eşleşmediğini gösteren bir boolean döndürür.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | left | [Ratio](../../com.groupdocs.editor.htmlcss.css.datatypes/ratio) | Kullanılacak ilk oran. |
|
|  | right | [Ratio](../../com.groupdocs.editor.htmlcss.css.datatypes/ratio) | Kullanılacak ikinci oran. |
|

**Returns:**
boolean - Her iki oran eşitse true, aksi takdirde false.

### op_Inequality(Ratio left, Ratio right) {#op-Inequality-com.groupdocs.editor.htmlcss.css.datatypes.Ratio-com.groupdocs.editor.htmlcss.css.datatypes.Ratio-}
```
public static boolean op_Inequality(Ratio left, Ratio right)
```


İki oranı karşılaştırır ve iki oranın eşleşmediğini gösteren bir boolean döndürür
eşleşir.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | left | [Ratio](../../com.groupdocs.editor.htmlcss.css.datatypes/ratio) | Kullanılacak ilk oran. |
|
|  | right | [Ratio](../../com.groupdocs.editor.htmlcss.css.datatypes/ratio) | Kullanılacak ikinci oran. |
|

**Returns:**
boolean - Her iki oran eşit değilse true, aksi takdirde false.

### hashCode() {#hashCode--}
```
public int hashCode()
```


Bu örnek için bir hashcode döndürür, bu hashcode örnek yaşam süresi boyunca değiştirilemez
yaşam süresi


**Returns:**
int - İşaretli 4 bayt tamsayı, bu örnek için değiştirilemez

### create(int numerator, int denominator) {#create-int-int-}
```
public static Ratio create(int numerator, int denominator)
```


Belirtilen pay ve ... kullanarak bir Ratio örneği oluşturur ve döndürür
payda


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | pay | int | Oranın payı. Kesinlikle pozitif bir tamsayı olmalıdır. |
|
|  | payda | int | Oranın paydası. Kesinlikle pozitif bir tamsayı olmalıdır. |
|

**Returns:**
[Ratio](../../com.groupdocs.editor.htmlcss.css.datatypes/ratio) - New Ratio instance

