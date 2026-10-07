---
title: "XmlEditOptions"
second_title: "GroupDocs.Editor Java için API Referansı"
description: "XML eXtensible Markup Language belgelerini yüklemek ve HTML'ye dönüştürmek için özel seçenekler belirtmeye izin verir"
type: docs
weight: 51
url: /tr/java/com.groupdocs.editor.options/xmleditoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.IEditOptions](../../com.groupdocs.editor.options/ieditoptions)
```
public final class XmlEditOptions implements IEditOptions
```

XML (eXtensible Markup Language) yüklemek için özel seçenekler belirtmeye izin verir
belgeler ve bunları HTML'ye dönüştürme

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [XmlEditOptions()](#XmlEditOptions--) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [getEncoding()](#getEncoding--) | Metin belgesinin karakter kodlaması, uygulanacak |
açma.
|
|  | [setEncoding(Charset value)](#setEncoding-java.nio.charset.Charset-) | Metin belgesinin karakter kodlaması, uygulanacak |
açma.
|
|  | [getFixIncorrectStructure()](#getFixIncorrectStructure--) | Bozuk XML yapısını düzeltmek için mekanizmanın etkinleştirilmesine veya devre dışı bırakılmasına izin verir. |
|
|  | [setFixIncorrectStructure(boolean value)](#setFixIncorrectStructure-boolean-) | Bozuk XML yapısını düzeltmek için mekanizmanın etkinleştirilmesine veya devre dışı bırakılmasına izin verir. |
|
|  | [getRecognizeUris()](#getRecognizeUris--) | URI tanıma algoritmasının etkinleştirilmesine izin verir. |
|
|  | [setRecognizeUris(boolean value)](#setRecognizeUris-boolean-) | URI tanıma algoritmasının etkinleştirilmesine izin verir. |
|
|  | [getRecognizeEmails()](#getRecognizeEmails--) | Özellikteki e-posta adresleri için tanıma algoritmasının etkinleştirilmesine izin verir. |
değerler
|
|  | [setRecognizeEmails(boolean value)](#setRecognizeEmails-boolean-) | Özellikteki e-posta adresleri için tanıma algoritmasının etkinleştirilmesine izin verir. |
değerler
|
|  | [getTrimTrailingWhitespaces()](#getTrimTrailingWhitespaces--) | İç etiketteki sondaki boşlukların kırpılmasına izin verir. |
metin.
|
|  | [setTrimTrailingWhitespaces(boolean value)](#setTrimTrailingWhitespaces-boolean-) | İç etiketteki sondaki boşlukların kırpılmasına izin verir. |
metin.
|
|  | [getAttributeValuesQuoteType()](#getAttributeValuesQuoteType--) | Özellik değerleri için tırnak tipini (tek veya çift tırnak) belirtmeye izin verir. |
|
|  | [setAttributeValuesQuoteType(QuoteType value)](#setAttributeValuesQuoteType-com.groupdocs.editor.htmlcss.serialization.QuoteType-) | Özellik değerleri için tırnak tipini (tek veya çift tırnak) belirtmeye izin verir. |
|
|  | [getHighlightOptions()](#getHighlightOptions--) | HTML'de temsil edildiğinde XML yapısına uygulanacak XML vurgulamasını ayarlamaya izin verir. |
|
|  | [getFormatOptions()](#getFormatOptions--) | HTML'de temsil edildiğinde XML yapısına uygulanacak XML biçimlendirmesini ayarlamaya izin verir. |
|
### XmlEditOptions() {#XmlEditOptions--}
```
public XmlEditOptions()
```


### getEncoding() {#getEncoding--}
```
public final Charset getEncoding()
```


Metin belgesinin karakter kodlaması, uygulanacak
açma. Varsayılan olarak null \\u2014 dahili belge kodlaması uygulanacaktır.


**Returns:**
java.nio.charset.Charset
### setEncoding(Charset value) {#setEncoding-java.nio.charset.Charset-}
```
public final void setEncoding(Charset value)
```


Metin belgesinin karakter kodlaması, uygulanacak
açma. Varsayılan olarak null \\u2014 dahili belge kodlaması uygulanacaktır.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.nio.charset.Charset |  |

### getFixIncorrectStructure() {#getFixIncorrectStructure--}
```
public final boolean getFixIncorrectStructure()
```


Bozuk XML yapısını düzeltmek için mekanizmanın etkinleştirilmesine veya devre dışı bırakılmasına izin verir.
Varsayılan olarak devre dışı bırakılmıştır (false).

*** ** * ** ***


Varsayılan olarak yalnızca doğru geçerli iyi biçimlendirilmiş XML belgeleri
kabul edilebilir. Bu seçenek etkinleştirildiğinde, GroupDocs.Editor düzeltmeye çalışacaktır
bozuk XML yapısını mümkünse.


**Returns:**
boolean
### setFixIncorrectStructure(boolean value) {#setFixIncorrectStructure-boolean-}
```
public final void setFixIncorrectStructure(boolean value)
```


Bozuk XML yapısını düzeltmek için mekanizmanın etkinleştirilmesine veya devre dışı bırakılmasına izin verir.
Varsayılan olarak devre dışı bırakılmıştır (false).

*** ** * ** ***


Varsayılan olarak yalnızca doğru geçerli iyi biçimlendirilmiş XML belgeleri
kabul edilebilir. Bu seçenek etkinleştirildiğinde, GroupDocs.Editor düzeltmeye çalışacaktır
bozuk XML yapısını mümkünse.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### getRecognizeUris() {#getRecognizeUris--}
```
public final boolean getRecognizeUris()
```


URI tanıma algoritmasının etkinleştirilmesine izin verir.


**Returns:**
boolean
### setRecognizeUris(boolean value) {#setRecognizeUris-boolean-}
```
public final void setRecognizeUris(boolean value)
```


URI tanıma algoritmasının etkinleştirilmesine izin verir.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### getRecognizeEmails() {#getRecognizeEmails--}
```
public final boolean getRecognizeEmails()
```


Özellikteki e-posta adresleri için tanıma algoritmasının etkinleştirilmesine izin verir.
değerler


**Returns:**
boolean
### setRecognizeEmails(boolean value) {#setRecognizeEmails-boolean-}
```
public final void setRecognizeEmails(boolean value)
```


Özellikteki e-posta adresleri için tanıma algoritmasının etkinleştirilmesine izin verir.
değerler


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### getTrimTrailingWhitespaces() {#getTrimTrailingWhitespaces--}
```
public final boolean getTrimTrailingWhitespaces()
```


İç etiketteki sondaki boşlukların kırpılmasına izin verir.
metin. Varsayılan olarak devre dışı bırakılmıştır (false) \\u2014 sondaki boşluklar
korunacaktır.


**Returns:**
boolean
### setTrimTrailingWhitespaces(boolean value) {#setTrimTrailingWhitespaces-boolean-}
```
public final void setTrimTrailingWhitespaces(boolean value)
```


İç etiketteki sondaki boşlukların kırpılmasına izin verir.
metin. Varsayılan olarak devre dışı bırakılmıştır (false) \\u2014 sondaki boşluklar
korunacaktır.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### getAttributeValuesQuoteType() {#getAttributeValuesQuoteType--}
```
public final QuoteType getAttributeValuesQuoteType()
```


Özellik değerleri için tırnak tipini (tek veya çift tırnak) belirtmeye izin verir. Çift tırnak varsayılandır.


**Returns:**
[QuoteType](../../com.groupdocs.editor.htmlcss.serialization/quotetype)
### setAttributeValuesQuoteType(QuoteType value) {#setAttributeValuesQuoteType-com.groupdocs.editor.htmlcss.serialization.QuoteType-}
```
public final void setAttributeValuesQuoteType(QuoteType value)
```


Özellik değerleri için tırnak tipini (tek veya çift tırnak) belirtmeye izin verir. Çift tırnak varsayılandır.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [QuoteType](../../com.groupdocs.editor.htmlcss.serialization/quotetype) |  |

### getHighlightOptions() {#getHighlightOptions--}
```
public final XmlHighlightOptions getHighlightOptions()
```


HTML'de temsil edildiğinde XML yapısına uygulanacak XML vurgulamasını ayarlamaya izin verir. Varsayılan vurgulama kullanılır ve ayarlanabilir. Null olamaz.


**Returns:**
[XmlHighlightOptions](../../com.groupdocs.editor.options/xmlhighlightoptions)
### getFormatOptions() {#getFormatOptions--}
```
public final XmlFormatOptions getFormatOptions()
```


HTML'de temsil edildiğinde XML yapısına uygulanacak XML biçimlendirmesini ayarlamaya izin verir. Varsayılan biçimlendirme kullanılır ve ayarlanabilir. Null olamaz.


**Returns:**
[XmlFormatOptions](../../com.groupdocs.editor.options/xmlformatoptions)
