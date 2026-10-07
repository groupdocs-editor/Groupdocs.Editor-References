---
title: "HtmlSaveOptions"
second_title: "GroupDocs.Editor Java için API Referansı"
description: "HTML formatında örneği kaydetmek için özel seçenekler belirtmeye izin verir"
type: docs
weight: 19
url: /tr/java/com.groupdocs.editor.options/htmlsaveoptions/
---
**Inheritance:**
java.lang.Object
```
public final class HtmlSaveOptions
```

HTML formatında [EditableDocument](../../com.groupdocs.editor/editabledocument) örneğini kaydetmek için özel seçenekler belirtmeye izin verir

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
|  | [getAttributeValueDelimiter()](#getAttributeValueDelimiter--) | HTML öğelerindeki öznitelik değerlerinin etrafında hangi ayırıcıların kullanılacağını kontrol eder: tek tırnak (varsayılan değer) veya çift tırnak |
|
|  | [setAttributeValueDelimiter(int value)](#setAttributeValueDelimiter-int-) | HTML öğelerindeki öznitelik değerlerinin etrafında hangi ayırıcıların kullanılacağını kontrol eder: tek tırnak (varsayılan değer) veya çift tırnak |
|
|  | [getEmbedStylesheetsIntoMarkup()](#getEmbedStylesheetsIntoMarkup--) | CSS stil sayfası(ları)nın nerede saklanacağını kontrol eder: harici kaynaklar olarak ( |
false
), veya HTML işaretlemesine, HTML-\>HEAD bölümündeki STYLE öğesinin içinde gömerek (
true
)
|
|  | [setEmbedStylesheetsIntoMarkup(boolean value)](#setEmbedStylesheetsIntoMarkup-boolean-) | CSS stil sayfası(ları)nın nerede saklanacağını kontrol eder: harici kaynaklar olarak ( |
false
), veya HTML işaretlemesine, HTML-\>HEAD bölümündeki STYLE öğesinin içinde gömerek (
true
)
|
|  | [getSavingCallback()](#getSavingCallback--) | Tüm harici HTML kaynaklarını kaydetmek için son kullanıcı tarafından uygulanması gereken arabirim |
|
|  | [setSavingCallback(IHtmlSavingCallback value)](#setSavingCallback-com.groupdocs.editor.options.IHtmlSavingCallback-) | Tüm harici HTML kaynaklarını kaydetmek için son kullanıcı tarafından uygulanması gereken arabirim |
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


HTML öğelerindeki öznitelik değerlerinin etrafında hangi ayırıcıların kullanılacağını kontrol eder: tek tırnak (varsayılan değer) veya çift tırnak


**Returns:**
int
### setAttributeValueDelimiter(int value) {#setAttributeValueDelimiter-int-}
```
public final void setAttributeValueDelimiter(int value)
```


HTML öğelerindeki öznitelik değerlerinin etrafında hangi ayırıcıların kullanılacağını kontrol eder: tek tırnak (varsayılan değer) veya çift tırnak


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getEmbedStylesheetsIntoMarkup() {#getEmbedStylesheetsIntoMarkup--}
```
public final boolean getEmbedStylesheetsIntoMarkup()
```


CSS stil sayfası(ları)nın nerede saklanacağını kontrol eder: harici kaynaklar olarak (
false
), veya HTML işaretlemesine, HTML-\>HEAD bölümündeki STYLE öğesinin içinde gömerek (
true
)


**Returns:**
boolean
### setEmbedStylesheetsIntoMarkup(boolean value) {#setEmbedStylesheetsIntoMarkup-boolean-}
```
public final void setEmbedStylesheetsIntoMarkup(boolean value)
```


CSS stil sayfası(ları)nın nerede saklanacağını kontrol eder: harici kaynaklar olarak (
false
), veya HTML işaretlemesine, HTML-\>HEAD bölümündeki STYLE öğesinin içinde gömerek (
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


Tüm harici HTML kaynaklarını kaydetmek için son kullanıcı tarafından uygulanması gereken arabirim


**Returns:**
[IHtmlSavingCallback](../../com.groupdocs.editor.options/ihtmlsavingcallback)
### setSavingCallback(IHtmlSavingCallback value) {#setSavingCallback-com.groupdocs.editor.options.IHtmlSavingCallback-}
```
public final void setSavingCallback(IHtmlSavingCallback value)
```


Tüm harici HTML kaynaklarını kaydetmek için son kullanıcı tarafından uygulanması gereken arabirim


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [IHtmlSavingCallback](../../com.groupdocs.editor.options/ihtmlsavingcallback) |  |

