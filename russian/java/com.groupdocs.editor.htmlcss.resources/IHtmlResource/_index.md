---
title: "IHtmlResource"
second_title: "GroupDocs.Editor for Java API Справка"
description: "Представляет один экземпляр неизвестного HTML‑ресурса: растрового или векторного изображения, таблицы стилей, шрифта, текстового ресурса, CSS, XML и т.д."
type: docs
weight: 12
url: /ru/java/com.groupdocs.editor.htmlcss.resources/ihtmlresource/
---
**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.resources.IAuxDisposable](../../com.groupdocs.editor.htmlcss.resources/iauxdisposable)
```
public interface IHtmlResource extends IAuxDisposable
```

Представляет один экземпляр неизвестного HTML‑ресурса (растрового или векторного изображения,
таблицы стилей, шрифт, текстовый ресурс (CSS, XML) и т.п.)

## Методы

| Метод | Описание |
| --- | --- |
|  | [getName()](#getName--) | Имя HTML‑ресурса |
|
|  | [getFilenameWithExtension()](#getFilenameWithExtension--) | Корректное имя файла указанного ресурса с соответствующим расширением |
расширение
|
|  | [getType()](#getType--) | Тип HTML‑ресурса |
|
|  | [getByteContent()](#getByteContent--) | Содержимое HTML‑ресурса в виде потока байтов |
|
|  | [getTextContent()](#getTextContent--) | Содержимое HTML‑ресурса в виде строки текста, закодированной в base64 |
для бинарных ресурсов или простой текст для текстовых ресурсов
|
|  | [save(String fullPathToFile)](#save-java.lang.String-) | Сохраняет текущий ресурс в указанный файл |
|
### getName() {#getName--}
```
public abstract String getName()
```


Имя HTML‑ресурса


**Returns:**
java.lang.String -
### getFilenameWithExtension() {#getFilenameWithExtension--}
```
public abstract String getFilenameWithExtension()
```


Корректное имя файла указанного ресурса с соответствующим расширением
расширение


**Returns:**
java.lang.String -
### getType() {#getType--}
```
public abstract IResourceType getType()
```


Тип HTML‑ресурса


**Returns:**
[IResourceType](../../com.groupdocs.editor.htmlcss.resources/iresourcetype) - 
### getByteContent() {#getByteContent--}
```
public abstract InputStream getByteContent()
```


Содержимое HTML‑ресурса в виде потока байтов


**Returns:**
java.io.InputStream
### getTextContent() {#getTextContent--}
```
public abstract String getTextContent()
```


Содержимое HTML‑ресурса в виде строки текста, закодированной в base64
для бинарных ресурсов или простой текст для текстовых ресурсов


**Returns:**
java.lang.String
### save(String fullPathToFile) {#save-java.lang.String-}
```
public abstract void save(String fullPathToFile)
```


Сохраняет текущий ресурс в указанный файл


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | fullPathToFile | java.lang.String | Полный путь к файлу, который будет создан или перезаписан содержимым текущего ресурса |
|

