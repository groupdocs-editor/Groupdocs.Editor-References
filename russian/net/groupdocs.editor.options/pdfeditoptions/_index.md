---
title: "PdfEditOptions"
second_title: "GroupDocs.Editor для .NET справочник API"
description: "Позволяет задавать пользовательские параметры для редактирования PDF‑документов"
type: docs
weight: 1050
url: /ru/net/groupdocs.editor.options/pdfeditoptions/
---
## PdfEditOptions class

Позволяет задавать пользовательские параметры для редактирования PDF‑документов

```csharp
public sealed class PdfEditOptions : FixedLayoutEditOptionsBase
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [PdfEditOptions](pdfeditoptions#constructor)() | Создаёт и возвращает новый экземпляр класса PdfEditOptions, в котором все параметры установлены в значения по умолчанию. |
| [PdfEditOptions](pdfeditoptions#constructor_1)(bool) | Создаёт и возвращает новый экземпляр класса PdfEditOptions с указанной пагинацией, а все остальные параметры — со значениями по умолчанию. |

## Свойства

| Имя | Описание |
| --- | --- |
| [EnablePagination](../../groupdocs.editor.options/fixedlayouteditoptionsbase/enablepagination) { get; set; } | Позволяет включить (true) или отключить (false) разбиение на страницы в результирующем HTML‑документе. По умолчанию отключено (false). |
| [Pages](../../groupdocs.editor.options/fixedlayouteditoptionsbase/pages) { get; set; } | Позволяет задать диапазон страниц для обработки. По умолчанию обрабатываются все страницы фиксированного макета. |
| [SkipImages](../../groupdocs.editor.options/fixedlayouteditoptionsbase/skipimages) { get; set; } | Получает или задаёт флаг, указывающий, следует ли пропускать изображения при преобразовании входного документа фиксированного макета в результирующий HTML. По умолчанию false — изображения сохраняются. |

### См. также

* class [FixedLayoutEditOptionsBase](../fixedlayouteditoptionsbase)
* namespace [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.editor.dll -->
