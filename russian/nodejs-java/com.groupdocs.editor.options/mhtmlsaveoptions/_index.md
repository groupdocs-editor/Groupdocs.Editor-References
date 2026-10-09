---
title: "MhtmlSaveOptions"
second_title: "GroupDocs.Editor для Node.js через Java API Reference"
description: "Позволяет указать пользовательские параметры для создания и сохранения MHTML MIME-инкапсуляции агрегированных HTML‑документов"
type: docs
weight: 26
url: /ru/nodejs-java/com.groupdocs.editor.options/mhtmlsaveoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.ISaveOptions](../../com.groupdocs.editor.options/isaveoptions)
```
public final class MhtmlSaveOptions implements ISaveOptions
```

Позволяет задавать пользовательские параметры для создания и сохранения документов MHTML (MIME-инкапсуляция агрегированных HTML‑документов).

## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [MhtmlSaveOptions()](#MhtmlSaveOptions--) |  |
## Методы

| Метод | Описание |
| --- | --- |
|  | [getExportCidUrls()](#getExportCidUrls--) | Указывает, использовать ли CID (Content-ID) URL для ссылки на ресурсы (изображения, шрифты, CSS), включённые в MHTML‑документы. |
|
|  | [setExportCidUrls(boolean value)](#setExportCidUrls-boolean-) | Указывает, использовать ли CID (Content-ID) URL для ссылки на ресурсы (изображения, шрифты, CSS), включённые в MHTML‑документы. |
|
|  | [getExportDocumentProperties()](#getExportDocumentProperties--) | Указывает, экспортировать ли встроенные и пользовательские свойства документа в MHTML. |
|
|  | [setExportDocumentProperties(boolean value)](#setExportDocumentProperties-boolean-) | Указывает, экспортировать ли встроенные и пользовательские свойства документа в MHTML. |
|
|  | [getExportLanguageInformation()](#getExportLanguageInformation--) | Указывает, экспортируется ли информация о языке в MHTML. |
|
|  | [setExportLanguageInformation(boolean value)](#setExportLanguageInformation-boolean-) | Указывает, экспортируется ли информация о языке в MHTML. |
|
### MhtmlSaveOptions() {#MhtmlSaveOptions--}
```
public MhtmlSaveOptions()
```


### getExportCidUrls() {#getExportCidUrls--}
```
public final boolean getExportCidUrls()
```


Указывает, использовать ли CID (Content-ID) URL для ссылки на ресурсы (изображения, шрифты, CSS), включённые в MHTML‑документы. Значение по умолчанию —
false
.

<br />

*** ** * ** ***


По умолчанию ресурсы в MHTML‑документах ссылаются по имени файла (например, "image.png"), которое сопоставляется с заголовками "Content-Location" MIME‑частей. Эта опция включает альтернативный метод, при котором ссылки на файлы ресурсов записываются как CID (Content-ID) URL (например, "cid:image.png") и сопоставляются с заголовками "Content-ID".


Теоретически не должно быть разницы между двумя методами ссылки, и любой из них должен работать во всех браузерах и почтовых клиентах. На практике однако некоторые клиенты не могут получить ресурсы по имени файла. Если ваш браузер или почтовый клиент отказывается загружать ресурсы, включённые в документ MTHML (не отображаются изображения или не загружаются стили CSS), попробуйте экспортировать документ с CID‑URL.

<br />



**Returns:**
boolean
### setExportCidUrls(boolean value) {#setExportCidUrls-boolean-}
```
public final void setExportCidUrls(boolean value)
```


Указывает, использовать ли CID (Content-ID) URL для ссылки на ресурсы (изображения, шрифты, CSS), включённые в MHTML‑документы. Значение по умолчанию —
false
.

<br />

*** ** * ** ***


По умолчанию ресурсы в MHTML‑документах ссылаются по имени файла (например, "image.png"), которое сопоставляется с заголовками "Content-Location" MIME‑частей. Эта опция включает альтернативный метод, при котором ссылки на файлы ресурсов записываются как CID (Content-ID) URL (например, "cid:image.png") и сопоставляются с заголовками "Content-ID".


Теоретически не должно быть разницы между двумя методами ссылки, и любой из них должен работать во всех браузерах и почтовых клиентах. На практике однако некоторые клиенты не могут получить ресурсы по имени файла. Если ваш браузер или почтовый клиент отказывается загружать ресурсы, включённые в документ MTHML (не отображаются изображения или не загружаются стили CSS), попробуйте экспортировать документ с CID‑URL.

<br />



**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

### getExportDocumentProperties() {#getExportDocumentProperties--}
```
public final boolean getExportDocumentProperties()
```


Указывает, экспортировать ли встроенные и пользовательские свойства документа в MHTML. Значение по умолчанию —
false
.


**Returns:**
boolean
### setExportDocumentProperties(boolean value) {#setExportDocumentProperties-boolean-}
```
public final void setExportDocumentProperties(boolean value)
```


Указывает, экспортировать ли встроенные и пользовательские свойства документа в MHTML. Значение по умолчанию —
false
.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

### getExportLanguageInformation() {#getExportLanguageInformation--}
```
public final boolean getExportLanguageInformation()
```


Указывает, экспортируется ли информация о языке в MHTML. Значение по умолчанию —
false
.

<br />

*** ** * ** ***

Когда это свойство установлено в  true , GroupDocs.Editor добавляет атрибут HTML  lang  к элементам документа, указывающим язык. Это может потребоваться для сохранения семантики, связанной с языком.

<br />



**Returns:**
boolean
### setExportLanguageInformation(boolean value) {#setExportLanguageInformation-boolean-}
```
public final void setExportLanguageInformation(boolean value)
```


Указывает, экспортируется ли информация о языке в MHTML. Значение по умолчанию —
false
.

<br />

*** ** * ** ***

Когда это свойство установлено в  true , GroupDocs.Editor добавляет атрибут HTML  lang  к элементам документа, указывающим язык. Это может потребоваться для сохранения семантики, связанной с языком.

<br />



**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

