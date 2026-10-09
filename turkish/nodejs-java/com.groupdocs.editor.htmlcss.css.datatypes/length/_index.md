---
title: "Uzunluk"
second_title: "GroupDocs.Editor Node.js için Java API Referansı"
description: "Yüzde ve birimsiz tip dahil olmak üzere desteklenen herhangi bir birimde bir CSS uzunluk değerini temsil eder."
type: docs
weight: 12
url: /tr/nodejs-java/com.groupdocs.editor.htmlcss.css.datatypes/length/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.css.datatypes.ICssDataType](../../com.groupdocs.editor.htmlcss.css.datatypes/icssdatatype)
```
public class Length implements ICssDataType
```

Desteklenen herhangi bir birimde, yüzde dahil, bir CSS uzunluk değerini temsil eder.
ve birimsiz tip. Değerler tamsayı veya kayan nokta, negatif, sıfır ve
pozitif. Değiştirilemez yapı.

*** ** * ** ***


Bu tip aşağıdaki CSS veri tiplerini kapsar:

<https://developer.mozilla.org/en-US/docs/Web/CSS/length>

<https://developer.mozilla.org/en-US/docs/Web/CSS/percentage>

<br />


## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [Length()](#Length--) |  |
## Alanlar

| Alan | Açıklama |
| --- | --- |
|  | [UnitlessZero](#UnitlessZero) | Birimsiz tamsayı sıfır - varsayılan değer, varsayılan parametresizle aynı |
yapıcı
|
|  | [OneHundredPercents](#OneHundredPercents) | 100% |
|
|  | [FiftyPercents](#FiftyPercents) | 50% |
|
|  | [ZeroPercents](#ZeroPercents) | 0% |
|
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [fromValueWithUnit(float value, int unit)](#fromValueWithUnit-float-int-) | Belirtilen float sayı ile Length tipinde bir örnek oluşturur ve döndürür |
ve birim
|
|  | [fromValueWithUnit(double value, int unit)](#fromValueWithUnit-double-int-) | Belirtilen double sayı ile Length tipinde bir örnek oluşturur ve döndürür |
ve birim
|
|  | [fromValueWithUnit(int value, int unit)](#fromValueWithUnit-int-int-) | Belirtilen tam sayı ile Length tipinde bir örnek oluşturur ve döndürür |
sayı ve birim
|
|  | [isUnitlessZero()](#isUnitlessZero--) | Bu örneğin birimsiz sıfır olup olmadığını belirler. |
|
|  | [isDefault()](#isDefault--) | Bu Length örneğinin varsayılan bir değere sahip olup olmadığını gösterir \u2014 birimsiz |
sıfır.
|
|  | [getUnitType()](#getUnitType--) | Bu Length örneğinin birim tipini döndürür. |
|
|  | [isInteger()](#isInteger--) | Bu Length örneğinin sayısal değerinin olup olmadığını gösterir |
başlangıçta bir tamsayı (INT32) sayı olarak belirtilmiş ve depolanmıştır
|
|  | [isFloat()](#isFloat--) | Bu Length örneğinin sayısal değerinin olup olmadığını gösterir |
başlangıçta bir kayan nokta (FP32) sayı olarak belirtilmiş ve depolanmıştır
|
|  | [getFloatValue()](#getFloatValue--) | Length örneğinin kayan nokta sayısal değerini döndürür. |
|
|  | [getIntegerValue()](#getIntegerValue--) | Bu Length örneğinin tamsayı sayısal değerini döndürür, eğer |
içsel olarak tamsayı olarak depolanmışsa, aksi takdirde bir istisna fırlatır, eğer
başlangıçta bir kayan nokta sayı olarak depolanmışsa.
|
|  | [isAbsolute()](#isAbsolute--) | Uzunluğun mutlak birimlerde verilip verilmediğini alır. |
|
|  | [isRelative()](#isRelative--) | Uzunluğun göreli birimlerde verilip verilmediğini alır. |
|
|  | [isZero()](#isZero--) | Bu uzunluğun sayısal değerinin sıfır olup olmadığını belirler |
|
|  | [isNegative()](#isNegative--) | Bu uzunluğun sayısal değerinin negatif olup olmadığını belirler |
|
|  | [isPositive()](#isPositive--) | Bu uzunluğun sayısal değerinin pozitif olup olmadığını belirler |
|
|  | [isUnitlessNonZero()](#isUnitlessNonZero--) | Değer birimsiz tiptedir, ancak sıfır değildir - pozitif ya da negatif |
number
|
|  | [toPixel()](#toPixel--) | Uzunluğu mümkünse piksel sayısına dönüştürür. |
|
|  | [to(int unit)](#to-int-) | Uzunluğu mümkünse verilen birime dönüştürür. |
|
|  | [toStringSpecified(int unit)](#toStringSpecified-int-) | Bu uzunluğun belirtilen birim tipinde bir dize temsili döndürür. |
|
|  | [serializeDefault()](#serializeDefault--) | Bu uzunluğun özgün yerel biçiminde bir dize temsili döndürür |
form (saklandığı gibi), uzunluk değerini başka bir birime dönüştürmeden
birim tipi
|
|  | [equals(Length other)](#equals-com.groupdocs.editor.htmlcss.css.datatypes.Length-) | Bu değerin diğer belirtilen uzunluğa eşit olup olmadığını tanımlar |
|
|  | [equals(Object obj)](#equals-java.lang.Object-) | Bu uzunluğun belirtilen nesneye eşit olup olmadığını belirler |
|
|  | [op_Multiply(Length multiplicand, int factor)](#op-Multiply-com.groupdocs.editor.htmlcss.css.datatypes.Length-int-) | Verilen Length'i verilen faktörle çarpar |
|
|  | [op_Equality(Length left, Length right)](#op-Equality-com.groupdocs.editor.htmlcss.css.datatypes.Length-com.groupdocs.editor.htmlcss.css.datatypes.Length-) | Verilen iki uzunluğun eşitliğini kontrol eder. |
|
|  | [op_Inequality(Length left, Length right)](#op-Inequality-com.groupdocs.editor.htmlcss.css.datatypes.Length-com.groupdocs.editor.htmlcss.css.datatypes.Length-) | Verilen iki uzunluğun eşitsizliğini kontrol eder. |
|
|  | [hashCode()](#hashCode--) | Bu Length örneğinin bir hash kodunu birleştirerek hesaplar ve döndürür |
değerin ve birim tipinin hash kodları
|
|  | [deepClone()](#deepClone--) | Bu Length örneğinin tam bir kopyasını döndürür |
|
|  | [getUnitFromName(String unitName)](#getUnitFromName-java.lang.String-) | Belirtilen birim adını ayrıştırmaya çalışır ve birinin karşılık gelen değerini döndürür |
Unit enum.
|
|  | [tryParse(String input, Length[] result)](#tryParse-java.lang.String-com.groupdocs.editor.htmlcss.css.datatypes.Length---) | Belirtilen bir dizeyi Length değeri olarak ayrıştırmaya çalışır, içinde |
sayısal değer ve birim adı
|
|  | [parse(String input)](#parse-java.lang.String-) | Belirtilen dizeyi Length değeri olarak ayrıştırır ve döndürür, içinde |
sayısal değer ve birim adı, ya da başarısızlıkta bir istisna fırlatır
|
### Length() {#Length--}
```
public Length()
```


### UnitlessZero {#UnitlessZero}
```
public static final Length UnitlessZero
```


Birimsiz tamsayı sıfır - varsayılan değer, varsayılan parametresizle aynı
yapıcı


### OneHundredPercents {#OneHundredPercents}
```
public static final Length OneHundredPercents
```


100%


### FiftyPercents {#FiftyPercents}
```
public static final Length FiftyPercents
```


50%


### ZeroPercents {#ZeroPercents}
```
public static final Length ZeroPercents
```


0%


### fromValueWithUnit(float value, int unit) {#fromValueWithUnit-float-int-}
```
public static Length fromValueWithUnit(float value, int unit)
```


Belirtilen float sayı ile Length tipinde bir örnek oluşturur ve döndürür
ve birim


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | değer | float | \>Herhangi bir float (FP32) sayı |
|
|  | birim | int | Geçerli herhangi bir birim tipi |
|

**Returns:**
[Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) - New instance of Length type

### fromValueWithUnit(double value, int unit) {#fromValueWithUnit-double-int-}
```
public static Length fromValueWithUnit(double value, int unit)
```


Belirtilen double sayı ile Length tipinde bir örnek oluşturur ve döndürür
ve birim


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | değer | double | Herhangi bir double (FP64) sayı, float (FP32)'a dönüştürülecek |
|
|  | birim | int | Geçerli herhangi bir birim tipi |
|

**Returns:**
[Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) - New instance of Length type

### fromValueWithUnit(int value, int unit) {#fromValueWithUnit-int-int-}
```
public static Length fromValueWithUnit(int value, int unit)
```


Belirtilen tam sayı ile Length tipinde bir örnek oluşturur ve döndürür
sayı ve birim


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | değer | int | Herhangi bir tam sayı |
|
|  | birim | int | Geçerli herhangi bir birim tipi |
|

**Returns:**
[Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) - New instance of Length type

### isUnitlessZero() {#isUnitlessZero--}
```
public final boolean isUnitlessZero()
```


Bu örneğin birimsiz sıfır olup olmadığını belirler. Birimsiz sıfır
bu tipin varsayılan değeridir. IsDefault özelliğiyle aynı.


**Returns:**
boolean
### isDefault() {#isDefault--}
```
public final boolean isDefault()
```


Bu Length örneğinin varsayılan bir değere sahip olup olmadığını gösterir \u2014 birimsiz
sıfır. IsUnitlessZero özelliğiyle aynı.


**Returns:**
boolean
### getUnitType() {#getUnitType--}
```
public final int getUnitType()
```


Bu Length örneğinin birim tipini döndürür.


**Returns:**
int
### isInteger() {#isInteger--}
```
public final boolean isInteger()
```


Bu Length örneğinin sayısal değerinin olup olmadığını gösterir
başlangıçta bir tamsayı (INT32) sayı olarak belirtilmiş ve depolanmıştır


**Returns:**
boolean
### isFloat() {#isFloat--}
```
public final boolean isFloat()
```


Bu Length örneğinin sayısal değerinin olup olmadığını gösterir
başlangıçta bir kayan nokta (FP32) sayı olarak belirtilmiş ve depolanmıştır


**Returns:**
boolean
### getFloatValue() {#getFloatValue--}
```
public final float getFloatValue()
```


Length örneğinin float sayısal değerini döndürür. Asla bir
istisna fırlatmaz - gerekirse Integer değerini Float'a dönüştürür.


**Returns:**
float
### getIntegerValue() {#getIntegerValue--}
```
public final int getIntegerValue()
```


Bu Length örneğinin tamsayı sayısal değerini döndürür, eğer
içsel olarak tamsayı olarak depolanmışsa, aksi takdirde bir istisna fırlatır, eğer
başlangıçta bir kayan nokta sayı olarak depolanmışsa.


**Returns:**
int
### isAbsolute() {#isAbsolute--}
```
public final boolean isAbsolute()
```


Uzunluğun mutlak birimlerde verilip verilmediğini alır. Böyle bir uzunluk olabilir
piksellere dönüştürülür.


**Returns:**
boolean
### isRelative() {#isRelative--}
```
public final boolean isRelative()
```


Uzunluğun göreli birimlerde verilip verilmediğini alır. Böyle bir uzunluk olamaz
piksellere dönüştürülür.


**Returns:**
boolean
### isZero() {#isZero--}
```
public final boolean isZero()
```


Bu uzunluğun sayısal değerinin sıfır olup olmadığını belirler


**Returns:**
boolean
### isNegative() {#isNegative--}
```
public final boolean isNegative()
```


Bu uzunluğun sayısal değerinin negatif olup olmadığını belirler


**Returns:**
boolean
### isPositive() {#isPositive--}
```
public final boolean isPositive()
```


Bu uzunluğun sayısal değerinin pozitif olup olmadığını belirler


**Returns:**
boolean
### isUnitlessNonZero() {#isUnitlessNonZero--}
```
public final boolean isUnitlessNonZero()
```


Değer birimsiz tiptedir, ancak sıfır değildir - pozitif ya da negatif
number


**Returns:**
boolean
### toPixel() {#toPixel--}
```
public final float toPixel()
```


Uzunluğu mümkünse bir piksel sayısına dönüştürür. Eğer mevcut
birim göreliyse, bir istisna fırlatılacaktır.


**Returns:**
float - Mevcut uzunluk tarafından temsil edilen piksel sayısı.

### to(int unit) {#to-int-}
```
public final float to(int unit)
```


Uzunluğu mümkünse verilen birime dönüştürür. Eğer mevcut ya da
verilen birim göreliyse, bir istisna fırlatılacaktır.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | birim | int | Dönüştürülecek birim. |
|

**Returns:**
float - Mevcut uzunluğun verilen birimdeki değeri.

### toStringSpecified(int unit) {#toStringSpecified-int-}
```
public final String toStringSpecified(int unit)
```


Bu uzunluğun belirtilen birim tipinde bir dize temsili döndürür.
Sayısal değer birim tipi değişikliğine karşılık olarak dönüştürülecektir.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | birim | int | Belirtilen birim, bu örneğin dizeye serileştirilmeden önce dönüştürülmesi gereken birim. Geçerli olmalıdır. Birimsiz olamaz. |
|

**Returns:**
java.lang.String - Dize temsili

### serializeDefault() {#serializeDefault--}
```
public final String serializeDefault()
```


Bu uzunluğun özgün yerel biçiminde bir dize temsili döndürür
form (saklandığı gibi), uzunluk değerini başka bir birime dönüştürmeden
birim tipi


**Returns:**
java.lang.String - Dize örneği

### equals(Length other) {#equals-com.groupdocs.editor.htmlcss.css.datatypes.Length-}
```
public final boolean equals(Length other)
```


Bu değerin diğer belirtilen uzunluğa eşit olup olmadığını tanımlar


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | other | [Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) | Length tipinin diğer örneği |
|

**Returns:**
boolean - Eşitse doğru, aksi takdirde yanlış

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Bu uzunluğun belirtilen nesneye eşit olup olmadığını belirler


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | obj | java.lang.Object | Length tipinin diğer örneği, System.Object ya da herhangi bir diğer soyut tip ya da arabirime kutulanmış |
|

**Returns:**
boolean - Eşitse doğru, aksi takdirde yanlış

### op_Multiply(Length multiplicand, int factor) {#op-Multiply-com.groupdocs.editor.htmlcss.css.datatypes.Length-int-}
```
public static Length op_Multiply(Length multiplicand, int factor)
```


Verilen Length'i verilen faktörle çarpar


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | multiplicand | [Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) | Length - çarpan |
|
|  | faktör | int | Arbitrary integer - faktör |
|

**Returns:**
[Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) - A new Length - a product of multiplication

### op_Equality(Length left, Length right) {#op-Equality-com.groupdocs.editor.htmlcss.css.datatypes.Length-com.groupdocs.editor.htmlcss.css.datatypes.Length-}
```
public static boolean op_Equality(Length left, Length right)
```


Verilen iki uzunluğun eşitliğini kontrol eder.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | left | [Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) | Sol uzunluk operandi. |
|
|  | right | [Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) | Sağ uzunluk operandi. |
|

**Returns:**
boolean - Her iki uzunluk da eşitse doğru, aksi takdirde yanlış.

### op_Inequality(Length left, Length right) {#op-Inequality-com.groupdocs.editor.htmlcss.css.datatypes.Length-com.groupdocs.editor.htmlcss.css.datatypes.Length-}
```
public static boolean op_Inequality(Length left, Length right)
```


Verilen iki uzunluğun eşitsizliğini kontrol eder.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | left | [Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) | Sol uzunluk operandi. |
|
|  | right | [Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) | Sağ uzunluk operandi. |
|

**Returns:**
boolean - Her iki uzunluk da eşit değilse doğru, aksi takdirde yanlış.

### hashCode() {#hashCode--}
```
public int hashCode()
```


Bu Length örneğinin bir hash kodunu birleştirerek hesaplar ve döndürür
değerin ve birim tipinin hash kodları


**Returns:**
int - Tamsayı

### deepClone() {#deepClone--}
```
public final Length deepClone()
```


Bu Length örneğinin tam bir kopyasını döndürür


**Returns:**
[Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) - New separate instance of this Length, that is absolutely identical to this one

### getUnitFromName(String unitName) {#getUnitFromName-java.lang.String-}
```
public static int getUnitFromName(String unitName)
```


Belirtilen birim adını ayrıştırmaya çalışır ve birinin karşılık gelen değerini döndürür
Unit enum. Uygun LengthUnit bulunamazsa LengthUnit.Unitless döndürür.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | unitName | java.lang.String | Bir birim adını temsil eden String |
|

**Returns:**
int - Her durumda Unit enum değerini, uygun birim bulunamazsa LengthUnit.Unitless

### tryParse(String input, Length[] result) {#tryParse-java.lang.String-com.groupdocs.editor.htmlcss.css.datatypes.Length---}
```
public static boolean tryParse(String input, Length[] result)
```


Belirtilen bir dizeyi Length değeri olarak ayrıştırmaya çalışır, içinde
sayısal değer ve birim adı


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | input | java.lang.String | Ayrıştırılması gereken giriş stringi |
|
|  | result | [Length\[\]](../../com.groupdocs.editor.htmlcss.css.datatypes/length) | Çıktı parametresi, ayrıştırmanın sonucunu içerir. Ayrıştırma başarısız olursa, varsayılan Length değerini içerir \\u2014 birimsiz sıfır. |
|

**Returns:**
boolean - Ayrıştırma başarılıysa true, başarısızsa false

### parse(String input) {#parse-java.lang.String-}
```
public static Length parse(String input)
```


Belirtilen dizeyi Length değeri olarak ayrıştırır ve döndürür, içinde
sayısal değer ve birim adı, ya da başarısızlıkta bir istisna fırlatır


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | input | java.lang.String | Ayrıştırılması gereken giriş stringi |
|

**Returns:**
[Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) - Valid parsed Length instance

