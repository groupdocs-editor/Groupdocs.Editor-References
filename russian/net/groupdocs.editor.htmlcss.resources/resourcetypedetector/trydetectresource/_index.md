---
title: "TryDetectResource"
second_title: "GroupDocs.Editor для .NET справочник API"
description: "Пытается проанализировать входной поток и создает один из поддерживаемых HTML‑ресурсов, учитывая указанный предполагаемый тип, если он не null."
type: docs
weight: 20
url: /ru/net/groupdocs.editor.htmlcss.resources/resourcetypedetector/trydetectresource/
---
## ResourceTypeDetector.TryDetectResource method

Пытается проанализировать входной поток и создает один из поддерживаемых HTML‑ресурсов, учитывая указанный предполагаемый тип, если он не равен null

```csharp
public static IHtmlResource TryDetectResource(Stream inputResourceStream, string name, 
    IResourceType assumptiveFormat)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputResourceStream | Stream | Входной поток, который, предположительно, содержит HTML‑ресурс. Если он недействителен, будет выброшено исключение. |
| name | String | Имя ресурса, которое будет использовано для созданного и возвращаемого ресурса при успехе. Не может быть NULL, пустым или состоящим только из пробелов. |
| assumptiveFormat | IResourceType | Предполагаемый формат входного HTML‑ресурса, полезный для достижения наилучшей производительности. Если полностью неизвестен, используйте значение NULL. Может быть неверным, что лишь ухудшит производительность. |

### Возвращаемое значение

Экземпляр, реализующий интерфейс 'IHtmlResource' и представляющий один из поддерживаемых HTML‑ресурсов при успехе, либо NULL при неудаче.

### См. также

* interface [IHtmlResource](../../ihtmlresource)
* interface [IResourceType](../../iresourcetype)
* class [ResourceTypeDetector](../../resourcetypedetector)
* namespace [GroupDocs.Editor.HtmlCss.Resources](../../../groupdocs.editor.htmlcss.resources)
* assembly [GroupDocs.Editor](../../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.editor.dll -->
