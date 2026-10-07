---
title: "WebFont"
second_title: "GroupDocs.Editor Java için API Referansı"
description: "Web için bir yazı tipi ayarını temsil eder."
type: docs
weight: 43
url: /tr/java/com.groupdocs.editor.options/webfont/
---
**Inheritance:**
java.lang.Object
```
public final class WebFont
```

Web için bir yazı tipi ayarını temsil eder.

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [getColor()](#getColor--) | ARGB32 formatında yazı tipi rengi |
|
|  | [setColor(ArgbColor value)](#setColor-com.groupdocs.editor.htmlcss.css.datatypes.ArgbColor-) | ARGB32 formatında yazı tipi rengi |
|
|  | [getWeight()](#getWeight--) | Yazı tipinin ağırlığını (veya kalınlığını) ayarlar |
|
|  | [setWeight(FontWeight value)](#setWeight-com.groupdocs.editor.htmlcss.css.properties.FontWeight-) | Yazı tipinin ağırlığını (veya kalınlığını) ayarlar |
|
|  | [getStyle()](#getStyle--) | Bir yazı tipinin normal, italik veya eğik yüzüyle stil verilip verilmeyeceğini ayarlar. |
|
|  | [setStyle(FontStyle value)](#setStyle-com.groupdocs.editor.htmlcss.css.properties.FontStyle-) | Bir yazı tipinin normal, italik veya eğik yüzüyle stil verilip verilmeyeceğini ayarlar. |
|
|  | [getLine()](#getLine--) | Metne uygulanan bir satırı veya satır kombinasyonunu ayarlar |
|
|  | [setLine(TextDecorationLineType value)](#setLine-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-) | Metne uygulanan bir satırı veya satır kombinasyonunu ayarlar |
|
|  | [getSize()](#getSize--) | Yazı tipinin boyutunu mutlak veya göreceli birimlerde ayarlar |
|
|  | [setSize(FontSize value)](#setSize-com.groupdocs.editor.htmlcss.css.properties.FontSize-) | Yazı tipinin boyutunu mutlak veya göreceli birimlerde ayarlar |
|
|  | [getName()](#getName--) | Yazı tipi adını ayarlar. |
|
|  | [setName(String value)](#setName-java.lang.String-) | Yazı tipi adını ayarlar. |
|
|  | [deepClone()](#deepClone--) | Bu [WebFont](../../com.groupdocs.editor.options/webfont) örneğinin tam bir derin kopyasını oluşturur ve döndürür |
|
|  | [equals(WebFont other)](#equals-com.groupdocs.editor.options.WebFont-) | Bu WebFont örneğinin belirtilenle eşit olup olmadığını belirler |
|
|  | [equals(Object obj)](#equals-java.lang.Object-) | Bu WebFont örneğinin belirtilen tip dönüşümü yapılmamış nesneyle eşit olup olmadığını belirler |
|
### getColor() {#getColor--}
```
public final ArgbColor getColor()
```


ARGB32 formatında yazı tipi rengi


**Returns:**
[ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor)
### setColor(ArgbColor value) {#setColor-com.groupdocs.editor.htmlcss.css.datatypes.ArgbColor-}
```
public final void setColor(ArgbColor value)
```


ARGB32 formatında yazı tipi rengi


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) |  |

### getWeight() {#getWeight--}
```
public final FontWeight getWeight()
```


Yazı tipinin ağırlığını (veya kalınlığını) ayarlar


**Returns:**
[FontWeight](../../com.groupdocs.editor.htmlcss.css.properties/fontweight)
### setWeight(FontWeight value) {#setWeight-com.groupdocs.editor.htmlcss.css.properties.FontWeight-}
```
public final void setWeight(FontWeight value)
```


Yazı tipinin ağırlığını (veya kalınlığını) ayarlar


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [FontWeight](../../com.groupdocs.editor.htmlcss.css.properties/fontweight) |  |

### getStyle() {#getStyle--}
```
public final FontStyle getStyle()
```


Bir yazı tipinin normal, italik veya eğik yüzüyle stil verilip verilmeyeceğini ayarlar.


**Returns:**
[FontStyle](../../com.groupdocs.editor.htmlcss.css.properties/fontstyle)
### setStyle(FontStyle value) {#setStyle-com.groupdocs.editor.htmlcss.css.properties.FontStyle-}
```
public final void setStyle(FontStyle value)
```


Bir yazı tipinin normal, italik veya eğik yüzüyle stil verilip verilmeyeceğini ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [FontStyle](../../com.groupdocs.editor.htmlcss.css.properties/fontstyle) |  |

### getLine() {#getLine--}
```
public final TextDecorationLineType getLine()
```


Metne uygulanan bir satırı veya satır kombinasyonunu ayarlar


**Returns:**
[TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype)
### setLine(TextDecorationLineType value) {#setLine-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-}
```
public final void setLine(TextDecorationLineType value)
```


Metne uygulanan bir satırı veya satır kombinasyonunu ayarlar


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) |  |

### getSize() {#getSize--}
```
public final FontSize getSize()
```


Yazı tipinin boyutunu mutlak veya göreceli birimlerde ayarlar


**Returns:**
[FontSize](../../com.groupdocs.editor.htmlcss.css.properties/fontsize)
### setSize(FontSize value) {#setSize-com.groupdocs.editor.htmlcss.css.properties.FontSize-}
```
public final void setSize(FontSize value)
```


Yazı tipinin boyutunu mutlak veya göreceli birimlerde ayarlar


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [FontSize](../../com.groupdocs.editor.htmlcss.css.properties/fontsize) |  |

### getName() {#getName--}
```
public final String getName()
```


Yazı tipi adını ayarlar. Belirtilmezse, varsayılan yazı tipi kullanılacaktır


**Returns:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


Yazı tipi adını ayarlar. Belirtilmezse, varsayılan yazı tipi kullanılacaktır


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### deepClone() {#deepClone--}
```
public final WebFont deepClone()
```


Bu [WebFont](../../com.groupdocs.editor.options/webfont) örneğinin tam bir derin kopyasını oluşturur ve döndürür


**Returns:**
[WebFont](../../com.groupdocs.editor.options/webfont) - New [WebFont](../../com.groupdocs.editor.options/webfont) instance, that is a full and deep copy of this one

### equals(WebFont other) {#equals-com.groupdocs.editor.options.WebFont-}
```
public final boolean equals(WebFont other)
```


Bu WebFont örneğinin belirtilenle eşit olup olmadığını belirler


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | other | [WebFont](../../com.groupdocs.editor.options/webfont) | Eşitliği kontrol etmek için başka bir WebFont, NULL olabilir |
|

**Returns:**
boolean - eşitse true, eşit değilse false

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Bu WebFont örneğinin belirtilen tip dönüşümü yapılmamış nesneyle eşit olup olmadığını belirler


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | obj | java.lang.Object | Bir [WebFont](../../com.groupdocs.editor.options/webfont) örneği olması beklenen nesne |
|

**Returns:**
boolean - eşitse true, eşit değilse false

