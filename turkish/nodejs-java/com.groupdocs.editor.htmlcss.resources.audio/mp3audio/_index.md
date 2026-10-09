---
title: "Mp3Audio"
second_title: "GroupDocs.Editor Node.js için Java API Referansı"
description: "İsteğe bağlı formatta bir ses kaynağını temsil eder."
type: docs
weight: 11
url: /tr/nodejs-java/com.groupdocs.editor.htmlcss.resources.audio/mp3audio/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.resources.IHtmlResource](../../com.groupdocs.editor.htmlcss.resources/ihtmlresource)
```
public final class Mp3Audio implements IHtmlResource
```

İsteğe bağlı formatta bir ses kaynağını temsil eder.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
|  | [Mp3Audio(String name, System.IO.Stream binaryContent, boolean leaveOpen)](#Mp3Audio-java.lang.String-com.aspose.ms.System.IO.Stream-boolean-) | Belirtilen adla, bayt akışı olarak temsil edilen MP3 içeriğinden yeni Mp3Audio sınıfı oluşturur |
|
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [isValid(System.IO.Stream binaryContent)](#isValid-com.aspose.ms.System.IO.Stream-) | Belirtilen akışın geçerli bir MP3 içeriği olup olmadığını denetler |
|
|  | [getName()](#getName--) | Bu MP3 içeriğinin adını döndürür. |
|
|  | [getFilenameWithExtension()](#getFilenameWithExtension--) | Bu MP3 içeriğinin ad ve uzantıdan oluşan doğru dosya adını döndürür. |
|
|  | [getType()](#getType--) | AudioFormat.Mp3 döndürür (aynı zamanda kovaryant dönüş üzerinden IHtmlResource.getFormat() metodunu da karşılar) |
|
|  | [getByteContent()](#getByteContent--) | Bu yazı tipinin içeriğini bayt akışı olarak döndürür |
|
|  | [getByteContentInternal()](#getByteContentInternal--) | Bu MP3 ses kaynağının içeriğini orijinal konumda bayt akışı olarak döndürür |
|
|  | [getTextContent()](#getTextContent--) | Bu MP3 kaynağının içeriğini base64 kodlu dize olarak döndürür. |
|
|  | [save(String fullPathToFile)](#save-java.lang.String-) | Bu MP3 kaynağını belirtilen dosyaya kaydeder |
|
|  | [equals(IHtmlResource other)](#equals-com.groupdocs.editor.htmlcss.resources.IHtmlResource-) | Bu örneği belirtilen HTML kaynağıyla referans eşitliği açısından kontrol eder |
|
|  | [equals(Mp3Audio other)](#equals-com.groupdocs.editor.htmlcss.resources.audio.Mp3Audio-) | Bu örneği belirtilen yazı tipi kaynağıyla referans eşitliği açısından kontrol eder |
|
|  | [dispose()](#dispose--) | Bu MP3 kaynağını ve içeriğini serbest bırakır, çoğu yöntem ve özelliği çalışmaz hâle getirir |
|
|  | [isDisposed()](#isDisposed--) | Bu MP3 içeriğinin serbest bırakılıp bırakılmadığını belirler |
|
| [addDisposedListener(EventHandler value)](#addDisposedListener-com.groupdocs.editor.handler.EventHandler-) |  |
| [removeDisposedListener(EventHandler value)](#removeDisposedListener-com.groupdocs.editor.handler.EventHandler-) |  |
### Mp3Audio(String name, System.IO.Stream binaryContent, boolean leaveOpen) {#Mp3Audio-java.lang.String-com.aspose.ms.System.IO.Stream-boolean-}
```
public Mp3Audio(String name, System.IO.Stream binaryContent, boolean leaveOpen)
```


Belirtilen adla, bayt akışı olarak temsil edilen MP3 içeriğinden yeni Mp3Audio sınıfı oluşturur


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | ad | java.lang.String | MP3 içeriğinin adı. Boş, null veya yalnızca boşluk olamaz. |
|
|  | binaryContent | com.aspose.ms.System.IO.Stream | İçerik bayt akışı olarak. Okuma orijinal konumdan başlar. Null olamaz. Okunabilir ve aranabilir olmalıdır. Bu örnek serbest bırakılırsa, bu akış da serbest bırakılacaktır. |
|
|  | leaveOpen | boolean | Mp3Audio örneği serbest bırakıldığında belirtilen akışın serbest bırakılıp bırakılmayacağını belirler |
|

### isValid(System.IO.Stream binaryContent) {#isValid-com.aspose.ms.System.IO.Stream-}
```
public static boolean isValid(System.IO.Stream binaryContent)
```


Belirtilen akışın geçerli bir MP3 içeriği olup olmadığını denetler


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | binaryContent | com.aspose.ms.System.IO.Stream | Muhtemelen MP3 içeriği içeren bayt akışı |
|

**Returns:**
boolean - Belirtilen akış geçerli MP3 içeriği içeriyorsa True, aksi takdirde false

### getName() {#getName--}
```
public String getName()
```


Bu MP3 içeriğinin adını döndürür. Genellikle dosya uzantısı içermez ve teorik olarak dosya adından farklı olabilir.


**Returns:**
java.lang.String
### getFilenameWithExtension() {#getFilenameWithExtension--}
```
public String getFilenameWithExtension()
```


Bu MP3 içeriğinin doğru dosya adını döndürür; ad ve uzantıdan oluşur. Teorik olarak adından farklı olabilir.


**Returns:**
java.lang.String
### getType() {#getType--}
```
public AudioType getType()
```


AudioFormat.Mp3 döndürür (aynı zamanda kovaryant dönüş üzerinden IHtmlResource.getFormat() metodunu da karşılar)


**Returns:**
[AudioType](../../com.groupdocs.editor.htmlcss.resources.audio/audiotype)
### getByteContent() {#getByteContent--}
```
public InputStream getByteContent()
```


Bu yazı tipinin içeriğini bayt akışı olarak döndürür


**Returns:**
java.io.InputStream
### getByteContentInternal() {#getByteContentInternal--}
```
public System.IO.Stream getByteContentInternal()
```


Bu MP3 ses kaynağının içeriğini orijinal konumda bayt akışı olarak döndürür


**Returns:**
com.aspose.ms.System.IO.Stream
### getTextContent() {#getTextContent--}
```
public String getTextContent()
```


Bu MP3 kaynağının içeriğini base64 kodlu dize olarak döndürür. Bu değer ilk çağrıdan sonra önbelleğe alınır.


**Returns:**
java.lang.String
### save(String fullPathToFile) {#save-java.lang.String-}
```
public void save(String fullPathToFile)
```


Bu MP3 kaynağını belirtilen dosyaya kaydeder


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | fullPathToFile | java.lang.String | Oluşturulacak veya yeniden yazılacak dosyanın tam yolu |
|

### equals(IHtmlResource other) {#equals-com.groupdocs.editor.htmlcss.resources.IHtmlResource-}
```
public boolean equals(IHtmlResource other)
```


Bu örneği belirtilen HTML kaynağıyla referans eşitliği açısından kontrol eder


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | other | [IHtmlResource](../../com.groupdocs.editor.htmlcss.resources/ihtmlresource) | IHtmlResource arayüzünün diğer türevi |
|

**Returns:**
boolean - Eşitse True, eşit değilse false

### equals(Mp3Audio other) {#equals-com.groupdocs.editor.htmlcss.resources.audio.Mp3Audio-}
```
public boolean equals(Mp3Audio other)
```


Bu örneği belirtilen yazı tipi kaynağıyla referans eşitliği açısından kontrol eder


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | other | [Mp3Audio](../../com.groupdocs.editor.htmlcss.resources.audio/mp3audio) | Mp3Audio sınıfının diğer örneği |
|

**Returns:**
boolean - Eşitse True, eşit değilse false

### dispose() {#dispose--}
```
public void dispose()
```


Bu MP3 kaynağını ve içeriğini serbest bırakır, çoğu yöntem ve özelliği çalışmaz hâle getirir


### isDisposed() {#isDisposed--}
```
public boolean isDisposed()
```


Bu MP3 içeriğinin serbest bırakılıp bırakılmadığını belirler


**Returns:**
boolean
### addDisposedListener(EventHandler value) {#addDisposedListener-com.groupdocs.editor.handler.EventHandler-}
```
public void addDisposedListener(EventHandler value)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [EventHandler](../../com.groupdocs.editor.handler/eventhandler) |  |

### removeDisposedListener(EventHandler value) {#removeDisposedListener-com.groupdocs.editor.handler.EventHandler-}
```
public void removeDisposedListener(EventHandler value)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [EventHandler](../../com.groupdocs.editor.handler/eventhandler) |  |

