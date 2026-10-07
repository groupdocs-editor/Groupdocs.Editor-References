---
title: "IHtmlResource"
second_title: "GroupDocs.Editor Java için API Referansı"
description: "Bilinmeyen HTML kaynağının (raster veya vektör görüntü, stil sayfası, yazı tipi, metin kaynağı, CSS, XML vb.) bir örneğini temsil eder"
type: docs
weight: 12
url: /tr/java/com.groupdocs.editor.htmlcss.resources/ihtmlresource/
---
**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.resources.IAuxDisposable](../../com.groupdocs.editor.htmlcss.resources/iauxdisposable)
```
public interface IHtmlResource extends IAuxDisposable
```

Bilinmeyen HTML kaynağının (raster veya vektör görüntü,
stil sayfası, yazı tipi, metin kaynağı (CSS, XML) vb.)

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [getName()](#getName--) | HTML kaynağının adı |
|
|  | [getFilenameWithExtension()](#getFilenameWithExtension--) | Belirtilen kaynağın uygun dosyayla doğru dosya adı |
uzantı
|
|  | [getType()](#getType--) | HTML kaynağının türü |
|
|  | [getByteContent()](#getByteContent--) | HTML kaynağının içeriği bir bayt akışı şeklinde |
|
|  | [getTextContent()](#getTextContent--) | HTML kaynağının içeriği base64 kodlu metin dizesi şeklinde |
ikili kaynaklar için veya metinsel kaynaklar için basit bir metin
|
|  | [save(String fullPathToFile)](#save-java.lang.String-) | Mevcut kaynağı belirtilen dosyaya kaydeder |
|
### getName() {#getName--}
```
public abstract String getName()
```


HTML kaynağının adı


**Returns:**
java.lang.String -
### getFilenameWithExtension() {#getFilenameWithExtension--}
```
public abstract String getFilenameWithExtension()
```


Belirtilen kaynağın uygun dosyayla doğru dosya adı
uzantı


**Returns:**
java.lang.String -
### getType() {#getType--}
```
public abstract IResourceType getType()
```


HTML kaynağının türü


**Returns:**
[IResourceType](../../com.groupdocs.editor.htmlcss.resources/iresourcetype) - 
### getByteContent() {#getByteContent--}
```
public abstract InputStream getByteContent()
```


HTML kaynağının içeriği bir bayt akışı şeklinde


**Returns:**
java.io.InputStream
### getTextContent() {#getTextContent--}
```
public abstract String getTextContent()
```


HTML kaynağının içeriği base64 kodlu metin dizesi şeklinde
ikili kaynaklar için veya metinsel kaynaklar için basit bir metin


**Returns:**
java.lang.String
### save(String fullPathToFile) {#save-java.lang.String-}
```
public abstract void save(String fullPathToFile)
```


Mevcut kaynağı belirtilen dosyaya kaydeder


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | fullPathToFile | java.lang.String | Mevcut kaynağın içeriğiyle oluşturulacak veya üzerine yazılacak dosyanın tam yolu |
|

