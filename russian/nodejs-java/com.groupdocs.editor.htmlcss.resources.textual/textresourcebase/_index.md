---
title: "TextResourceBase"
second_title: "GroupDocs.Editor для Node.js через Java API Reference"
description: "Базовый класс для любого поддерживаемого текстового ресурса с текстовым содержимым и кодировкой"
type: docs
weight: 11
url: /ru/nodejs-java/com.groupdocs.editor.htmlcss.resources.textual/textresourcebase/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.resources.IHtmlResource](../../com.groupdocs.editor.htmlcss.resources/ihtmlresource)
```
public abstract class TextResourceBase implements IHtmlResource
```

Базовый класс для любого поддерживаемого текстового ресурса с текстовым содержимым и кодировкой

## Конструкторы

| Конструктор | Описание |
| --- | --- |
|  | [TextResourceBase(String name, String textualContent, Charset originalEncoding)](#TextResourceBase-java.lang.String-java.lang.String-java.nio.charset.Charset-) | Создаёт новый текстовый ресурс из указанного текстового содержимого с кодировкой |
|
|  | [TextResourceBase(String name, InputStream binaryContent, Charset originalEncoding)](#TextResourceBase-java.lang.String-java.io.InputStream-java.nio.charset.Charset-) | Создает новый текстовый ресурс из указанного потока байтов и кодировки |
|
## Поля

| Поле | Описание |
| --- | --- |
| [Disposed](#Disposed) |  |
## Методы

| Метод | Описание |
| --- | --- |
|  | [getName()](#getName--) | Возвращает имя этого текстового ресурса без расширения файла |
|
|  | [getFilenameWithExtension()](#getFilenameWithExtension--) | Возвращает правильное имя файла этого текстового ресурса, которое состоит из имени |
и расширения
|
|  | [getEncoding()](#getEncoding--) | Возвращает кодировку этого текстового ресурса. |
|
|  | [getByteContent()](#getByteContent--) | Возвращает содержимое этого текстового ресурса в виде потока байтов с оригинальной |
кодировкой
|
|  | [getTextContent()](#getTextContent--) | Возвращает содержимое этого текстового ресурса в виде стандартной строки |
|
|  | [save(String fullPathToFile)](#save-java.lang.String-) | Сохраняет этот текстовый ресурс в указанный файл |
|
|  | [equals(IHtmlResource other)](#equals-com.groupdocs.editor.htmlcss.resources.IHtmlResource-) | Проверяет этот экземпляр на равенство с указанным. |
|
|  | [dispose()](#dispose--) | Уничтожает этот текстовый ресурс, удаляя его содержимое и делая большинство |
методов и свойств нерабочими.
|
|  | [isDisposed()](#isDisposed--) | Определяет, уничтожен ли этот текстовый ресурс или нет |
|
|  | [getType()](#getType--) | В реализующем типе следует возвращать информацию о типе текста |
resource
|
### TextResourceBase(String name, String textualContent, Charset originalEncoding) {#TextResourceBase-java.lang.String-java.lang.String-java.nio.charset.Charset-}
```
public TextResourceBase(String name, String textualContent, Charset originalEncoding)
```


Создаёт новый текстовый ресурс из указанного текстового содержимого с кодировкой


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | name | java.lang.String | Обязательное имя ресурса, которое служит его уникальным идентификатором. Обычно это имя файла. |
|
|  | textualContent | java.lang.String | Текстовое содержимое ресурса, не может быть NULL или пустым |
|
|  | originalEncoding | java.nio.charset.Charset | Исходная кодировка ресурса, не может быть NULL или пустой |
|

### TextResourceBase(String name, InputStream binaryContent, Charset originalEncoding) {#TextResourceBase-java.lang.String-java.io.InputStream-java.nio.charset.Charset-}
```
public TextResourceBase(String name, InputStream binaryContent, Charset originalEncoding)
```


Создает новый текстовый ресурс из указанного потока байтов и кодировки


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | name | java.lang.String | Обязательное имя ресурса, которое служит его уникальным идентификатором. Обычно это имя файла. |
|
|  | binaryContent | java.io.InputStream | Бинарное содержимое ресурса в виде потока байтов. Не может быть NULL, уничтожено, должно быть читаемым и перемещаемым. |
|
|  | originalEncoding | java.nio.charset.Charset | Исходная кодировка ресурса, не может быть NULL или пустой |
|

### Disposed {#Disposed}
```
public final Event<EventHandler> Disposed
```


### getName() {#getName--}
```
public final String getName()
```


Возвращает имя этого текстового ресурса без расширения файла


**Returns:**
java.lang.String
### getFilenameWithExtension() {#getFilenameWithExtension--}
```
public final String getFilenameWithExtension()
```


Возвращает правильное имя файла этого текстового ресурса, которое состоит из имени
и расширения


**Returns:**
java.lang.String
### getEncoding() {#getEncoding--}
```
public final Charset getEncoding()
```


Возвращает кодировку этого текстового ресурса. Обычно возвращает UTF-8.


**Returns:**
java.nio.charset.Charset -
### getByteContent() {#getByteContent--}
```
public final InputStream getByteContent()
```


Возвращает содержимое этого текстового ресурса в виде потока байтов с оригинальной
кодировкой


**Returns:**
java.io.InputStream -
### getTextContent() {#getTextContent--}
```
public final String getTextContent()
```


Возвращает содержимое этого текстового ресурса в виде стандартной строки


**Returns:**
java.lang.String -
### save(String fullPathToFile) {#save-java.lang.String-}
```
public final void save(String fullPathToFile)
```


Сохраняет этот текстовый ресурс в указанный файл


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | fullPathToFile | java.lang.String | Полный путь к файлу, который будет создан или перезаписан, если уже существует |
|

### equals(IHtmlResource other) {#equals-com.groupdocs.editor.htmlcss.resources.IHtmlResource-}
```
public final boolean equals(IHtmlResource other)
```


Проверяет этот экземпляр на равенство с указанным.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | other | [IHtmlResource](../../com.groupdocs.editor.htmlcss.resources/ihtmlresource) | Другой HTML‑ресурс неизвестного типа, который, вероятно, является наследником TextResourceBase |
|

**Returns:**
boolean — Возвращает true, если равны, или false, если не равны

### dispose() {#dispose--}
```
public final void dispose()
```


Уничтожает этот текстовый ресурс, удаляя его содержимое и делая большинство
методы и свойства не работают. Допускает множественные вызовы.


### isDisposed() {#isDisposed--}
```
public final boolean isDisposed()
```


Определяет, уничтожен ли этот текстовый ресурс или нет


**Returns:**
boolean —
### getType() {#getType--}
```
public abstract TextType getType()
```


В реализующем типе следует возвращать информацию о типе текста
resource


**Returns:**
[TextType](../../com.groupdocs.editor.htmlcss.resources.textual/texttype)
