---
title: "MarkdownEditOptions"
second_title: "GroupDocs.Editor Java için API Referansı"
description: "Markdown formatında belgeleri düzenlemek için özel seçenekleri belirtmeye izin verir."
type: docs
weight: 21
url: /tr/java/com.groupdocs.editor.options/markdowneditoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.IEditOptions](../../com.groupdocs.editor.options/ieditoptions)
```
public final class MarkdownEditOptions implements IEditOptions
```

Markdown formatında belgeleri düzenlemek için özel seçenekleri belirtmeye izin verir.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
|  | [MarkdownEditOptions()](#MarkdownEditOptions--) | MarkdownEditOptions sınıfının yeni bir örneğini oluşturur ve döndürür, |
tüm seçeneklerin varsayılan değerlerine ayarlandığı yerde
|
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [getImageLoadCallback()](#getImageLoadCallback--) | Markdown belgesi dönüştürülürken görüntülerin nasıl kaydedileceğini kontrol etmeye izin verir |
HTML'ye.
|
|  | [setImageLoadCallback(IMarkdownImageLoadCallback value)](#setImageLoadCallback-com.groupdocs.editor.options.IMarkdownImageLoadCallback-) | Markdown belgesi dönüştürülürken görüntülerin nasıl kaydedileceğini kontrol etmeye izin verir |
HTML'ye.
|
### MarkdownEditOptions() {#MarkdownEditOptions--}
```
public MarkdownEditOptions()
```


MarkdownEditOptions sınıfının yeni bir örneğini oluşturur ve döndürür,
tüm seçeneklerin varsayılan değerlerine ayarlandığı yerde


### getImageLoadCallback() {#getImageLoadCallback--}
```
public final IMarkdownImageLoadCallback getImageLoadCallback()
```


Markdown belgesi dönüştürülürken görüntülerin nasıl kaydedileceğini kontrol etmeye izin verir
HTML'ye.
Değer: Görüntü kaydetme geri çağrısı.


**Returns:**
[IMarkdownImageLoadCallback](../../com.groupdocs.editor.options/imarkdownimageloadcallback)
### setImageLoadCallback(IMarkdownImageLoadCallback value) {#setImageLoadCallback-com.groupdocs.editor.options.IMarkdownImageLoadCallback-}
```
public final void setImageLoadCallback(IMarkdownImageLoadCallback value)
```


Markdown belgesi dönüştürülürken görüntülerin nasıl kaydedileceğini kontrol etmeye izin verir
HTML'ye.
Değer: Görüntü kaydetme geri çağrısı.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [IMarkdownImageLoadCallback](../../com.groupdocs.editor.options/imarkdownimageloadcallback) |  |

