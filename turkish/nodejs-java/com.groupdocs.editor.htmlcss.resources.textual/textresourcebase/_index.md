---
title: "TextResourceBase"
second_title: "GroupDocs.Editor Node.js için Java API Referansı"
description: "Metin içeriği ve kodlaması olan herhangi bir desteklenen metin kaynağı için temel sınıf."
type: docs
weight: 11
url: /tr/nodejs-java/com.groupdocs.editor.htmlcss.resources.textual/textresourcebase/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.resources.IHtmlResource](../../com.groupdocs.editor.htmlcss.resources/ihtmlresource)
```
public abstract class TextResourceBase implements IHtmlResource
```

Metin içeriği ve kodlaması olan herhangi bir desteklenen metin kaynağı için temel sınıf.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
|  | [TextResourceBase(String name, String textualContent, Charset originalEncoding)](#TextResourceBase-java.lang.String-java.lang.String-java.nio.charset.Charset-) | Belirtilen metin içeriği ve kodlamasıyla yeni bir metin kaynağı oluşturur |
|
|  | [TextResourceBase(String name, InputStream binaryContent, Charset originalEncoding)](#TextResourceBase-java.lang.String-java.io.InputStream-java.nio.charset.Charset-) | Belirtilen bayt akışı ve kodlamadan yeni metin kaynağı oluşturur |
|
## Alanlar

| Alan | Açıklama |
| --- | --- |
| [Disposed](#Disposed) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [getName()](#getName--) | Bu metin kaynağının dosya uzantısı olmadan adını döndürür |
|
|  | [getFilenameWithExtension()](#getFilenameWithExtension--) | Bu metin kaynağının doğru dosya adını döndürür, bu ad |
ve uzantı
|
|  | [getEncoding()](#getEncoding--) | Bu metinsel kaynağın kodlamasını döndürür. |
|
|  | [getByteContent()](#getByteContent--) | Bu metin kaynağının içeriğini orijinal |
kodlama
|
|  | [getTextContent()](#getTextContent--) | Bu metin kaynağının içeriğini standart bir dize olarak döndürür |
|
|  | [save(String fullPathToFile)](#save-java.lang.String-) | Bu metin kaynağını belirtilen dosyaya kaydeder |
|
|  | [equals(IHtmlResource other)](#equals-com.groupdocs.editor.htmlcss.resources.IHtmlResource-) | Bu örneği belirtilenle eşitlik açısından kontrol eder. |
|
|  | [dispose()](#dispose--) | Bu metin kaynağını serbest bırakır, içeriğini serbest bırakarak çoğu |
metot ve özelliklerin çalışmaz hale gelmesini sağlar.
|
|  | [isDisposed()](#isDisposed--) | Bu metin kaynağının serbest bırakılıp bırakılmadığını belirler |
|
|  | [getType()](#getType--) | Uygulayan tip, metnin tipine ilişkin bilgiyi döndürmelidir |
kaynak
|
### TextResourceBase(String name, String textualContent, Charset originalEncoding) {#TextResourceBase-java.lang.String-java.lang.String-java.nio.charset.Charset-}
```
public TextResourceBase(String name, String textualContent, Charset originalEncoding)
```


Belirtilen metin içeriği ve kodlamasıyla yeni bir metin kaynağı oluşturur


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | ad | java.lang.String | Kaynağın benzersiz tanımlayıcısı olarak hizmet veren zorunlu adı. Genellikle bir dosya adıdır. |
|
|  | textualContent | java.lang.String | Kaynağın metinsel içeriği, NULL veya boş olamaz |
|
|  | originalEncoding | java.nio.charset.Charset | Kaynağın orijinal kodlaması, NULL veya boş olamaz |
|

### TextResourceBase(String name, InputStream binaryContent, Charset originalEncoding) {#TextResourceBase-java.lang.String-java.io.InputStream-java.nio.charset.Charset-}
```
public TextResourceBase(String name, InputStream binaryContent, Charset originalEncoding)
```


Belirtilen bayt akışı ve kodlamadan yeni metin kaynağı oluşturur


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | ad | java.lang.String | Kaynağın benzersiz tanımlayıcısı olarak hizmet veren zorunlu adı. Genellikle bir dosya adıdır. |
|
|  | binaryContent | java.io.InputStream | Bir kaynağın ikili içeriği bayt akışı olarak. NULL olamaz, serbest bırakılmış olmamalı, okunabilir ve aranabilir olmalıdır. |
|
|  | originalEncoding | java.nio.charset.Charset | Kaynağın orijinal kodlaması, NULL veya boş olamaz |
|

### Disposed {#Disposed}
```
public final Event<EventHandler> Disposed
```


### getName() {#getName--}
```
public final String getName()
```


Bu metin kaynağının dosya uzantısı olmadan adını döndürür


**Returns:**
java.lang.String
### getFilenameWithExtension() {#getFilenameWithExtension--}
```
public final String getFilenameWithExtension()
```


Bu metin kaynağının doğru dosya adını döndürür, bu ad
ve uzantı


**Returns:**
java.lang.String
### getEncoding() {#getEncoding--}
```
public final Charset getEncoding()
```


Bu metinsel kaynağın kodlamasını döndürür. Genellikle UTF-8 döndürür.


**Returns:**
java.nio.charset.Charset -
### getByteContent() {#getByteContent--}
```
public final InputStream getByteContent()
```


Bu metin kaynağının içeriğini orijinal
kodlama


**Returns:**
java.io.InputStream -
### getTextContent() {#getTextContent--}
```
public final String getTextContent()
```


Bu metin kaynağının içeriğini standart bir dize olarak döndürür


**Returns:**
java.lang.String -
### save(String fullPathToFile) {#save-java.lang.String-}
```
public final void save(String fullPathToFile)
```


Bu metin kaynağını belirtilen dosyaya kaydeder


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | fullPathToFile | java.lang.String | Dosyanın tam yolu, zaten mevcutsa oluşturulacak veya üzerine yazılacak |
|

### equals(IHtmlResource other) {#equals-com.groupdocs.editor.htmlcss.resources.IHtmlResource-}
```
public final boolean equals(IHtmlResource other)
```


Bu örneği belirtilenle eşitlik açısından kontrol eder.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | other | [IHtmlResource](../../com.groupdocs.editor.htmlcss.resources/ihtmlresource) | Bilinmeyen türde başka bir HTML kaynağı, aynı zamanda muhtemel TextResourceBase türevi |
|

**Returns:**
boolean - Eşitse true, eşit değilse false döndürür

### dispose() {#dispose--}
```
public final void dispose()
```


Bu metin kaynağını serbest bırakır, içeriğini serbest bırakarak çoğu
metotlar ve özellikler çalışmıyor. Birden çok çağrıya toleranslı.


### isDisposed() {#isDisposed--}
```
public final boolean isDisposed()
```


Bu metin kaynağının serbest bırakılıp bırakılmadığını belirler


**Returns:**
boolean -
### getType() {#getType--}
```
public abstract TextType getType()
```


Uygulayan tip, metnin tipine ilişkin bilgiyi döndürmelidir
kaynak


**Returns:**
[TextType](../../com.groupdocs.editor.htmlcss.resources.textual/texttype)
