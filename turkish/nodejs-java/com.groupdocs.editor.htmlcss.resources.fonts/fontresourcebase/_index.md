---
title: "FontResourceBase"
second_title: "GroupDocs.Editor Node.js için Java API Referansı"
description: "HTML belgesi için tüm özellikleriyle bir kaynak olarak desteklenen herhangi bir font tipinin temel sınıfı"
type: docs
weight: 11
url: /tr/nodejs-java/com.groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.resources.IHtmlResource](../../com.groupdocs.editor.htmlcss.resources/ihtmlresource)
```
public abstract class FontResourceBase implements IHtmlResource
```

HTML belgesi için bir kaynak olarak desteklenen herhangi bir font tipinin temel sınıfı
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
|  | [getFilenameWithExtension()](#getFilenameWithExtension--) | Bu yazı tipi kaynağının doğru dosya adını döndürür; adından oluşur |
ve uzantı.
|
|  | [getByteContent()](#getByteContent--) | Bu yazı tipinin içeriğini bayt akışı olarak döndürür |
|
|  | [getTextContent()](#getTextContent--) | Bu yazı tipinin içeriğini base64 kodlu dize olarak döndürür. |
|
|  | [save(String fullPathToFile)](#save-java.lang.String-) | Bu yazı tipini belirtilen dosyaya kaydeder |
|
|  | [equals(IHtmlResource other)](#equals-com.groupdocs.editor.htmlcss.resources.IHtmlResource-) | Bu örneği belirtilen HTML kaynağıyla referans eşitliği açısından kontrol eder |
|
|  | [equals(FontResourceBase other)](#equals-com.groupdocs.editor.htmlcss.resources.fonts.FontResourceBase-) | Bu örneği belirtilen yazı tipi kaynağıyla referans eşitliği açısından kontrol eder |
|
|  | [dispose()](#dispose--) | Bu yazı tipi kaynağını serbest bırakır, içeriğini serbest bırakarak çoğunu |
metod ve özelliklerini çalışmaz hâle getirir
|
|  | [isDisposed()](#isDisposed--) | Bu yazı tipinin serbest bırakılıp bırakılmadığını belirler |
|
|  | [getType()](#getType--) | Uygulayan tür, belirli bir tür hakkında bilgi döndürmelidir |
yazı tipi kaynağını belirli FontType türünün bir örneği olarak, ki
tüm türe özgü bilgileri kapsar
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


Bu yazı tipi kaynağının doğru dosya adını döndürür; adından oluşur
ve uzantı. Teorik olarak adından farklı olabilir.


**Returns:**
java.lang.String
### getByteContent() {#getByteContent--}
```
public final InputStream getByteContent()
```


Bu yazı tipinin içeriğini bayt akışı olarak döndürür


**Returns:**
java.io.InputStream -
### getTextContent() {#getTextContent--}
```
public final String getTextContent()
```


Bu yazı tipinin içeriğini base64 kodlu dize olarak döndürür. Bu değer
ilk çağrıdan sonra önbelleğe alınır.


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


Bu örneği belirtilen HTML kaynağıyla referans eşitliği açısından kontrol eder


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | other | [IHtmlResource](../../com.groupdocs.editor.htmlcss.resources/ihtmlresource) | IHtmlResource arayüzünün diğer türevi |
|

**Returns:**
boolean - Eşitse True, eşit değilse false

### equals(FontResourceBase other) {#equals-com.groupdocs.editor.htmlcss.resources.fonts.FontResourceBase-}
```
public final boolean equals(FontResourceBase other)
```


Bu örneği belirtilen yazı tipi kaynağıyla referans eşitliği açısından kontrol eder


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | other | [FontResourceBase](../../com.groupdocs.editor.htmlcss.resources.fonts/fontresourcebase) | FontResourceBase soyut sınıfının diğer türevi |
|

**Returns:**
boolean - Eşitse True, eşit değilse false

### dispose() {#dispose--}
```
public final void dispose()
```


Bu yazı tipi kaynağını serbest bırakır, içeriğini serbest bırakarak çoğunu
metod ve özelliklerini çalışmaz hâle getirir


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


Uygulayan tür, belirli bir tür hakkında bilgi döndürmelidir
yazı tipi kaynağını belirli FontType türünün bir örneği olarak, ki
tüm türe özgü bilgileri kapsar


**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype)
