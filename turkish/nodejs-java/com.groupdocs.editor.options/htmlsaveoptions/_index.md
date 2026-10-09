---
title: "HtmlSaveOptions"
second_title: "GroupDocs.Editor Node.js için Java API Referansı"
description: "HTML formatına kaydetmek için örnek için özel seçenekler belirlemeye izin verir"
type: docs
weight: 19
url: /tr/nodejs-java/com.groupdocs.editor.options/htmlsaveoptions/
---
**Inheritance:**
java.lang.Object
```
public final class HtmlSaveOptions
```

HTML formatına kaydetmek için [EditableDocument](../../com.groupdocs.editor/editabledocument) örneği için özel seçenekler belirlemeye izin verir

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [HtmlSaveOptions()](#HtmlSaveOptions--) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [getHtmlTagCase()](#getHtmlTagCase--) | HTML işaretleme içinde HTML etiket adlarının nasıl görüneceğini kontrol eder: Tümü küçük harf (varsayılan değer), Tümü büyük harf veya İlk harf büyük |
|
|  | [setHtmlTagCase(int value)](#setHtmlTagCase-int-) | HTML işaretleme içinde HTML etiket adlarının nasıl görüneceğini kontrol eder: Tümü küçük harf (varsayılan değer), Tümü büyük harf veya İlk harf büyük |
|
|  | [getAttributeValueDelimiter()](#getAttributeValueDelimiter--) | HTML öğelerindeki öznitelik değerlerinin etrafında hangi sınırlayıcının kullanılacağını kontrol eder: tek tırnak (varsayılan değer) veya çift tırnak |
|
|  | [setAttributeValueDelimiter(int value)](#setAttributeValueDelimiter-int-) | HTML öğelerindeki öznitelik değerlerinin etrafında hangi sınırlayıcının kullanılacağını kontrol eder: tek tırnak (varsayılan değer) veya çift tırnak |
|
|  | [getEmbedStylesheetsIntoMarkup()](#getEmbedStylesheetsIntoMarkup--) | CSS stil sayfası(ları) nereye depolanacağını kontrol eder: dış kaynaklar olarak ( |
false
) veya HTML-\>HEAD bölümündeki STYLE öğesi içinde (
true
)
|
|  | [setEmbedStylesheetsIntoMarkup(boolean value)](#setEmbedStylesheetsIntoMarkup-boolean-) | CSS stil sayfası(ları) nereye depolanacağını kontrol eder: dış kaynaklar olarak ( |
false
) veya HTML-\>HEAD bölümündeki STYLE öğesi içinde (
true
)
|
|  | [getSavingCallback()](#getSavingCallback--) | Tüm dış HTML kaynaklarını kaydetmek için son kullanıcı tarafından uygulanması gereken arayüz |
|
|  | [setSavingCallback(IHtmlSavingCallback value)](#setSavingCallback-com.groupdocs.editor.options.IHtmlSavingCallback-) | Tüm dış HTML kaynaklarını kaydetmek için son kullanıcı tarafından uygulanması gereken arayüz |
|
### HtmlSaveOptions() {#HtmlSaveOptions--}
```
public HtmlSaveOptions()
```


### getHtmlTagCase() {#getHtmlTagCase--}
```
public final int getHtmlTagCase()
```


HTML işaretleme içinde HTML etiket adlarının nasıl görüneceğini kontrol eder: Tümü küçük harf (varsayılan değer), Tümü büyük harf veya İlk harf büyük


**Returns:**
int
### setHtmlTagCase(int value) {#setHtmlTagCase-int-}
```
public final void setHtmlTagCase(int value)
```


HTML işaretleme içinde HTML etiket adlarının nasıl görüneceğini kontrol eder: Tümü küçük harf (varsayılan değer), Tümü büyük harf veya İlk harf büyük


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getAttributeValueDelimiter() {#getAttributeValueDelimiter--}
```
public final int getAttributeValueDelimiter()
```


HTML öğelerindeki öznitelik değerlerinin etrafında hangi sınırlayıcının kullanılacağını kontrol eder: tek tırnak (varsayılan değer) veya çift tırnak


**Returns:**
int
### setAttributeValueDelimiter(int value) {#setAttributeValueDelimiter-int-}
```
public final void setAttributeValueDelimiter(int value)
```


HTML öğelerindeki öznitelik değerlerinin etrafında hangi sınırlayıcının kullanılacağını kontrol eder: tek tırnak (varsayılan değer) veya çift tırnak


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getEmbedStylesheetsIntoMarkup() {#getEmbedStylesheetsIntoMarkup--}
```
public final boolean getEmbedStylesheetsIntoMarkup()
```


CSS stil sayfası(ları) nereye depolanacağını kontrol eder: dış kaynaklar olarak (
false
) veya HTML-\>HEAD bölümündeki STYLE öğesi içinde (
true
)


**Returns:**
boolean
### setEmbedStylesheetsIntoMarkup(boolean value) {#setEmbedStylesheetsIntoMarkup-boolean-}
```
public final void setEmbedStylesheetsIntoMarkup(boolean value)
```


CSS stil sayfası(ları) nereye depolanacağını kontrol eder: dış kaynaklar olarak (
false
) veya HTML-\>HEAD bölümündeki STYLE öğesi içinde (
true
)


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### getSavingCallback() {#getSavingCallback--}
```
public final IHtmlSavingCallback getSavingCallback()
```


Tüm dış HTML kaynaklarını kaydetmek için son kullanıcı tarafından uygulanması gereken arayüz


**Returns:**
[IHtmlSavingCallback](../../com.groupdocs.editor.options/ihtmlsavingcallback)
### setSavingCallback(IHtmlSavingCallback value) {#setSavingCallback-com.groupdocs.editor.options.IHtmlSavingCallback-}
```
public final void setSavingCallback(IHtmlSavingCallback value)
```


Tüm dış HTML kaynaklarını kaydetmek için son kullanıcı tarafından uygulanması gereken arayüz


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [IHtmlSavingCallback](../../com.groupdocs.editor.options/ihtmlsavingcallback) |  |

