---
title: "ArgbColor"
second_title: "GroupDocs.Editor Java için API Referansı"
description: "Dönüştürücüler ve serileştiricilerle ARGB formatında bir renk değerini temsil eder."
type: docs
weight: 10
url: /tr/java/com.groupdocs.editor.htmlcss.css.datatypes/argbcolor/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct

**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.css.datatypes.ICssDataType](../../com.groupdocs.editor.htmlcss.css.datatypes/icssdatatype)
```
public class ArgbColor extends Struct<ArgbColor> implements ICssDataType
```

Dönüştürücüler ve serileştiricilerle ARGB formatında bir renk değerini temsil eder.

<br />

*** ** * ** ***

Bu tip, CSS işlemleri için (ancak bunlarla sınırlı olmamak üzere) faydalı olacak şekilde tasarlanmıştır. Daha fazla bilgi: https://developer.mozilla.org/en-US/docs/Web/CSS/color_value

<br />


## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [ArgbColor()](#ArgbColor--) |  |
| [ArgbColor(int r, int g, int b)](#ArgbColor-int-int-int-) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [fromRgba(int red, int green, int blue, int alpha)](#fromRgba-int-int-int-int-) | Belirtilen Kırmızı, Yeşil, Mavi ve Alfa kanallarından bir [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) değeri oluşturur |
|
|  | [fromRgb(int red, int green, int blue)](#fromRgb-int-int-int-) | Belirtilen Kırmızı, Yeşil, Mavi kanallarından bir [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) değeri oluşturur, Alfa kanalı ise tamamen opaktır |
|
|  | [fromSingleValueRgb(byte value)](#fromSingleValueRgb-byte-) | Tek bir değerden tamamen opak (A=255) bir renk oluşturur; bu değer tüm kanallara uygulanır |
|
|  | [fromColor(Color color)](#fromColor-java.awt.Color-) | Belirtilen [Color](../../com.groupdocs.editor.htmlcss.css.specificdeclarations.font/color) üzerinden bir [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) değeri oluşturur |
|
|  | [getValue()](#getValue--) | Rengin Int32 değerini alır. |
|
|  | [getA()](#getA--) | Rengin alfa kısmını alır. |
|
|  | [getAlpha()](#getAlpha--) | Rengin alfa kısmını yüzde olarak (0..1) alır. |
|
|  | [getR()](#getR--) | Rengin kırmızı kısmını alır. |
|
|  | [getG()](#getG--) | Rengin yeşil kısmını alır. |
|
|  | [getB()](#getB--) | Rengin mavi kısmını alır. |
|
|  | [isEmpty()](#isEmpty--) | Başlatılmamış renk - tüm 4 kanal 0 olarak ayarlanır. |
|
|  | [isDefault()](#isDefault--) | Bu [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) örneğinin varsayılan (Transparent) olup olmadığını gösterir - tüm 4 kanal 0 olarak ayarlanır |
|
|  | [isFullyTransparent()](#isFullyTransparent--) | Bu [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) örneğinin tamamen şeffaf olup olmadığını gösterir - Alfa kanalı minimum (0) değere sahiptir, bu yüzden diğer R, G ve B kanalları görünür bir etki yapmaz. |
|
|  | [isTranslucent()](#isTranslucent--) | Bu [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) örneğinin yarı saydam (tamamen şeffaf değil, aynı zamanda tamamen opak da değil) olup olmadığını gösterir |
|
|  | [isFullyOpaque()](#isFullyOpaque--) | Bu [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) örneğinin şeffaflık olmadan tamamen opak olup olmadığını gösterir (Alfa kanalı maksimum değere sahiptir) |
|
|  | [toSystemColor()](#toSystemColor--) | Bu [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) örneğinin değerini [Color](../../com.groupdocs.editor.htmlcss.css.specificdeclarations.font/color) örneğine dönüştürür ve döndürür |
|
|  | [toRGBA()](#toRGBA--) | Bu [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) örneğini 'rgba' CSS fonksiyon notasyonuna serileştirir |
|
|  | [toRGB()](#toRGB--) | Bu [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) örneğini 'rgb' CSS fonksiyon notasyonuna serileştirir |
|
|  | [serializeDefault()](#serializeDefault--) | Bu [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) örneğini şeffaflığa bağlı olarak en uygun CSS fonksiyon notasyonuna serileştirir |
|
|  | [toString()](#toString--) | Aynı #serializeDefault.serializeDefault |
|
|  | [op_Equality(ArgbColor left, ArgbColor right)](#op-Equality-com.groupdocs.editor.htmlcss.css.datatypes.ArgbColor-com.groupdocs.editor.htmlcss.css.datatypes.ArgbColor-) | İki rengi karşılaştırır ve iki rengin eşleşip eşleşmediğini belirten bir boolean döndürür. |
|
|  | [op_Inequality(ArgbColor left, ArgbColor right)](#op-Inequality-com.groupdocs.editor.htmlcss.css.datatypes.ArgbColor-com.groupdocs.editor.htmlcss.css.datatypes.ArgbColor-) | İki rengi karşılaştırır ve iki rengin eşleşmediğini belirten bir boolean döndürür. |
|
|  | [equals(ArgbColor other)](#equals-com.groupdocs.editor.htmlcss.css.datatypes.ArgbColor-) | İki [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) rengin eşitliğini kontrol eder |
|
|  | [equals(ICssDataType other)](#equals-com.groupdocs.editor.htmlcss.css.datatypes.ICssDataType-) | İki [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) rengin eşitliğini kontrol eder |
|
|  | [equals(Object other)](#equals-java.lang.Object-) | Başka bir nesnenin bu [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) örneğine eşit olup olmadığını test eder. |
|
|  | [hashCode()](#hashCode--) | Mevcut rengi tanımlayan bir hash kodu döndürür. |
|
### ArgbColor() {#ArgbColor--}
```
public ArgbColor()
```


### ArgbColor(int r, int g, int b) {#ArgbColor-int-int-int-}
```
public ArgbColor(int r, int g, int b)
```


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| r | int |  |
| g | int |  |
| b | int |  |

### fromRgba(int red, int green, int blue, int alpha) {#fromRgba-int-int-int-int-}
```
public static ArgbColor fromRgba(int red, int green, int blue, int alpha)
```


Belirtilen Kırmızı, Yeşil, Mavi ve Alfa kanallarından bir [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) değeri oluşturur


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | kırmızı | int | Kırmızı kanal değeri |
|
|  | yeşil | int | Yeşil kanal değeri |
|
|  | mavi | int | Mavi kanal değeri |
|
|  | alfa | int | Alfa kanal değeri |
|

**Returns:**
[ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) - New [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) value

### fromRgb(int red, int green, int blue) {#fromRgb-int-int-int-}
```
public static ArgbColor fromRgb(int red, int green, int blue)
```


Belirtilen Kırmızı, Yeşil, Mavi kanallarından bir [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) değeri oluşturur, Alfa kanalı ise tamamen opaktır


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | kırmızı | int | Kırmızı kanal değeri |
|
|  | yeşil | int | Yeşil kanal değeri |
|
|  | mavi | int | Mavi kanal değeri |
|

**Returns:**
[ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) - New [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) value

### fromSingleValueRgb(byte value) {#fromSingleValueRgb-byte-}
```
public static ArgbColor fromSingleValueRgb(byte value)
```


Tek bir değerden tamamen opak (A=255) bir renk oluşturur; bu değer tüm kanallara uygulanır


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | değer | bayt | Kırmızı, Yeşil ve Mavi kanallar için aynı olan bir byte değeri |
|

**Returns:**
[ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) - New [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) instance

### fromColor(Color color) {#fromColor-java.awt.Color-}
```
public static ArgbColor fromColor(Color color)
```


Belirtilen [Color](../../com.groupdocs.editor.htmlcss.css.specificdeclarations.font/color) üzerinden bir [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) değeri oluşturur


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| renk | java.awt.Color |  |

**Returns:**
[ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) - 
### getValue() {#getValue--}
```
public final int getValue()
```


Rengin Int32 değerini alır.


**Returns:**
int
### getA() {#getA--}
```
public final int getA()
```


Rengin alfa kısmını alır.


**Returns:**
int
### getAlpha() {#getAlpha--}
```
public final double getAlpha()
```


Rengin alfa kısmını yüzde olarak (0..1) alır.


**Returns:**
double
### getR() {#getR--}
```
public final int getR()
```


Rengin kırmızı kısmını alır.


**Returns:**
int
### getG() {#getG--}
```
public final int getG()
```


Rengin yeşil kısmını alır.


**Returns:**
int
### getB() {#getB--}
```
public final int getB()
```


Rengin mavi kısmını alır.


**Returns:**
int
### isEmpty() {#isEmpty--}
```
public final boolean isEmpty()
```


Başlatılmamış renk - tüm 4 kanal 0 olarak ayarlanır. Varsayılan ve Şeffaf ile aynı.


**Returns:**
boolean
### isDefault() {#isDefault--}
```
public final boolean isDefault()
```


Bu [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) örneğinin varsayılan (Transparent) olup olmadığını gösterir - tüm 4 kanal 0 olarak ayarlanır


**Returns:**
boolean
### isFullyTransparent() {#isFullyTransparent--}
```
public final boolean isFullyTransparent()
```


Bu [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) örneğinin tamamen şeffaf olup olmadığını gösterir - Alfa kanalı minimum (0) değere sahiptir, bu yüzden diğer R, G ve B kanalları görünür bir etki yapmaz.


**Returns:**
boolean
### isTranslucent() {#isTranslucent--}
```
public final boolean isTranslucent()
```


Bu [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) örneğinin yarı saydam (tamamen şeffaf değil, aynı zamanda tamamen opak da değil) olup olmadığını gösterir


**Returns:**
boolean
### isFullyOpaque() {#isFullyOpaque--}
```
public final boolean isFullyOpaque()
```


Bu [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) örneğinin şeffaflık olmadan tamamen opak olup olmadığını gösterir (Alfa kanalı maksimum değere sahiptir)


**Returns:**
boolean
### toSystemColor() {#toSystemColor--}
```
public final Color toSystemColor()
```


Bu [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) örneğinin değerini [Color](../../com.groupdocs.editor.htmlcss.css.specificdeclarations.font/color) örneğine dönüştürür ve döndürür


**Returns:**
[Color](../../java.awt/color) - New [Color](../../com.groupdocs.editor.htmlcss.css.specificdeclarations.font/color) instance

### toRGBA() {#toRGBA--}
```
public final String toRGBA()
```


Bu [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) örneğini 'rgba' CSS fonksiyon notasyonuna serileştirir


**Returns:**
java.lang.String - 'rgba(r, g, b, a)' biçiminde bir dize

### toRGB() {#toRGB--}
```
public final String toRGB()
```


Bu [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) örneğini 'rgb' CSS fonksiyon notasyonuna serileştirir


**Returns:**
java.lang.String - 'rgb(r, g, b)' biçiminde bir dize

### serializeDefault() {#serializeDefault--}
```
public final String serializeDefault()
```


Bu [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) örneğini şeffaflığa bağlı olarak en uygun CSS fonksiyon notasyonuna serileştirir


**Returns:**
java.lang.String - 'rgba(r, g, b, a)' veya 'rgb(r, g, b)' biçiminde bir dize

### toString() {#toString--}
```
public String toString()
```


Aynı #serializeDefault.serializeDefault


**Returns:**
java.lang.String - #serializeDefault.serializeDefault içinde aynı dönüş değeri

### op_Equality(ArgbColor left, ArgbColor right) {#op-Equality-com.groupdocs.editor.htmlcss.css.datatypes.ArgbColor-com.groupdocs.editor.htmlcss.css.datatypes.ArgbColor-}
```
public static boolean op_Equality(ArgbColor left, ArgbColor right)
```


İki rengi karşılaştırır ve iki rengin eşleşip eşleşmediğini belirten bir boolean döndürür.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | left | [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) | Kullanılacak ilk renk. |
|
|  | right | [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) | Kullanılacak ikinci renk. |
|

**Returns:**
boolean - Renkler eşitse doğru, aksi takdirde yanlış.

### op_Inequality(ArgbColor left, ArgbColor right) {#op-Inequality-com.groupdocs.editor.htmlcss.css.datatypes.ArgbColor-com.groupdocs.editor.htmlcss.css.datatypes.ArgbColor-}
```
public static boolean op_Inequality(ArgbColor left, ArgbColor right)
```


İki rengi karşılaştırır ve iki rengin eşleşmediğini belirten bir boolean döndürür.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | left | [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) | Kullanılacak ilk renk. |
|
|  | right | [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) | Kullanılacak ikinci renk. |
|

**Returns:**
boolean - Renkler eşit değilse doğru, aksi takdirde yanlış.

### equals(ArgbColor other) {#equals-com.groupdocs.editor.htmlcss.css.datatypes.ArgbColor-}
```
public final boolean equals(ArgbColor other)
```


İki [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) rengin eşitliğini kontrol eder


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | other | [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) | Diğer [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) renk |
|

**Returns:**
boolean - Renkler eşitse doğru, aksi takdirde yanlış.

### equals(ICssDataType other) {#equals-com.groupdocs.editor.htmlcss.css.datatypes.ICssDataType-}
```
public final boolean equals(ICssDataType other)
```


İki [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) rengin eşitliğini kontrol eder


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | other | [ICssDataType](../../com.groupdocs.editor.htmlcss.css.datatypes/icssdatatype) | Diğer [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) renk, ICssDataType'a dönüştürülmüş |
|

**Returns:**
boolean - Renkler eşitse doğru, aksi takdirde yanlış.

### equals(Object other) {#equals-java.lang.Object-}
```
public boolean equals(Object other)
```


Başka bir nesnenin bu [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) örneğine eşit olup olmadığını test eder.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | diğer | java.lang.Object | Test edilecek nesne. |
|

**Returns:**
boolean - Nesneler eşitse doğru, aksi takdirde yanlış.

### hashCode() {#hashCode--}
```
public int hashCode()
```


Mevcut rengi tanımlayan bir hash kodu döndürür.


**Returns:**
int - Hashcode'un tam sayı değeri.

