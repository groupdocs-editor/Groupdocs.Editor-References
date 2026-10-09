---
title: "MarkdownImageLoadArgs"
second_title: "GroupDocs.Editor Node.js için Java API Referansı"
description: "MGroupDocs.Editor.Options.IMarkdownImageLoadCallback.ProcessImageMarkdownImageLoadArgs olayı için veri sağlar."
type: docs
weight: 22
url: /tr/nodejs-java/com.groupdocs.editor.options/markdownimageloadargs/
---
**Inheritance:**
java.lang.Object
```
public class MarkdownImageLoadArgs
```

Veri sağlar

M:GroupDocs.Editor.Options.IMarkdownImageLoadCallback.ProcessImage(MarkdownImageLoadArgs)

olay.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [MarkdownImageLoadArgs()](#MarkdownImageLoadArgs--) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [getImageFileName()](#getImageFileName--) | Markdown belgesindeki haliyle dosya adını alır veya ayarlar |
işleyecek.
|
|  | [setImageFileName(String value)](#setImageFileName-java.lang.String-) | Markdown belgesindeki haliyle dosya adını alır veya ayarlar |
işleyecek.
|
|  | [isAbsoluteUri()](#isAbsoluteUri--) | Bu görüntünün mutlak URI bağlantısına sahip olup olmadığını gösteren bir değer al. |
|
|  | [setAbsoluteUri(boolean value)](#setAbsoluteUri-boolean-) | Bu görüntünün mutlak URI bağlantısına sahip olup olmadığını gösteren bir değer al. |
|
|  | [setData(byte[] data)](#setData-byte---) | Kullanıcı tarafından sağlanan kaynak verisini ayarlar; bu, şu durumda kullanılır |

M:GroupDocs.Editor.Options.IMarkdownImageLoadCallback.ProcessImage(MarkdownImageLoadArgs)

|
### MarkdownImageLoadArgs() {#MarkdownImageLoadArgs--}
```
public MarkdownImageLoadArgs()
```


### getImageFileName() {#getImageFileName--}
```
public final String getImageFileName()
```


Markdown belgesindeki haliyle dosya adını alır veya ayarlar
işleyecek.


**Returns:**
java.lang.String
### setImageFileName(String value) {#setImageFileName-java.lang.String-}
```
public final void setImageFileName(String value)
```


Markdown belgesindeki haliyle dosya adını alır veya ayarlar
işleyecek.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### isAbsoluteUri() {#isAbsoluteUri--}
```
public final boolean isAbsoluteUri()
```


Bu görüntünün mutlak URI bağlantısına sahip olup olmadığını gösteren bir değer al.
Değer:  true  bu görüntünün mutlak URI bağlantısı varsa; aksi takdirde,  false .


**Returns:**
boolean
### setAbsoluteUri(boolean value) {#setAbsoluteUri-boolean-}
```
public final void setAbsoluteUri(boolean value)
```


Bu görüntünün mutlak URI bağlantısına sahip olup olmadığını gösteren bir değer al.
Değer:  true  bu görüntünün mutlak URI bağlantısı varsa; aksi takdirde,  false .


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### setData(byte[] data) {#setData-byte---}
```
public final void setData(byte[] data)
```


Kullanıcı tarafından sağlanan kaynak verisini ayarlar; bu, şu durumda kullanılır

M:GroupDocs.Editor.Options.IMarkdownImageLoadCallback.ProcessImage(MarkdownImageLoadArgs)



**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| veri | byte[] |  |

