---
title: "WordProcessingEditOptions"
second_title: "GroupDocs.Editor Node.js için Java API Referansı"
description: "DOCX, RTF, ODT vb. gibi desteklenen tüm WordProcessing Words uyumlu biçimlerdeki belgeleri düzenlemek için özel seçenekler belirtmeye izin verir."
type: docs
weight: 44
url: /tr/nodejs-java/com.groupdocs.editor.options/wordprocessingeditoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.IEditOptions](../../com.groupdocs.editor.options/ieditoptions)
```
public class WordProcessingEditOptions implements IEditOptions
```

Desteklenen tüm belgeleri düzenlemek için özel seçenekler belirtmeye izin verir.
DOC(X), RTF, ODT vb. gibi WordProcessing (Words uyumlu) biçimler.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
|  | [WordProcessingEditOptions()](#WordProcessingEditOptions--) | WordProcessingEditOptions sınıfının yeni bir örneğini oluşturur ve döndürür. |
tüm seçeneklerin varsayılan değerlere ayarlandığı sınıf
|
|  | [WordProcessingEditOptions(boolean enablePagination)](#WordProcessingEditOptions-boolean-) | WordProcessingEditOptions sınıfının yeni bir örneğini oluşturur ve döndürür. |
belirtilen sayfalama ile ve diğer tüm seçeneklerin varsayılan olduğu sınıf
|
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [getEnablePagination()](#getEnablePagination--) | Ortaya çıkan HTML belgesinde sayfalama özelliğini etkinleştirmeye veya devre dışı bırakmaya izin verir. |
|
|  | [setEnablePagination(boolean value)](#setEnablePagination-boolean-) | Ortaya çıkan HTML belgesinde sayfalama özelliğini etkinleştirmeye veya devre dışı bırakmaya izin verir. |
|
|  | [getEnableLanguageInformation()](#getEnableLanguageInformation--) | Dil bilgisinin HTML işaretlemesine şu şekilde aktarılıp aktarılmayacağını belirtir |
'lang' HTML öznitelikleri biçiminde.
|
|  | [setEnableLanguageInformation(boolean value)](#setEnableLanguageInformation-boolean-) | Dil bilgisinin HTML işaretlemesine şu şekilde aktarılıp aktarılmayacağını belirtir |
'lang' HTML öznitelikleri biçiminde.
|
|  | [getExtractOnlyUsedFont()](#getExtractOnlyUsedFont--) | Yalnızca font kaynaklarını çıkarmayı gösteren bir değeri alır veya ayarlar |
belgenin metin içeriğinde kullanılıp kullanılmadığını.
|
|  | [setExtractOnlyUsedFont(boolean value)](#setExtractOnlyUsedFont-boolean-) | Yalnızca font kaynaklarını çıkarmayı gösteren bir değeri alır veya ayarlar |
belgenin metin içeriğinde kullanılıp kullanılmadığını.
|
|  | [getFontExtraction()](#getFontExtraction--) | Girişte kullanılan font kaynaklarını çıkarmaktan sorumludur. |
WordProcessing belgesi.
|
|  | [setFontExtraction(int value)](#setFontExtraction-int-) | Girişte kullanılan font kaynaklarını çıkarmaktan sorumludur. |
WordProcessing belgesi.
|
|  | [getInputControlsClassName()](#getInputControlsClassName--) | Bir sınıf adı belirtmeye izin verir, bu sınıf adı 'class' özniteliğine yerleştirilecektir |
girişteki bazı alanı temsil eden her HTML öğesindeki öznitelikler
WordProcessing belgesi.
|
|  | [setInputControlsClassName(String value)](#setInputControlsClassName-java.lang.String-) | Bir sınıf adı belirtmeye izin verir, bu sınıf adı 'class' özniteliğine yerleştirilecektir |
girişteki bazı alanı temsil eden her HTML öğesindeki öznitelikler
WordProcessing belgesi.
|
|  | [getUseInlineStyles()](#getUseInlineStyles--) | Giriş WordProcessing belgesinin stil ve biçimlendirme verilerinin nerede saklanacağını kontrol eder: dış stil sayfasında ( |
false
) veya HTML işaretlemesinde satır içi stiller olarak (
true
).
|
|  | [setUseInlineStyles(boolean value)](#setUseInlineStyles-boolean-) | Giriş WordProcessing belgesinin stil ve biçimlendirme verilerinin nerede saklanacağını kontrol eder: dış stil sayfasında ( |
false
) veya HTML işaretlemesinde satır içi stiller olarak (
true
).
|
### WordProcessingEditOptions() {#WordProcessingEditOptions--}
```
public WordProcessingEditOptions()
```


WordProcessingEditOptions sınıfının yeni bir örneğini oluşturur ve döndürür.
tüm seçeneklerin varsayılan değerlere ayarlandığı sınıf


### WordProcessingEditOptions(boolean enablePagination) {#WordProcessingEditOptions-boolean-}
```
public WordProcessingEditOptions(boolean enablePagination)
```


WordProcessingEditOptions sınıfının yeni bir örneğini oluşturur ve döndürür.
belirtilen sayfalama ile ve diğer tüm seçeneklerin varsayılan olduğu sınıf


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | enablePagination | boolean | Sayfalama moduna ayarlanmış HTML çıktısını etkinleştiren sayfalama bayrağı |
|

### getEnablePagination() {#getEnablePagination--}
```
public final boolean getEnablePagination()
```


Sonuç HTML belgesinde sayfalama özelliğini etkinleştirmeye veya devre dışı bırakmaya izin verir. By
varsayılan olarak devre dışıdır (false).


**Returns:**
boolean
### setEnablePagination(boolean value) {#setEnablePagination-boolean-}
```
public final void setEnablePagination(boolean value)
```


Sonuç HTML belgesinde sayfalama özelliğini etkinleştirmeye veya devre dışı bırakmaya izin verir. By
varsayılan olarak devre dışıdır (false).


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### getEnableLanguageInformation() {#getEnableLanguageInformation--}
```
public final boolean getEnableLanguageInformation()
```


Dil bilgisinin HTML işaretlemesine şu şekilde aktarılıp aktarılmayacağını belirtir
'lang' HTML özniteliklerinin bir biçimi. Bu seçenek çift yönlü dönüşüm için faydalı olabilir
çok dilli belgelerin dönüştürülmesi. Varsayılan olarak devre dışıdır
(false).


**Returns:**
boolean
### setEnableLanguageInformation(boolean value) {#setEnableLanguageInformation-boolean-}
```
public final void setEnableLanguageInformation(boolean value)
```


Dil bilgisinin HTML işaretlemesine şu şekilde aktarılıp aktarılmayacağını belirtir
'lang' HTML özniteliklerinin bir biçimi. Bu seçenek çift yönlü dönüşüm için faydalı olabilir
çok dilli belgelerin dönüştürülmesi. Varsayılan olarak devre dışıdır
(false).


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### getExtractOnlyUsedFont() {#getExtractOnlyUsedFont--}
```
public final boolean getExtractOnlyUsedFont()
```


Yalnızca font kaynaklarını çıkarmayı gösteren bir değeri alır veya ayarlar
belgenin metin içeriğinde kullanılıp kullanılmadığını.
Değer:  true  yalnızca belge metin içeriğinde kullanılan yazı tipi kaynaklarını çıkarmak gerektiğinde; aksi takdirde  false . Varsayılan değer  false .


*** ** * ** ***

WordProcessing belgesinde kullanılan tüm yazı tipleri %100 doğrudan (metne uygulanarak) kullanılmaz. Belge içinde bir yazı tipine referans verilmiş ve hatta gömülü olsa bile, hiçbir metin parçasına uygulanmamış bir durum olabilir. Örneğin, bir yazı tipi bir stile eklenmiş olabilir, ancak bu stil metnin hiçbir kısmına uygulanmaz. Bu seçenek bu tür durumların nasıl işleneceğini kontrol eder.

<br />



**Returns:**
boolean
### setExtractOnlyUsedFont(boolean value) {#setExtractOnlyUsedFont-boolean-}
```
public final void setExtractOnlyUsedFont(boolean value)
```


Yalnızca font kaynaklarını çıkarmayı gösteren bir değeri alır veya ayarlar
belgenin metin içeriğinde kullanılıp kullanılmadığını.
Değer:  true  yalnızca belge metin içeriğinde kullanılan yazı tipi kaynaklarını çıkarmak gerektiğinde; aksi takdirde  false . Varsayılan değer  false .


*** ** * ** ***

WordProcessing belgesinde kullanılan tüm yazı tipleri %100 doğrudan (metne uygulanarak) kullanılmaz. Belge içinde bir yazı tipine referans verilmiş ve hatta gömülü olsa bile, hiçbir metin parçasına uygulanmamış bir durum olabilir. Örneğin, bir yazı tipi bir stile eklenmiş olabilir, ancak bu stil metnin hiçbir kısmına uygulanmaz. Bu seçenek bu tür durumların nasıl işleneceğini kontrol eder.

<br />



**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### getFontExtraction() {#getFontExtraction--}
```
public final int getFontExtraction()
```


Girişte kullanılan font kaynaklarını çıkarmaktan sorumludur.
WordProcessing belgesi. Varsayılan olarak hiçbir yazı tipi çıkarmaz
(NotExtract).


**Returns:**
int
### setFontExtraction(int value) {#setFontExtraction-int-}
```
public final void setFontExtraction(int value)
```


Girişte kullanılan font kaynaklarını çıkarmaktan sorumludur.
WordProcessing belgesi. Varsayılan olarak hiçbir yazı tipi çıkarmaz
(NotExtract).


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getInputControlsClassName() {#getInputControlsClassName--}
```
public final String getInputControlsClassName()
```


Bir sınıf adı belirtmeye izin verir, bu sınıf adı 'class' özniteliğine yerleştirilecektir
girişteki bazı alanı temsil eden her HTML öğesindeki öznitelikler
WordProcessing belgesi. Varsayılan olarak NULL - 'class' öznitelikleri
uygulanmaz.


*** ** * ** ***

Almost all formats from WordProcessing format family contain fields \u2014 specific document entities, that allow to obtain input data from users. There are a wide variety of fields: text-boxes, checkboxes, combo-boxes, drop down lists, buttons, date/time pickers, etc. All of them are translated into the most appropriate HTML structures and elements, with preserving the entered user data, if they are present in the input document. In specific use-cases it is required only to gather entered data on a client-side instead of editing the entire document content. For such case it is required to identify input controls in some way for fetching them with their data on client-side. This property allows to specify a class name, that will be applied for every input control in HTML markup, so client code will be able to traverse over HTML document structure and gather data.

<br />



**Returns:**
java.lang.String
### setInputControlsClassName(String value) {#setInputControlsClassName-java.lang.String-}
```
public final void setInputControlsClassName(String value)
```


Bir sınıf adı belirtmeye izin verir, bu sınıf adı 'class' özniteliğine yerleştirilecektir
girişteki bazı alanı temsil eden her HTML öğesindeki öznitelikler
WordProcessing belgesi. Varsayılan olarak NULL - 'class' öznitelikleri
uygulanmaz.


*** ** * ** ***

Almost all formats from WordProcessing format family contain fields \u2014 specific document entities, that allow to obtain input data from users. There are a wide variety of fields: text-boxes, checkboxes, combo-boxes, drop down lists, buttons, date/time pickers, etc. All of them are translated into the most appropriate HTML structures and elements, with preserving the entered user data, if they are present in the input document. In specific use-cases it is required only to gather entered data on a client-side instead of editing the entire document content. For such case it is required to identify input controls in some way for fetching them with their data on client-side. This property allows to specify a class name, that will be applied for every input control in HTML markup, so client code will be able to traverse over HTML document structure and gather data.

<br />



**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### getUseInlineStyles() {#getUseInlineStyles--}
```
public final boolean getUseInlineStyles()
```


Giriş WordProcessing belgesinin stil ve biçimlendirme verilerinin nerede saklanacağını kontrol eder: dış stil sayfasında (
false
) veya HTML işaretlemesinde satır içi stiller olarak (
true
). Varsayılan olarak dış stiller kullanılır (
false
).


**Returns:**
boolean
### setUseInlineStyles(boolean value) {#setUseInlineStyles-boolean-}
```
public final void setUseInlineStyles(boolean value)
```


Giriş WordProcessing belgesinin stil ve biçimlendirme verilerinin nerede saklanacağını kontrol eder: dış stil sayfasında (
false
) veya HTML işaretlemesinde satır içi stiller olarak (
true
). Varsayılan olarak dış stiller kullanılır (
false
).


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

