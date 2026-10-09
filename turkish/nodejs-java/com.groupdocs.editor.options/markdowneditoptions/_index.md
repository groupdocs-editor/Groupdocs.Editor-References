---
title: "MarkdownEditOptions"
second_title: "GroupDocs.Editor Node.js için Java API Referansı"
description: "Markdown formatındaki belgeleri düzenlemek için özel seçenekleri belirtmeye izin verir."
type: docs
weight: 21
url: /tr/nodejs-java/com.groupdocs.editor.options/markdowneditoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.IEditOptions](../../com.groupdocs.editor.options/ieditoptions)
```
public final class MarkdownEditOptions implements IEditOptions
```

Markdown formatındaki belgeleri düzenlemek için özel seçenekleri belirtmeye izin verir.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
|  | [MarkdownEditOptions()](#MarkdownEditOptions--) | MarkdownEditOptions sınıfının yeni bir örneğini oluşturur ve döndürür, |
tüm seçeneklerin varsayılan değerlerine ayarlandığı
|
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [getImageLoadCallback()](#getImageLoadCallback--) | Markdown belgesi dönüştürülürken görüntülerin nasıl kaydedileceğini kontrol etmeyi sağlar |
Html'e.
|
|  | [setImageLoadCallback(IMarkdownImageLoadCallback value)](#setImageLoadCallback-com.groupdocs.editor.options.IMarkdownImageLoadCallback-) | Markdown belgesi dönüştürülürken görüntülerin nasıl kaydedileceğini kontrol etmeyi sağlar |
Html'e.
|
### MarkdownEditOptions() {#MarkdownEditOptions--}
```
public MarkdownEditOptions()
```


MarkdownEditOptions sınıfının yeni bir örneğini oluşturur ve döndürür,
tüm seçeneklerin varsayılan değerlerine ayarlandığı


### getImageLoadCallback() {#getImageLoadCallback--}
```
public final IMarkdownImageLoadCallback getImageLoadCallback()
```


Markdown belgesi dönüştürülürken görüntülerin nasıl kaydedileceğini kontrol etmeyi sağlar
Html'e.
Değer: Görüntü kaydetme geri çağrısı.


**Returns:**
[IMarkdownImageLoadCallback](../../com.groupdocs.editor.options/imarkdownimageloadcallback)
### setImageLoadCallback(IMarkdownImageLoadCallback value) {#setImageLoadCallback-com.groupdocs.editor.options.IMarkdownImageLoadCallback-}
```
public final void setImageLoadCallback(IMarkdownImageLoadCallback value)
```


Markdown belgesi dönüştürülürken görüntülerin nasıl kaydedileceğini kontrol etmeyi sağlar
Html'e.
Değer: Görüntü kaydetme geri çağrısı.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [IMarkdownImageLoadCallback](../../com.groupdocs.editor.options/imarkdownimageloadcallback) |  |

