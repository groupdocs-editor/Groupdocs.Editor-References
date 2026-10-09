---
title: "MarkdownImageLoadingAction"
second_title: "GroupDocs.Editor для Node.js через Java API Reference"
description: "Определяет режим загрузки изображений при открытии файла для редактирования в формате Markdown."
type: docs
weight: 23
url: /ru/nodejs-java/com.groupdocs.editor.options/markdownimageloadingaction/
---
**Inheritance:**
java.lang.Object
```
public final class MarkdownImageLoadingAction
```

Определяет режим загрузки изображений при открытии файла для редактирования в формате Markdown.

## Поля

| Поле | Описание |
| --- | --- |
|  | [Default](#Default) | GroupDocs.Editor загрузит этот ресурс как обычно |
|
|  | [Skip](#Skip) | GroupDocs.Editor пропустит загрузку этого изображения |
|
|  | [UserProvided](#UserProvided) | GroupDocs.Editor будет использовать массив байтов, предоставленный пользователем в |
M:GroupDocs.Editor.Options.MarkdownImageLoadArgs.SetData(System.Byte[])
в качестве данных изображения
|
### Default {#Default}
```
public static final int Default
```


GroupDocs.Editor загрузит этот ресурс как обычно


### Skip {#Skip}
```
public static final int Skip
```


GroupDocs.Editor пропустит загрузку этого изображения


### UserProvided {#UserProvided}
```
public static final int UserProvided
```


GroupDocs.Editor будет использовать массив байтов, предоставленный пользователем в
M:GroupDocs.Editor.Options.MarkdownImageLoadArgs.SetData(System.Byte[])
в качестве данных изображения


