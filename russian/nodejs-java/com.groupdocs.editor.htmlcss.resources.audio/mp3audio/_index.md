---
title: "Mp3Audio"
second_title: "GroupDocs.Editor для Node.js через Java API Reference"
description: "Представляет один аудио ресурс произвольного формата"
type: docs
weight: 11
url: /ru/nodejs-java/com.groupdocs.editor.htmlcss.resources.audio/mp3audio/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.resources.IHtmlResource](../../com.groupdocs.editor.htmlcss.resources/ihtmlresource)
```
public final class Mp3Audio implements IHtmlResource
```

Представляет один аудио ресурс произвольного формата

## Конструкторы

| Конструктор | Описание |
| --- | --- |
|  | [Mp3Audio(String name, System.IO.Stream binaryContent, boolean leaveOpen)](#Mp3Audio-java.lang.String-com.aspose.ms.System.IO.Stream-boolean-) | Создаёт новый класс Mp3Audio из MP3‑контента, представленного в виде байтового потока, с указанным именем |
|
## Методы

| Метод | Описание |
| --- | --- |
|  | [isValid(System.IO.Stream binaryContent)](#isValid-com.aspose.ms.System.IO.Stream-) | Проверяет, является ли указанный поток действительным MP3‑контентом |
|
|  | [getName()](#getName--) | Возвращает имя этого MP3‑контента. |
|
|  | [getFilenameWithExtension()](#getFilenameWithExtension--) | Возвращает корректное имя файла этого MP3‑контента, состоящее из имени и расширения. |
|
|  | [getType()](#getType--) | Возвращает AudioFormat.Mp3 (также удовлетворяет IHtmlResource.getFormat() посредством ковариантного возвращаемого значения) |
|
|  | [getByteContent()](#getByteContent--) | Возвращает содержимое этого шрифта в виде потока байтов |
|
|  | [getByteContentInternal()](#getByteContentInternal--) | Возвращает содержимое этого MP3 аудио ресурса в виде потока байтов с исходной позицией |
|
|  | [getTextContent()](#getTextContent--) | Возвращает содержимое этого MP3 ресурса в виде строки, закодированной в base64. |
|
|  | [save(String fullPathToFile)](#save-java.lang.String-) | Сохраняет этот MP3 ресурс в указанный файл |
|
|  | [equals(IHtmlResource other)](#equals-com.groupdocs.editor.htmlcss.resources.IHtmlResource-) | Проверяет данный экземпляр с указанным HTML ресурсом на равенство ссылок |
|
|  | [equals(Mp3Audio other)](#equals-com.groupdocs.editor.htmlcss.resources.audio.Mp3Audio-) | Проверяет данный экземпляр с указанным ресурсом шрифта на равенство ссылок |
|
|  | [dispose()](#dispose--) | Освобождает этот MP3 ресурс, освобождая его содержимое и делая большинство методов и свойств нерабочими |
|
|  | [isDisposed()](#isDisposed--) | Определяет, освобожден ли этот MP3 контент, или нет |
|
| [addDisposedListener(EventHandler value)](#addDisposedListener-com.groupdocs.editor.handler.EventHandler-) |  |
| [removeDisposedListener(EventHandler value)](#removeDisposedListener-com.groupdocs.editor.handler.EventHandler-) |  |
### Mp3Audio(String name, System.IO.Stream binaryContent, boolean leaveOpen) {#Mp3Audio-java.lang.String-com.aspose.ms.System.IO.Stream-boolean-}
```
public Mp3Audio(String name, System.IO.Stream binaryContent, boolean leaveOpen)
```


Создаёт новый класс Mp3Audio из MP3‑контента, представленного в виде байтового потока, с указанным именем


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | name | java.lang.String | Имя MP3 контента. Не может быть null, пустым или состоять только из пробелов. |
|
|  | binaryContent | com.aspose.ms.System.IO.Stream | Содержимое в виде потока байтов. Чтение начинается с исходной позиции. Не может быть null. Должен быть читаемым и поддерживать поиск. Если этот экземпляр будет освобождён, этот поток также будет освобождён. |
|
|  | leaveOpen | boolean | Определяет, следует ли освобождать указанный поток при освобождении экземпляра Mp3Audio |
|

### isValid(System.IO.Stream binaryContent) {#isValid-com.aspose.ms.System.IO.Stream-}
```
public static boolean isValid(System.IO.Stream binaryContent)
```


Проверяет, является ли указанный поток действительным MP3‑контентом


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | binaryContent | com.aspose.ms.System.IO.Stream | Поток байтов, который предположительно содержит MP3 контент |
|

**Returns:**
boolean - True, если указанный поток содержит корректный MP3 контент, иначе false

### getName() {#getName--}
```
public String getName()
```


Возвращает имя этого MP3 контента. Обычно не содержит расширения файла и теоретически может отличаться от имени файла.


**Returns:**
java.lang.String
### getFilenameWithExtension() {#getFilenameWithExtension--}
```
public String getFilenameWithExtension()
```


Возвращает корректное имя файла этого MP3 контента, которое состоит из имени и расширения. Теоретически может отличаться от имени.


**Returns:**
java.lang.String
### getType() {#getType--}
```
public AudioType getType()
```


Возвращает AudioFormat.Mp3 (также удовлетворяет IHtmlResource.getFormat() посредством ковариантного возвращаемого значения)


**Returns:**
[AudioType](../../com.groupdocs.editor.htmlcss.resources.audio/audiotype)
### getByteContent() {#getByteContent--}
```
public InputStream getByteContent()
```


Возвращает содержимое этого шрифта в виде потока байтов


**Returns:**
java.io.InputStream
### getByteContentInternal() {#getByteContentInternal--}
```
public System.IO.Stream getByteContentInternal()
```


Возвращает содержимое этого MP3 аудио ресурса в виде потока байтов с исходной позицией


**Returns:**
com.aspose.ms.System.IO.Stream
### getTextContent() {#getTextContent--}
```
public String getTextContent()
```


Возвращает содержимое этого MP3 ресурса в виде строки, закодированной в base64. Это значение кэшируется после первого вызова.


**Returns:**
java.lang.String
### save(String fullPathToFile) {#save-java.lang.String-}
```
public void save(String fullPathToFile)
```


Сохраняет этот MP3 ресурс в указанный файл


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | fullPathToFile | java.lang.String | Полный путь к файлу, который будет создан или перезаписан |
|

### equals(IHtmlResource other) {#equals-com.groupdocs.editor.htmlcss.resources.IHtmlResource-}
```
public boolean equals(IHtmlResource other)
```


Проверяет данный экземпляр с указанным HTML ресурсом на равенство ссылок


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | other | [IHtmlResource](../../com.groupdocs.editor.htmlcss.resources/ihtmlresource) | Другой наследник интерфейса IHtmlResource |
|

**Returns:**
boolean - True, если равны, false, если не равны

### equals(Mp3Audio other) {#equals-com.groupdocs.editor.htmlcss.resources.audio.Mp3Audio-}
```
public boolean equals(Mp3Audio other)
```


Проверяет данный экземпляр с указанным ресурсом шрифта на равенство ссылок


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | other | [Mp3Audio](../../com.groupdocs.editor.htmlcss.resources.audio/mp3audio) | Другой экземпляр класса Mp3Audio |
|

**Returns:**
boolean - True, если равны, false, если не равны

### dispose() {#dispose--}
```
public void dispose()
```


Освобождает этот MP3 ресурс, освобождая его содержимое и делая большинство методов и свойств нерабочими


### isDisposed() {#isDisposed--}
```
public boolean isDisposed()
```


Определяет, освобожден ли этот MP3 контент, или нет


**Returns:**
boolean
### addDisposedListener(EventHandler value) {#addDisposedListener-com.groupdocs.editor.handler.EventHandler-}
```
public void addDisposedListener(EventHandler value)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [EventHandler](../../com.groupdocs.editor.handler/eventhandler) |  |

### removeDisposedListener(EventHandler value) {#removeDisposedListener-com.groupdocs.editor.handler.EventHandler-}
```
public void removeDisposedListener(EventHandler value)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [EventHandler](../../com.groupdocs.editor.handler/eventhandler) |  |

