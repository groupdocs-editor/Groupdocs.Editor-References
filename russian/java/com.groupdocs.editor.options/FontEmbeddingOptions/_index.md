---
title: "FontEmbeddingOptions"
second_title: "GroupDocs.Editor for Java API Справка"
description: "Параметры встраивания шрифтов определяют, какие ресурсы шрифтов должны быть встроены в выходной документ WordProcessing"
type: docs
weight: 17
url: /ru/java/com.groupdocs.editor.options/fontembeddingoptions/
---
**Inheritance:**
java.lang.Object
```
public final class FontEmbeddingOptions
```

Параметры встраивания шрифтов определяют, какие ресурсы шрифтов должны быть встроены в
выходной документ WordProcessing


*** ** * ** ***

Параметры встраивания шрифтов применяются при сохранении документа (из промежуточного EditableDocument в выходной формат WordProcessing), этот перечислимый тип включён как свойство в WordProcessingSaveOptions, откуда его следует использовать

<br />


## Поля

| Поле | Описание |
| --- | --- |
|  | [NotEmbed](#NotEmbed) | Не встраивать любые ресурсы шрифтов ни из EditableDocument, ни из |
системы.
|
|  | [EmbedAll](#EmbedAll) | Анализировать содержимое документа из входного EditableDocument, найти все используемые шрифты |
и встроить их в выходной документ WordProcessing.
|
|  | [EmbedWithoutSystem](#EmbedWithoutSystem) | Точно как [EmbedAll](../../com.groupdocs.editor.options/fontembeddingoptions#EmbedAll), но исключить эти шрифты, |
которые рассматриваются ОС как системные шрифты
|
## Методы

| Метод | Описание |
| --- | --- |
| [getFontEmbeddingOptions()](#getFontEmbeddingOptions--) |  |
### NotEmbed {#NotEmbed}
```
public static final int NotEmbed
```


Не встраивать любые ресурсы шрифтов ни из EditableDocument, ни из
система. Значение по умолчанию.


### EmbedAll {#EmbedAll}
```
public static final int EmbedAll
```


Анализировать содержимое документа из входного EditableDocument, найти все используемые шрифты
и внедрить их в выходной документ WordProcessing. Прежде всего
GroupDocs.Editor берёт шрифты из ресурсов шрифтов внутри EditableDocument.
Если их недостаточно или они отсутствуют, то GroupDocs.Editor берёт шрифты
из ОС.


*** ** * ** ***

Прежде всего GroupDocs.Editor анализирует содержимое EditableDocument и формирует список всех используемых шрифтов. Затем эти шрифты ищутся в ресурсах шрифтов EditableDocument. Если EditableDocument содержит некоторые ресурсы шрифтов, которые не задействованы в содержимом документа, такие ресурсы игнорируются. Если есть шрифты, используемые в содержимом документа, для которых нет соответствующих ресурсов шрифтов в EditableDocument, тогда GroupDocs.Editor пытается найти их в ОС. Эта опция похожа на параметр "Embed fonts in the file", при котором все подопции отключены в Microsoft Word 2007 и выше.

<br />



### EmbedWithoutSystem {#EmbedWithoutSystem}
```
public static final int EmbedWithoutSystem
```


Точно как [EmbedAll](../../com.groupdocs.editor.options/fontembeddingoptions#EmbedAll), но исключить эти шрифты,
которые рассматриваются ОС как системные шрифты


*** ** * ** ***

В MS Windows существует понятие системных шрифтов, которые являются самыми базовыми и используемыми шрифтами самой Windows. При использовании этой опции GroupDocs.Editor работает так же, как в случае [EmbedAll](../../com.groupdocs.editor.options/fontembeddingoptions#EmbedAll), но в конце проверяет набор полученных шрифтов и исключает те, которые рассматриваются ОС как системные шрифты. Эта опция похожа на параметры "Embed fonts in the file" + "Do not embed common system fonts" в Microsoft Word 2007 и выше.

<br />



### getFontEmbeddingOptions() {#getFontEmbeddingOptions--}
```
public static int[] getFontEmbeddingOptions()
```




**Returns:**
int[]
