---
title: "XmlEditOptions"
second_title: "GroupDocs.Editor Node.js için Java API Referansı"
description: "XML (eXtensible Markup Language) belgelerini yüklemek ve HTML'ye dönüştürmek için özel seçenekler belirtmeye olanak tanır"
type: docs
weight: 51
url: /tr/nodejs-java/com.groupdocs.editor.options/xmleditoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.IEditOptions](../../com.groupdocs.editor.options/ieditoptions)
```
public final class XmlEditOptions implements IEditOptions
```

XML (eXtensible Markup Language) yüklemek için özel seçenekler belirtmeye olanak tanır
belgeleri ve bunları HTML'ye dönüştürmeyi

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [XmlEditOptions()](#XmlEditOptions--) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [getEncoding()](#getEncoding--) | Metin belgesinin karakter kodlaması, bunun için uygulanacak |
açma.
|
|  | [setEncoding(Charset value)](#setEncoding-java.nio.charset.Charset-) | Metin belgesinin karakter kodlaması, bunun için uygulanacak |
açma.
|
|  | [getFixIncorrectStructure()](#getFixIncorrectStructure--) | Bozuk XML yapısını düzeltmek için mekanizmayı etkinleştirmeye veya devre dışı bırakmaya olanak tanır. |
|
|  | [setFixIncorrectStructure(boolean value)](#setFixIncorrectStructure-boolean-) | Bozuk XML yapısını düzeltmek için mekanizmayı etkinleştirmeye veya devre dışı bırakmaya olanak tanır. |
|
|  | [getRecognizeUris()](#getRecognizeUris--) | URI tanıma algoritmasını etkinleştirmeye olanak tanır |
|
|  | [setRecognizeUris(boolean value)](#setRecognizeUris-boolean-) | URI tanıma algoritmasını etkinleştirmeye olanak tanır |
|
|  | [getRecognizeEmails()](#getRecognizeEmails--) | Özelliklerdeki e-posta adreslerini tanıma algoritmasını etkinleştirmeye olanak tanır |
değerler
|
|  | [setRecognizeEmails(boolean value)](#setRecognizeEmails-boolean-) | Özelliklerdeki e-posta adreslerini tanıma algoritmasını etkinleştirmeye olanak tanır |
değerler
|
|  | [getTrimTrailingWhitespaces()](#getTrimTrailingWhitespaces--) | İç etiketlerdeki sondaki boşlukların kırpılmasını etkinleştirmeye olanak tanır |
metin.
|
|  | [setTrimTrailingWhitespaces(boolean value)](#setTrimTrailingWhitespaces-boolean-) | İç etiketlerdeki sondaki boşlukların kırpılmasını etkinleştirmeye olanak tanır |
metin.
|
|  | [getAttributeValuesQuoteType()](#getAttributeValuesQuoteType--) | Özellik değerleri için alıntı tipini (tek veya çift tırnak) belirtmeye olanak tanır. |
|
|  | [setAttributeValuesQuoteType(QuoteType value)](#setAttributeValuesQuoteType-com.groupdocs.editor.htmlcss.serialization.QuoteType-) | Özellik değerleri için alıntı tipini (tek veya çift tırnak) belirtmeye olanak tanır. |
|
|  | [getHighlightOptions()](#getHighlightOptions--) | HTML'de gösterildiğinde XML yapısına uygulanacak XML vurgulamasını ayarlamaya olanak tanır. |
|
|  | [getFormatOptions()](#getFormatOptions--) | HTML'de gösterildiğinde XML yapısına uygulanacak XML biçimlendirmesini ayarlamaya olanak tanır. |
|
### XmlEditOptions() {#XmlEditOptions--}
```
public XmlEditOptions()
```


### getEncoding() {#getEncoding--}
```
public final Charset getEncoding()
```


Metin belgesinin karakter kodlaması, bunun için uygulanacak
açılış. Varsayılan olarak null \\u2014 iç belge kodlaması uygulanacaktır.


**Returns:**
java.nio.charset.Charset
### setEncoding(Charset value) {#setEncoding-java.nio.charset.Charset-}
```
public final void setEncoding(Charset value)
```


Metin belgesinin karakter kodlaması, bunun için uygulanacak
açılış. Varsayılan olarak null \\u2014 iç belge kodlaması uygulanacaktır.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.nio.charset.Charset |  |

### getFixIncorrectStructure() {#getFixIncorrectStructure--}
```
public final boolean getFixIncorrectStructure()
```


Bozuk XML yapısını düzeltmek için mekanizmayı etkinleştirmeye veya devre dışı bırakmaya olanak tanır.
Varsayılan olarak devre dışı bırakılır (false).

*** ** * ** ***


Varsayılan olarak yalnızca uygun, geçerli, iyi biçimlendirilmiş XML belgeleri
kabul edilebilir. Bu seçenek etkinleştirildiğinde, GroupDocs.Editor düzeltmeye çalışacaktır
bozuk XML yapısını mümkünse.


**Returns:**
boolean
### setFixIncorrectStructure(boolean value) {#setFixIncorrectStructure-boolean-}
```
public final void setFixIncorrectStructure(boolean value)
```


Bozuk XML yapısını düzeltmek için mekanizmayı etkinleştirmeye veya devre dışı bırakmaya olanak tanır.
Varsayılan olarak devre dışı bırakılır (false).

*** ** * ** ***


Varsayılan olarak yalnızca uygun, geçerli, iyi biçimlendirilmiş XML belgeleri
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


URI tanıma algoritmasını etkinleştirmeye olanak tanır


**Returns:**
boolean
### setRecognizeUris(boolean value) {#setRecognizeUris-boolean-}
```
public final void setRecognizeUris(boolean value)
```


URI tanıma algoritmasını etkinleştirmeye olanak tanır


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### getRecognizeEmails() {#getRecognizeEmails--}
```
public final boolean getRecognizeEmails()
```


Özelliklerdeki e-posta adreslerini tanıma algoritmasını etkinleştirmeye olanak tanır
değerler


**Returns:**
boolean
### setRecognizeEmails(boolean value) {#setRecognizeEmails-boolean-}
```
public final void setRecognizeEmails(boolean value)
```


Özelliklerdeki e-posta adreslerini tanıma algoritmasını etkinleştirmeye olanak tanır
değerler


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### getTrimTrailingWhitespaces() {#getTrimTrailingWhitespaces--}
```
public final boolean getTrimTrailingWhitespaces()
```


İç etiketlerdeki sondaki boşlukların kırpılmasını etkinleştirmeye olanak tanır
metin. Varsayılan olarak devre dışı bırakılır (false) \\u2014 son boşluklar
korunur.


**Returns:**
boolean
### setTrimTrailingWhitespaces(boolean value) {#setTrimTrailingWhitespaces-boolean-}
```
public final void setTrimTrailingWhitespaces(boolean value)
```


İç etiketlerdeki sondaki boşlukların kırpılmasını etkinleştirmeye olanak tanır
metin. Varsayılan olarak devre dışı bırakılır (false) \\u2014 son boşluklar
korunur.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### getAttributeValuesQuoteType() {#getAttributeValuesQuoteType--}
```
public final QuoteType getAttributeValuesQuoteType()
```


Özellik değerleri için alıntı tipini (tek veya çift tırnak) belirtmeye izin verir. Çift tırnaklar varsayılandır.


**Returns:**
[QuoteType](../../com.groupdocs.editor.htmlcss.serialization/quotetype)
### setAttributeValuesQuoteType(QuoteType value) {#setAttributeValuesQuoteType-com.groupdocs.editor.htmlcss.serialization.QuoteType-}
```
public final void setAttributeValuesQuoteType(QuoteType value)
```


Özellik değerleri için alıntı tipini (tek veya çift tırnak) belirtmeye izin verir. Çift tırnaklar varsayılandır.


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
