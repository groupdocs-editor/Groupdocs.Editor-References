---
title: "FixedLayoutEditOptionsBase"
second_title: "GroupDocs.Editor Java için API Referansı"
description: "PDF ve XPS gibi sabit düzen formatlarındaki tüm belgeler için seçeneklerin temel soyut sınıfı."
type: docs
weight: 16
url: /tr/java/com.groupdocs.editor.options/fixedlayouteditoptionsbase/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.IEditOptions](../../com.groupdocs.editor.options/ieditoptions)
```
public abstract class FixedLayoutEditOptionsBase implements IEditOptions
```

PDF ve XPS gibi sabit düzen formatlarındaki tüm belgeler için seçeneklerin temel soyut sınıfı.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [FixedLayoutEditOptionsBase()](#FixedLayoutEditOptionsBase--) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [getSkipImages()](#getSkipImages--) | Giriş sabit düzen belgesini sonuç HTML'ye dönüştürürken görüntülerin atlanıp atlanmayacağını belirten bayrağı alır veya ayarlar. |
|
|  | [setSkipImages(boolean value)](#setSkipImages-boolean-) | Giriş sabit düzen belgesini sonuç HTML'ye dönüştürürken görüntülerin atlanıp atlanmayacağını belirten bayrağı alır veya ayarlar. |
|
|  | [getPages()](#getPages--) | İşlenecek bir sayfa aralığı ayarlamaya olanak tanır. |
|
|  | [setPages(PageRange value)](#setPages-com.groupdocs.editor.options.PageRange-) | İşlenecek bir sayfa aralığı ayarlamaya olanak tanır. |
|
|  | [getEnablePagination()](#getEnablePagination--) | Sonuç HTML belgesinde sayfalama özelliğini etkinleştirmeye (true) veya devre dışı bırakmaya (false) olanak tanır. |
|
|  | [setEnablePagination(boolean value)](#setEnablePagination-boolean-) | Sonuç HTML belgesinde sayfalama özelliğini etkinleştirmeye (true) veya devre dışı bırakmaya (false) olanak tanır. |
|
### FixedLayoutEditOptionsBase() {#FixedLayoutEditOptionsBase--}
```
public FixedLayoutEditOptionsBase()
```


### getSkipImages() {#getSkipImages--}
```
public final boolean getSkipImages()
```


Giriş sabit düzen belgesini sonuç HTML'ye dönüştürürken görüntülerin atlanıp atlanmayacağını belirten bayrağı alır veya ayarlar. Varsayılan false'tur - görüntüler korunur.


**Returns:**
boolean
### setSkipImages(boolean value) {#setSkipImages-boolean-}
```
public final void setSkipImages(boolean value)
```


Giriş sabit düzen belgesini sonuç HTML'ye dönüştürürken görüntülerin atlanıp atlanmayacağını belirten bayrağı alır veya ayarlar. Varsayılan false'tur - görüntüler korunur.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### getPages() {#getPages--}
```
public final PageRange getPages()
```


İşlenecek bir sayfa aralığı ayarlamaya olanak tanır. Varsayılan olarak sabit düzen belgesinin tüm sayfaları işlenir.


**Returns:**
[PageRange](../../com.groupdocs.editor.options/pagerange)
### setPages(PageRange value) {#setPages-com.groupdocs.editor.options.PageRange-}
```
public final void setPages(PageRange value)
```


İşlenecek bir sayfa aralığı ayarlamaya olanak tanır. Varsayılan olarak sabit düzen belgesinin tüm sayfaları işlenir.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [PageRange](../../com.groupdocs.editor.options/pagerange) |  |

### getEnablePagination() {#getEnablePagination--}
```
public final boolean getEnablePagination()
```


Sonuç HTML belgesinde sayfalama özelliğini etkinleştirmeye (true) veya devre dışı bırakmaya (false) olanak tanır. Varsayılan olarak devre dışıdır (false).

<br />

*** ** * ** ***

Sabit düzen formatındaki belgeler (özellikle PDF ve XPS), özünde kesinlikle sayfalıdır, içerikleri sabit bir düzene sahiptir ve sayfalara bölünür. Ancak sonuçta elde edilen düzenlenebilir HTML, sayfasız veya sayfalı görünümde temsil edilebilir.

<br />



**Returns:**
boolean
### setEnablePagination(boolean value) {#setEnablePagination-boolean-}
```
public final void setEnablePagination(boolean value)
```


Sonuç HTML belgesinde sayfalama özelliğini etkinleştirmeye (true) veya devre dışı bırakmaya (false) olanak tanır. Varsayılan olarak devre dışıdır (false).

<br />

*** ** * ** ***

Sabit düzen formatındaki belgeler (özellikle PDF ve XPS), özünde kesinlikle sayfalıdır, içerikleri sabit bir düzene sahiptir ve sayfalara bölünür. Ancak sonuçta elde edilen düzenlenebilir HTML, sayfasız veya sayfalı görünümde temsil edilebilir.

<br />



**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

