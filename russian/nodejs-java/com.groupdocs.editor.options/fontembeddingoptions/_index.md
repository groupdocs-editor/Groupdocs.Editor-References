---
title: "FontEmbeddingOptions"
second_title: "GroupDocs.Editor для Node.js через Java API Reference"
description: "Параметры встраивания шрифтов определяют, какие ресурсы шрифтов должны быть встроены в выходной документ WordProcessing"
type: docs
weight: 17
url: /ru/nodejs-java/com.groupdocs.editor.options/fontembeddingoptions/
---
**Inheritance:**
java.lang.Object
```
public final class FontEmbeddingOptions
```

Параметры встраивания шрифтов определяют, какие ресурсы шрифтов должны быть встроены в
выходной документ WordProcessing


*** ** * ** ***

Параметры встраивания шрифтов применяются при сохранении документа (из промежуточного EditableDocument в выходной формат WordProcessing), это перечисление включено как свойство в WordProcessingSaveOptions, откуда его следует использовать

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
которые операционная система рассматривает как системные шрифты
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
и встроить их в выходной документ WordProcessing. Прежде всего
GroupDocs.Editor берёт шрифты из ресурсов шрифтов внутри EditableDocument.
Если они недостаточны или отсутствуют, то GroupDocs.Editor берёт шрифты
из ОС.


*** ** * ** ***

Во-первых, GroupDocs.Editor анализирует содержимое EditableDocument и формирует список всех использованных шрифтов. Затем эти шрифты ищутся в ресурсах шрифтов EditableDocument. Если EditableDocument содержит некоторые ресурсы шрифтов, которые не задействованы в содержимом документа, такие ресурсы игнорируются. Если есть шрифты, используемые в содержимом документа, для которых нет соответствующих ресурсов шрифтов в EditableDocument, то GroupDocs.Editor пытается найти их в ОС. Эта опция напоминает параметр "Embed fonts in the file" с отключёнными всеми подопциями в Microsoft Word 2007 и выше

<br />



### EmbedWithoutSystem {#EmbedWithoutSystem}
```
public static final int EmbedWithoutSystem
```


Точно как [EmbedAll](../../com.groupdocs.editor.options/fontembeddingoptions#EmbedAll), но исключить эти шрифты,
которые операционная система рассматривает как системные шрифты


*** ** * ** ***

MS Windows имеет концепцию системных шрифтов, которые являются самыми базовыми и используемыми шрифтами самой Windows. При использовании этой опции GroupDocs.Editor работает как в случае [EmbedAll](../../com.groupdocs.editor.options/fontembeddingoptions#EmbedAll), но в конце проверяет набор полученных шрифтов и исключает те, которые ОС рассматривает как системные шрифты. Эта опция напоминает параметры "Embed fonts in the file" + "Do not embed common system fonts" в Microsoft Word 2007 и выше

<br />



### getFontEmbeddingOptions() {#getFontEmbeddingOptions--}
```
public static int[] getFontEmbeddingOptions()
```




**Returns:**
int[]
