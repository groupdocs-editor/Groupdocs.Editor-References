---
title: "Mp3Audio"
second_title: "GroupDocs.Editor для .NET справочник API"
description: "Создает новый класс Mp3Audio из MP3‑содержимого, представленного в виде потока байтов, и с указанным именем."
type: docs
weight: 10
url: /ru/net/groupdocs.editor.htmlcss.resources.audio/mp3audio/mp3audio/
---
## Mp3Audio constructor

Создаёт новый объект класса Mp3Audio из MP3‑контента, представленного в виде потока байтов, и с указанным именем

```csharp
public Mp3Audio(string name, Stream binaryContent)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| name | String | Имя MP3‑содержимого. Не может быть null, пустым или состоять из пробелов. |
| binaryContent | Stream | Содержимое в виде байтового потока. Чтение начинается с исходной позиции. Не может быть null. Должен быть доступен для чтения и перемещения. Если этот экземпляр будет освобождён, этот поток также будет освобождён. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentException |  |

### См. также

* class [Mp3Audio](../../mp3audio)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Audio](../../../groupdocs.editor.htmlcss.resources.audio)
* assembly [GroupDocs.Editor](../../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.editor.dll -->
