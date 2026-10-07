---
title: "WordProcessingEditOptions"
second_title: "GroupDocs.Editor Java için API Referansı"
description: "DOCX, RTF, ODT vb. gibi desteklenen tüm WordProcessing Words uyumlu formatlardaki belgeleri düzenlemek için özel seçenekler belirtmeye izin verir"
type: docs
weight: 44
url: /tr/java/com.groupdocs.editor.options/wordprocessingeditoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.IEditOptions](../../com.groupdocs.editor.options/ieditoptions)
```
public class WordProcessingEditOptions implements IEditOptions
```

Desteklenen tüm belgeleri düzenlemek için özel seçenekler belirtmeye izin verir
DOC(X), RTF, ODT vb. gibi WordProcessing (Words uyumlu) formatları

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
|  | [WordProcessingEditOptions()](#WordProcessingEditOptions--) | WordProcessingEditOptions sınıfının yeni bir örneğini oluşturur ve döndürür |
tüm seçeneklerin varsayılan değerlerine ayarlandığı sınıf
|
|  | [WordProcessingEditOptions(boolean enablePagination)](#WordProcessingEditOptions-boolean-) | WordProcessingEditOptions sınıfının yeni bir örneğini oluşturur ve döndürür |
belirtilen sayfalama ve diğer tüm seçeneklerin varsayılan olduğu sınıf
|
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [getEnablePagination()](#getEnablePagination--) | Sonuç HTML belgesinde sayfalama özelliğini etkinleştirmeye veya devre dışı bırakmaya izin verir. |
|
|  | [setEnablePagination(boolean value)](#setEnablePagination-boolean-) | Sonuç HTML belgesinde sayfalama özelliğini etkinleştirmeye veya devre dışı bırakmaya izin verir. |
|
|  | [getEnableLanguageInformation()](#getEnableLanguageInformation--) | Dil bilgisinin HTML işaretlemesine aktarılıp aktarılmayacağını belirtir |
'lang' HTML öznitelikleri biçiminde.
|
|  | [setEnableLanguageInformation(boolean value)](#setEnableLanguageInformation-boolean-) | Dil bilgisinin HTML işaretlemesine aktarılıp aktarılmayacağını belirtir |
'lang' HTML öznitelikleri biçiminde.
|
|  | [getExtractOnlyUsedFont()](#getExtractOnlyUsedFont--) | Yalnızca font kaynaklarını çıkartıp çıkarmayacağını gösteren bir değeri alır veya ayarlar |
belgenin metin içeriğinde kullanılıp kullanılmadığını.
|
|  | [setExtractOnlyUsedFont(boolean value)](#setExtractOnlyUsedFont-boolean-) | Yalnızca font kaynaklarını çıkartıp çıkarmayacağını gösteren bir değeri alır veya ayarlar |
belgenin metin içeriğinde kullanılıp kullanılmadığını.
|
|  | [getFontExtraction()](#getFontExtraction--) | Girişte kullanılan font kaynaklarını çıkarmaktan sorumludur |
WordProcessing belgesi.
|
|  | [setFontExtraction(int value)](#setFontExtraction-int-) | Girişte kullanılan font kaynaklarını çıkarmaktan sorumludur |
WordProcessing belgesi.
|
|  | [getInputControlsClassName()](#getInputControlsClassName--) | 'class' özniteliğine yerleştirilecek bir sınıf adı belirtmeye izin verir |
girişteki bir alanı temsil eden her HTML öğesindeki özniteliklere
WordProcessing belgesi.
|
|  | [setInputControlsClassName(String value)](#setInputControlsClassName-java.lang.String-) | 'class' özniteliğine yerleştirilecek bir sınıf adı belirtmeye izin verir |
girişteki bir alanı temsil eden her HTML öğesindeki özniteliklere
WordProcessing belgesi.
|
|  | [getUseInlineStyles()](#getUseInlineStyles--) | Giriş WordProcessing belgesinin stil ve biçimlendirme verilerinin nerede saklanacağını kontrol eder: dış stil sayfasında ( |
false
) ya da HTML işaretlemesinde satır içi stiller olarak (
true
).
|
|  | [setUseInlineStyles(boolean value)](#setUseInlineStyles-boolean-) | Giriş WordProcessing belgesinin stil ve biçimlendirme verilerinin nerede saklanacağını kontrol eder: dış stil sayfasında ( |
false
) ya da HTML işaretlemesinde satır içi stiller olarak (
true
).
|
### WordProcessingEditOptions() {#WordProcessingEditOptions--}
```
public WordProcessingEditOptions()
```


WordProcessingEditOptions sınıfının yeni bir örneğini oluşturur ve döndürür
tüm seçeneklerin varsayılan değerlerine ayarlandığı sınıf


### WordProcessingEditOptions(boolean enablePagination) {#WordProcessingEditOptions-boolean-}
```
public WordProcessingEditOptions(boolean enablePagination)
```


WordProcessingEditOptions sınıfının yeni bir örneğini oluşturur ve döndürür
belirtilen sayfalama ve diğer tüm seçeneklerin varsayılan olduğu sınıf


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | enablePagination | boolean | Sayfalama bayrağı, sayfalı mod için ayarlanmış HTML çıktısını etkinleştirir |
|

### getEnablePagination() {#getEnablePagination--}
```
public final boolean getEnablePagination()
```


Sonuçta oluşan HTML belgesinde sayfalama özelliğini etkinleştirmeye veya devre dışı bırakmaya izin verir. By
varsayılan olarak devre dışı bırakılmıştır (false).


**Returns:**
boolean
### setEnablePagination(boolean value) {#setEnablePagination-boolean-}
```
public final void setEnablePagination(boolean value)
```


Sonuçta oluşan HTML belgesinde sayfalama özelliğini etkinleştirmeye veya devre dışı bırakmaya izin verir. By
varsayılan olarak devre dışı bırakılmıştır (false).


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### getEnableLanguageInformation() {#getEnableLanguageInformation--}
```
public final boolean getEnableLanguageInformation()
```


Dil bilgisinin HTML işaretlemesine aktarılıp aktarılmayacağını belirtir
'lang' HTML öznitelikleri biçiminde. Bu seçenek, dönüşüm sırasında faydalı olabilir
çok dilli belgelerin dönüştürülmesi için. Varsayılan olarak devre dışıdır
(false).


**Returns:**
boolean
### setEnableLanguageInformation(boolean value) {#setEnableLanguageInformation-boolean-}
```
public final void setEnableLanguageInformation(boolean value)
```


Dil bilgisinin HTML işaretlemesine aktarılıp aktarılmayacağını belirtir
'lang' HTML öznitelikleri biçiminde. Bu seçenek, dönüşüm sırasında faydalı olabilir
çok dilli belgelerin dönüştürülmesi için. Varsayılan olarak devre dışıdır
(false).


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### getExtractOnlyUsedFont() {#getExtractOnlyUsedFont--}
```
public final boolean getExtractOnlyUsedFont()
```


Yalnızca font kaynaklarını çıkartıp çıkarmayacağını gösteren bir değeri alır veya ayarlar
belgenin metin içeriğinde kullanılıp kullanılmadığını.
Değer:  true  yalnızca belgenin metin içeriğinde kullanılan font kaynaklarını çıkarmak gerekiyorsa; aksi takdirde  false . Varsayılan değer  false .


*** ** * ** ***

WordProcessing belgesinde kullanılan tüm fontlar %100 doğrudan (metne uygulanarak) kullanılmaz. Font belge içinde referans alınmış ve hatta gömülü olabilir, ancak hiçbir metin parçasına uygulanmamış bir durum olabilir. Örneğin, bir font bir stile eklenmiş olabilir, ancak bu stil metnin hiçbir kısmına uygulanmamış olabilir. Bu seçenek bu tür durumların nasıl işleneceğini kontrol eder.

<br />



**Returns:**
boolean
### setExtractOnlyUsedFont(boolean value) {#setExtractOnlyUsedFont-boolean-}
```
public final void setExtractOnlyUsedFont(boolean value)
```


Yalnızca font kaynaklarını çıkartıp çıkarmayacağını gösteren bir değeri alır veya ayarlar
belgenin metin içeriğinde kullanılıp kullanılmadığını.
Değer:  true  yalnızca belgenin metin içeriğinde kullanılan font kaynaklarını çıkarmak gerekiyorsa; aksi takdirde  false . Varsayılan değer  false .


*** ** * ** ***

WordProcessing belgesinde kullanılan tüm fontlar %100 doğrudan (metne uygulanarak) kullanılmaz. Font belge içinde referans alınmış ve hatta gömülü olabilir, ancak hiçbir metin parçasına uygulanmamış bir durum olabilir. Örneğin, bir font bir stile eklenmiş olabilir, ancak bu stil metnin hiçbir kısmına uygulanmamış olabilir. Bu seçenek bu tür durumların nasıl işleneceğini kontrol eder.

<br />



**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### getFontExtraction() {#getFontExtraction--}
```
public final int getFontExtraction()
```


Girişte kullanılan font kaynaklarını çıkarmaktan sorumludur
WordProcessing belgesi. Varsayılan olarak hiçbir font çıkarılmaz
(NotExtract).


**Returns:**
int
### setFontExtraction(int value) {#setFontExtraction-int-}
```
public final void setFontExtraction(int value)
```


Girişte kullanılan font kaynaklarını çıkarmaktan sorumludur
WordProcessing belgesi. Varsayılan olarak hiçbir font çıkarılmaz
(NotExtract).


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getInputControlsClassName() {#getInputControlsClassName--}
```
public final String getInputControlsClassName()
```


'class' özniteliğine yerleştirilecek bir sınıf adı belirtmeye izin verir
girişteki bir alanı temsil eden her HTML öğesindeki özniteliklere
WordProcessing belgesi. Varsayılan olarak NULL'dur - 'class' öznitelikleri uygulanmaz.
uygulanır.


*** ** * ** ***

WordProcessing format ailesinin neredeyse tüm formatları alanlar içerir \\u2014 belirli belge varlıkları, kullanıcıların giriş verilerini elde etmeyi sağlar. Çok çeşitli alanlar vardır: metin kutuları, onay kutuları, kombinasyon kutuları, açılır listeler, düğmeler, tarih/saat seçiciler vb. Hepsi, giriş belgesinde mevcutsa girilen kullanıcı verilerini koruyarak en uygun HTML yapı ve öğelerine dönüştürülür. Belirli kullanım senaryolarında, tüm belge içeriğini düzenlemek yerine yalnızca istemci tarafında girilen verileri toplamak gerekir. Böyle bir durumda, istemci tarafında verileriyle birlikte bu giriş denetimlerini bir şekilde tanımlamak gerekir. Bu özellik, HTML işaretlemesindeki her giriş denetimi için uygulanacak bir sınıf adını belirtmeye olanak tanır, böylece istemci kodu HTML belge yapısında dolaşarak verileri toplayabilir.

<br />



**Returns:**
java.lang.String
### setInputControlsClassName(String value) {#setInputControlsClassName-java.lang.String-}
```
public final void setInputControlsClassName(String value)
```


'class' özniteliğine yerleştirilecek bir sınıf adı belirtmeye izin verir
girişteki bir alanı temsil eden her HTML öğesindeki özniteliklere
WordProcessing belgesi. Varsayılan olarak NULL'dur - 'class' öznitelikleri uygulanmaz.
uygulanır.


*** ** * ** ***

WordProcessing format ailesinin neredeyse tüm formatları alanlar içerir \\u2014 belirli belge varlıkları, kullanıcıların giriş verilerini elde etmeyi sağlar. Çok çeşitli alanlar vardır: metin kutuları, onay kutuları, kombinasyon kutuları, açılır listeler, düğmeler, tarih/saat seçiciler vb. Hepsi, giriş belgesinde mevcutsa girilen kullanıcı verilerini koruyarak en uygun HTML yapı ve öğelerine dönüştürülür. Belirli kullanım senaryolarında, tüm belge içeriğini düzenlemek yerine yalnızca istemci tarafında girilen verileri toplamak gerekir. Böyle bir durumda, istemci tarafında verileriyle birlikte bu giriş denetimlerini bir şekilde tanımlamak gerekir. Bu özellik, HTML işaretlemesindeki her giriş denetimi için uygulanacak bir sınıf adını belirtmeye olanak tanır, böylece istemci kodu HTML belge yapısında dolaşarak verileri toplayabilir.

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
) ya da HTML işaretlemesinde satır içi stiller olarak (
true
). Varsayılan olarak dış stil dosyaları kullanılır (
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
) ya da HTML işaretlemesinde satır içi stiller olarak (
true
). Varsayılan olarak dış stil dosyaları kullanılır (
false
).


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

