---
title: "XpsSaveOptions"
second_title: "GroupDocs.Editor для .NET справочник API"
description: "Позволяет задавать пользовательские параметры генерации и сохранения документов XPS XML Paper Specifications"
type: docs
weight: 1300
url: /ru/net/groupdocs.editor.options/xpssaveoptions/
---
## XpsSaveOptions class

Позволяет задавать пользовательские параметры для создания и сохранения документов XPS (XML Paper Specifications)

```csharp
public sealed class XpsSaveOptions : ISaveOptions
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [XpsSaveOptions](xpssaveoptions)() | Конструктор по умолчанию. |

## Свойства

| Имя | Описание |
| --- | --- |
| [OptimizeMemoryUsage](../../groupdocs.editor.options/xpssaveoptions/optimizememoryusage) { get; set; } | Включает механизмы оптимизации памяти при генерации документа из HTML, что снижает производительность в качестве цены за уменьшение использования памяти. Установка этой опции в true может значительно снизить потребление памяти при генерации больших документов за счёт более медленного времени сохранения. По умолчанию false (оптимизация памяти отключена ради лучшей производительности). |

### Замечания

Файл XPS представляет собой файлы разметки страниц, основанные на XML Paper Specifications, созданных Microsoft. Он был разработан как замена формата EMF и похож на формат PDF, но использует XML для описания разметки, внешнего вида и печатной информации документа.

### См. также

* interface [ISaveOptions](../isaveoptions)
* namespace [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.editor.dll -->
