---
title: "FontResourceBase"
second_title: "GroupDocs.Editor for Java API Справка"
description: "Базовый класс для любого поддерживаемого типа шрифта как ресурса HTML‑документа со всеми его свойствами"
type: docs
weight: 11
url: /ru/java/com.groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.resources.IHtmlResource](../../com.groupdocs.editor.htmlcss.resources/ihtmlresource)
```
public abstract class FontResourceBase implements IHtmlResource
```

Базовый класс для любого поддерживаемого типа шрифта как ресурса HTML‑документа
со всеми его свойствами

## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [FontResourceBase()](#FontResourceBase--) |  |
## Поля

| Поле | Описание |
| --- | --- |
|  | [Disposed](#Disposed) | Событие, которое происходит, когда этот шрифт освобождается |
|
## Методы

| Метод | Описание |
| --- | --- |
|  | [getName()](#getName--) | Возвращает имя этого ресурса шрифта. |
|
|  | [getFilenameWithExtension()](#getFilenameWithExtension--) | Возвращает корректное имя файла этого ресурса шрифта, которое состоит из имени |
и расширения.
|
|  | [getByteContent()](#getByteContent--) | Возвращает содержимое этого шрифта в виде байтового потока |
|
|  | [getTextContent()](#getTextContent--) | Возвращает содержимое этого шрифта в виде строки, закодированной base64. |
|
|  | [save(String fullPathToFile)](#save-java.lang.String-) | Сохраняет этот шрифт в указанный файл |
|
|  | [equals(IHtmlResource other)](#equals-com.groupdocs.editor.htmlcss.resources.IHtmlResource-) | Проверяет этот экземпляр с указанным HTML‑ресурсом на равенство ссылок |
|
|  | [equals(FontResourceBase other)](#equals-com.groupdocs.editor.htmlcss.resources.fonts.FontResourceBase-) | Проверяет этот экземпляр с указанным ресурсом шрифта на равенство ссылок |
|
|  | [dispose()](#dispose--) | Освобождает этот ресурс шрифта, освобождая его содержимое и делая большинство |
методы и свойства нерабочими
|
|  | [isDisposed()](#isDisposed--) | Определяет, освобожден ли этот шрифт, или нет |
|
|  | [getType()](#getType--) | В реализующем типе следует вернуть информацию о типе конкретного |
ресурса шрифта как экземпляра конкретного типа FontType, который
инкапсулирует всю типо-специфическую информацию
|
### FontResourceBase() {#FontResourceBase--}
```
public FontResourceBase()
```


### Disposed {#Disposed}
```
public final Event<EventHandler> Disposed
```


Событие, которое происходит, когда этот шрифт освобождается


### getName() {#getName--}
```
public final String getName()
```


Возвращает имя этого ресурса шрифта. Обычно не содержит имя файла
расширение и теоретически может отличаться от имени файла.


**Returns:**
java.lang.String
### getFilenameWithExtension() {#getFilenameWithExtension--}
```
public final String getFilenameWithExtension()
```


Возвращает корректное имя файла этого ресурса шрифта, которое состоит из имени
и расширения. Теоретически может отличаться от имени.


**Returns:**
java.lang.String
### getByteContent() {#getByteContent--}
```
public final InputStream getByteContent()
```


Возвращает содержимое этого шрифта в виде байтового потока


**Returns:**
java.io.InputStream -
### getTextContent() {#getTextContent--}
```
public final String getTextContent()
```


Возвращает содержимое этого шрифта в виде строки, закодированной base64. Это значение
кешируется после первого вызова.


**Returns:**
java.lang.String -
### save(String fullPathToFile) {#save-java.lang.String-}
```
public final void save(String fullPathToFile)
```


Сохраняет этот шрифт в указанный файл


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | fullPathToFile | java.lang.String | Полный путь к файлу, который будет создан или перезаписан. |
|

### equals(IHtmlResource other) {#equals-com.groupdocs.editor.htmlcss.resources.IHtmlResource-}
```
public final boolean equals(IHtmlResource other)
```


Проверяет этот экземпляр с указанным HTML‑ресурсом на равенство ссылок


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | other | [IHtmlResource](../../com.groupdocs.editor.htmlcss.resources/ihtmlresource) | Другой наследник интерфейса IHtmlResource |
|

**Returns:**
boolean — True, если равны, false, если не равны

### equals(FontResourceBase other) {#equals-com.groupdocs.editor.htmlcss.resources.fonts.FontResourceBase-}
```
public final boolean equals(FontResourceBase other)
```


Проверяет этот экземпляр с указанным ресурсом шрифта на равенство ссылок


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | other | [FontResourceBase](../../com.groupdocs.editor.htmlcss.resources.fonts/fontresourcebase) | Другой наследник абстрактного класса FontResourceBase |
|

**Returns:**
boolean — True, если равны, false, если не равны

### dispose() {#dispose--}
```
public final void dispose()
```


Освобождает этот ресурс шрифта, освобождая его содержимое и делая большинство
методы и свойства нерабочими


### isDisposed() {#isDisposed--}
```
public final boolean isDisposed()
```


Определяет, освобожден ли этот шрифт, или нет


**Returns:**
boolean -
### getType() {#getType--}
```
public abstract FontType getType()
```


В реализующем типе следует вернуть информацию о типе конкретного
ресурса шрифта как экземпляра конкретного типа FontType, который
инкапсулирует всю типо-специфическую информацию


**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype)
