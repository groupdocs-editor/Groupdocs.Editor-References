---
title: "EbookEditOptions"
second_title: "GroupDocs.Editor Java için API Referansı"
description: "Desteklenen tüm formatlarda (ePub, MOBI ve AZW3) E-kitap belgelerini düzenlemek için özel seçenekleri belirtmeye ve ayarlamaya izin verir."
type: docs
weight: 12
url: /tr/java/com.groupdocs.editor.options/ebookeditoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.IEditOptions](../../com.groupdocs.editor.options/ieditoptions)
```
public final class EbookEditOptions implements IEditOptions
```

Tüm desteklenen formatlarda (ePub, MOBI ve AZW3) E-kitap belgelerini düzenlemek için özel seçenekleri belirtmeye ve ayarlamaya izin verir.

<br />

*** ** * ** ***

Desteklenen e-Kitap formatları:

1. [ePub](../https://docs.fileformat.com/ebook/epub/) (Elektronik Yayın)
2. [MOBI](../https://docs.fileformat.com/ebook/mobi/) (MobiPocket)
3. [AZW3](../https://docs.fileformat.com/ebook/azw3/) (Kindle Format 8t)

<br />


## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
|  | [EbookEditOptions()](#EbookEditOptions--) | Tüm seçeneklerin varsayılan değerlere ayarlandığı [EbookEditOptions](../../com.groupdocs.editor.options/ebookeditoptions) sınıfının yeni bir örneğini başlatır |
|
|  | [EbookEditOptions(boolean enablePagination)](#EbookEditOptions-boolean-) | Belirtilen sayfalama moduyla [EbookEditOptions](../../com.groupdocs.editor.options/ebookeditoptions) sınıfının yeni bir örneğini başlatır |
|
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [getEnablePagination()](#getEnablePagination--) | Sonuç HTML belgesinde sayfalama özelliğini etkinleştirmeye veya devre dışı bırakmaya izin verir. |
|
|  | [setEnablePagination(boolean value)](#setEnablePagination-boolean-) | Sonuç HTML belgesinde sayfalama özelliğini etkinleştirmeye veya devre dışı bırakmaya izin verir. |
|
|  | [getEnableLanguageInformation()](#getEnableLanguageInformation--) | Dil bilgisinin HTML işaretlemesine 'lang' HTML öznitelikleri biçiminde dışa aktarılıp aktarılmayacağını belirtir. |
|
|  | [setEnableLanguageInformation(boolean value)](#setEnableLanguageInformation-boolean-) | Dil bilgisinin HTML işaretlemesine 'lang' HTML öznitelikleri biçiminde dışa aktarılıp aktarılmayacağını belirtir. |
|
### EbookEditOptions() {#EbookEditOptions--}
```
public EbookEditOptions()
```


Tüm seçeneklerin varsayılan değerlere ayarlandığı [EbookEditOptions](../../com.groupdocs.editor.options/ebookeditoptions) sınıfının yeni bir örneğini başlatır


### EbookEditOptions(boolean enablePagination) {#EbookEditOptions-boolean-}
```
public EbookEditOptions(boolean enablePagination)
```


Belirtilen sayfalama moduyla [EbookEditOptions](../../com.groupdocs.editor.options/ebookeditoptions) sınıfının yeni bir örneğini başlatır


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | enablePagination | boolean | Sonuç HTML belgesindeki e-kitap içeriğinin sayfalamasını etkinleştirir ( true ) veya devre dışı bırakır ( false ). Varsayılan olarak devre dışıdır ( false ). |
|

### getEnablePagination() {#getEnablePagination--}
```
public final boolean getEnablePagination()
```


Sonuç HTML belgesinde sayfalamayı etkinleştirmeye veya devre dışı bırakmaya izin verir. Varsayılan olarak devre dışıdır (
false
).

<br />

*** ** * ** ***

Özünde, çoğu e-kitap formatı dahili olarak Office Open XML gibi bir akış formatıdır; içerik bütün bir yapıdadır ve bölümlere ayrılır ancak sayfalara bölünmez. Bununla birlikte, sayfa numaraları, dipnotlar, üstbilgi/altbilgi gibi sayfaya özgü bilgiler içerir. Bazı e-kitap okuyucular içerği sayfalara bölerek gösterir, diğerleri (özellikle mobil) \\u2014 bölmez. Bu seçenek, e-kitap içeriğinin düzenleme sırasında HTML/CSS içinde nasıl temsil edileceğini kontrol etmeye olanak tanır \\u2014 kayan ( false ) veya sayfalı ( true ) görünümde.

<br />



**Returns:**
boolean
### setEnablePagination(boolean value) {#setEnablePagination-boolean-}
```
public final void setEnablePagination(boolean value)
```


Sonuç HTML belgesinde sayfalamayı etkinleştirmeye veya devre dışı bırakmaya izin verir. Varsayılan olarak devre dışıdır (
false
).

<br />

*** ** * ** ***

Özünde, çoğu e-kitap formatı dahili olarak Office Open XML gibi bir akış formatıdır; içerik bütün bir yapıdadır ve bölümlere ayrılır ancak sayfalara bölünmez. Bununla birlikte, sayfa numaraları, dipnotlar, üstbilgi/altbilgi gibi sayfaya özgü bilgiler içerir. Bazı e-kitap okuyucular içerği sayfalara bölerek gösterir, diğerleri (özellikle mobil) \\u2014 bölmez. Bu seçenek, e-kitap içeriğinin düzenleme sırasında HTML/CSS içinde nasıl temsil edileceğini kontrol etmeye olanak tanır \\u2014 kayan ( false ) veya sayfalı ( true ) görünümde.

<br />



**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### getEnableLanguageInformation() {#getEnableLanguageInformation--}
```
public final boolean getEnableLanguageInformation()
```


Dil bilgisinin HTML işaretlemesine 'lang' HTML öznitelikleri biçiminde dışa aktarılıp aktarılmayacağını belirtir.
Bu seçenek, çok dilli belgelerin çift yönlü dönüşümü için yararlı olabilir. Varsayılan olarak devre dışıdır (
false
).


**Returns:**
boolean
### setEnableLanguageInformation(boolean value) {#setEnableLanguageInformation-boolean-}
```
public final void setEnableLanguageInformation(boolean value)
```


Dil bilgisinin HTML işaretlemesine 'lang' HTML öznitelikleri biçiminde dışa aktarılıp aktarılmayacağını belirtir.
Bu seçenek, çok dilli belgelerin çift yönlü dönüşümü için yararlı olabilir. Varsayılan olarak devre dışıdır (
false
).


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

