---
title: "MarkdownImageLoadArgs"
second_title: "GroupDocs.Editor Java için API Referansı"
description: "MGroupDocs.Editor.Options.IMarkdownImageLoadCallback.ProcessImageMarkdownImageLoadArgs olayı için veri sağlar."
type: docs
weight: 22
url: /tr/java/com.groupdocs.editor.options/markdownimageloadargs/
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
|  | [getImageFileName()](#getImageFileName--) | Markdown belgesinde olduğu gibi dosya adını alır veya ayarlar |
işlenecek.
|
|  | [setImageFileName(String value)](#setImageFileName-java.lang.String-) | Markdown belgesinde olduğu gibi dosya adını alır veya ayarlar |
işlenecek.
|
|  | [isAbsoluteUri()](#isAbsoluteUri--) | Bu görselin mutlak URI bağlantısına sahip olup olmadığını gösteren bir değer al. |
|
|  | [setAbsoluteUri(boolean value)](#setAbsoluteUri-boolean-) | Bu görselin mutlak URI bağlantısına sahip olup olmadığını gösteren bir değer al. |
|
|  | [setData(byte[] data)](#setData-byte---) | Kaynak için, kullanıcının sağladığı veriyi ayarlar; eğer |

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


Markdown belgesinde olduğu gibi dosya adını alır veya ayarlar
işlenecek.


**Returns:**
java.lang.String
### setImageFileName(String value) {#setImageFileName-java.lang.String-}
```
public final void setImageFileName(String value)
```


Markdown belgesinde olduğu gibi dosya adını alır veya ayarlar
işlenecek.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### isAbsoluteUri() {#isAbsoluteUri--}
```
public final boolean isAbsoluteUri()
```


Bu görselin mutlak URI bağlantısına sahip olup olmadığını gösteren bir değer al.
Değer:  true  bu görsel mutlak URI bağlantısına sahipse; aksi takdirde,  false .


**Returns:**
boolean
### setAbsoluteUri(boolean value) {#setAbsoluteUri-boolean-}
```
public final void setAbsoluteUri(boolean value)
```


Bu görselin mutlak URI bağlantısına sahip olup olmadığını gösteren bir değer al.
Değer:  true  bu görsel mutlak URI bağlantısına sahipse; aksi takdirde,  false .


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### setData(byte[] data) {#setData-byte---}
```
public final void setData(byte[] data)
```


Kaynak için, kullanıcının sağladığı veriyi ayarlar; eğer

M:GroupDocs.Editor.Options.IMarkdownImageLoadCallback.ProcessImage(MarkdownImageLoadArgs)



**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| veri | byte[] |  |

