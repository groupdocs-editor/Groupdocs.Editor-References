---
title: "FontResourceBase"
second_title: "GroupDocs.Editor Java için API Referansı"
description: "HTML belgesi için bir kaynak olarak desteklenen herhangi bir yazı tipi türünün temel sınıfı, tüm özellikleriyle birlikte"
type: docs
weight: 11
url: /tr/java/com.groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.resources.IHtmlResource](../../com.groupdocs.editor.htmlcss.resources/ihtmlresource)
```
public abstract class FontResourceBase implements IHtmlResource
```

HTML belgesi için bir kaynak olarak desteklenen herhangi bir yazı tipi türünün temel sınıfı
tüm özellikleriyle

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [FontResourceBase()](#FontResourceBase--) |  |
## Alanlar

| Alan | Açıklama |
| --- | --- |
|  | [Disposed](#Disposed) | Bu yazı tipi serbest bırakıldığında gerçekleşen olay |
|
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [getName()](#getName--) | Bu yazı tipi kaynağının adını döndürür. |
|
|  | [getFilenameWithExtension()](#getFilenameWithExtension--) | Bu yazı tipi kaynağının doğru dosya adını döndürür, adı içeren |
ve uzantıyı.
|
|  | [getByteContent()](#getByteContent--) | Bu yazı tipinin içeriğini bayt akışı olarak döndürür. |
|
|  | [getTextContent()](#getTextContent--) | Bu yazı tipinin içeriğini base64 kodlu dize olarak döndürür. |
|
|  | [save(String fullPathToFile)](#save-java.lang.String-) | Bu yazı tipini belirtilen dosyaya kaydeder |
|
|  | [equals(IHtmlResource other)](#equals-com.groupdocs.editor.htmlcss.resources.IHtmlResource-) | Bu örneği belirtilen HTML kaynağıyla referans eşitliğine göre kontrol eder |
|
|  | [equals(FontResourceBase other)](#equals-com.groupdocs.editor.htmlcss.resources.fonts.FontResourceBase-) | Bu örneği belirtilen yazı tipi kaynağıyla referans eşitliğine göre kontrol eder |
|
|  | [dispose()](#dispose--) | Bu yazı tipi kaynağını serbest bırakır, içeriğini serbest bırakır ve çoğunu |
metot ve özellikleri çalışmaz hâle getirir
|
|  | [isDisposed()](#isDisposed--) | Bu yazı tipinin serbest bırakılıp bırakılmadığını belirler |
|
|  | [getType()](#getType--) | Uygulama türü, belirli bir tipin türü hakkında bilgi döndürmelidir |
yazı tipi kaynağını belirli FontType tipinin bir örneği olarak, ki
tüm tip-özel bilgileri kapsar
|
### FontResourceBase() {#FontResourceBase--}
```
public FontResourceBase()
```


### Disposed {#Disposed}
```
public final Event<EventHandler> Disposed
```


Bu yazı tipi serbest bırakıldığında gerçekleşen olay


### getName() {#getName--}
```
public final String getName()
```


Bu yazı tipi kaynağının adını döndürür. Genellikle dosya adı içermez
uzantı ve teorik olarak dosya adından farklı olabilir.


**Returns:**
java.lang.String
### getFilenameWithExtension() {#getFilenameWithExtension--}
```
public final String getFilenameWithExtension()
```


Bu yazı tipi kaynağının doğru dosya adını döndürür, adı içeren
ve uzantı. Teorik olarak isimden farklı olabilir.


**Returns:**
java.lang.String
### getByteContent() {#getByteContent--}
```
public final InputStream getByteContent()
```


Bu yazı tipinin içeriğini bayt akışı olarak döndürür.


**Returns:**
java.io.InputStream -
### getTextContent() {#getTextContent--}
```
public final String getTextContent()
```


Bu yazı tipinin içeriğini base64 kodlu dize olarak döndürür. Bu değer
ilk çağrıdan sonra önbelleğe alındı.


**Returns:**
java.lang.String -
### save(String fullPathToFile) {#save-java.lang.String-}
```
public final void save(String fullPathToFile)
```


Bu yazı tipini belirtilen dosyaya kaydeder


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | fullPathToFile | java.lang.String | Oluşturulacak veya yeniden yazılacak dosyanın tam yolu |
|

### equals(IHtmlResource other) {#equals-com.groupdocs.editor.htmlcss.resources.IHtmlResource-}
```
public final boolean equals(IHtmlResource other)
```


Bu örneği belirtilen HTML kaynağıyla referans eşitliğine göre kontrol eder


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | other | [IHtmlResource](../../com.groupdocs.editor.htmlcss.resources/ihtmlresource) | IHtmlResource arayüzünün diğer türevi |
|

**Returns:**
boolean - Eşitse true, eşit değilse false.

### equals(FontResourceBase other) {#equals-com.groupdocs.editor.htmlcss.resources.fonts.FontResourceBase-}
```
public final boolean equals(FontResourceBase other)
```


Bu örneği belirtilen yazı tipi kaynağıyla referans eşitliğine göre kontrol eder


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | other | [FontResourceBase](../../com.groupdocs.editor.htmlcss.resources.fonts/fontresourcebase) | FontResourceBase soyut sınıfının diğer türevi |
|

**Returns:**
boolean - Eşitse true, eşit değilse false.

### dispose() {#dispose--}
```
public final void dispose()
```


Bu yazı tipi kaynağını serbest bırakır, içeriğini serbest bırakır ve çoğunu
metot ve özellikleri çalışmaz hâle getirir


### isDisposed() {#isDisposed--}
```
public final boolean isDisposed()
```


Bu yazı tipinin serbest bırakılıp bırakılmadığını belirler


**Returns:**
boolean -
### getType() {#getType--}
```
public abstract FontType getType()
```


Uygulama türü, belirli bir tipin türü hakkında bilgi döndürmelidir
yazı tipi kaynağını belirli FontType tipinin bir örneği olarak, ki
tüm tip-özel bilgileri kapsar


**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype)
