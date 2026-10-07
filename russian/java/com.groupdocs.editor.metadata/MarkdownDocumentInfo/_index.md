---
title: "MarkdownDocumentInfo"
second_title: "GroupDocs.Editor for Java API Справка"
description: "Представляет метаданные одного документа Markdown"
type: docs
weight: 13
url: /ru/java/com.groupdocs.editor.metadata/markdowndocumentinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.metadata.IDocumentInfo](../../com.groupdocs.editor.metadata/idocumentinfo)
```
public class MarkdownDocumentInfo implements IDocumentInfo
```

Представляет метаданные одного документа Markdown

## Методы

| Метод | Описание |
| --- | --- |
|  | [getFormat()](#getFormat--) | Возвращает формат этого Markdown документа — всегда |
[TextualFormats.Md](../../com.groupdocs.editor.formats/textualformats#Md)
|
|  | [getPageCount()](#getPageCount--) | Возвращает количество страниц. |
|
|  | [getSize()](#getSize--) | Возвращает размер в байтах этого Markdown‑документа |
|
|  | [isEncrypted()](#isEncrypted--) | Поскольку Markdown‑документы не могут быть зашифрованы паролем, это |
свойство всегда возвращает 'false'
|
|  | [equals(MarkdownDocumentInfo other)](#equals-com.groupdocs.editor.metadata.MarkdownDocumentInfo-) | Определяет, равен ли этот экземпляр указанному другому |
[MarkdownDocumentInfo](../../com.groupdocs.editor.metadata/markdowndocumentinfo) instance.
|
### getFormat() {#getFormat--}
```
public final DocumentFormatBase getFormat()
```


Возвращает формат этого Markdown документа — всегда
[TextualFormats.Md](../../com.groupdocs.editor.formats/textualformats#Md)


**Returns:**
[DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase)
### getPageCount() {#getPageCount--}
```
public final int getPageCount()
```


Возвращает количество страниц. Обычно у Markdown‑документов нет фиксированных страниц
и, следовательно, количество страниц, поэтому это число рассчитывается из стандартного размера страницы
установлен на A4 в портретной ориентации.


**Returns:**
int
### getSize() {#getSize--}
```
public final long getSize()
```


Возвращает размер в байтах этого Markdown‑документа


**Returns:**
long
### isEncrypted() {#isEncrypted--}
```
public final boolean isEncrypted()
```


Поскольку Markdown‑документы не могут быть зашифрованы паролем, это
свойство всегда возвращает 'false'


**Returns:**
boolean
### equals(MarkdownDocumentInfo other) {#equals-com.groupdocs.editor.metadata.MarkdownDocumentInfo-}
```
public final boolean equals(MarkdownDocumentInfo other)
```


Определяет, равен ли этот экземпляр указанному другому
[MarkdownDocumentInfo](../../com.groupdocs.editor.metadata/markdowndocumentinfo) instance.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | other | [MarkdownDocumentInfo](../../com.groupdocs.editor.metadata/markdowndocumentinfo) | Другой экземпляр [MarkdownDocumentInfo](../../com.groupdocs.editor.metadata/markdowndocumentinfo), который следует проверить на равенство с этим |
|

**Returns:**
boolean — True, если равны, false, если не равны

