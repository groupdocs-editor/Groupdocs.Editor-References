---
title: "IsValid"
second_title: "GroupDocs.Editor для .NET справочник API"
description: "Проверяет, является ли указанный поток допустимым шрифтом WOFF"
type: docs
weight: 40
url: /ru/net/groupdocs.editor.htmlcss.resources.fonts/wofffont/isvalid/
---
## IsValid(Stream) {#isvalid}

Проверяет, является ли указанный поток допустимым шрифтом WOFF

```csharp
public static bool IsValid(Stream binaryContent)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| binaryContent | Stream | Поток байтов, который предположительно содержит ресурс WOFF |

### Возвращаемое значение

True, если указанный поток содержит действительный шрифт WOFF, иначе false

### См. также

* class [WoffFont](../../wofffont)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Fonts](../../../groupdocs.editor.htmlcss.resources.fonts)
* assembly [GroupDocs.Editor](../../../)

---

## IsValid(string) {#isvalid_1}

Проверяет, является ли указанная строка в формате base64 допустимым шрифтом WOFF

```csharp
public static bool IsValid(string contentInBase64)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| contentInBase64 | String | Содержимое предполагаемого шрифта WOFF в виде строки, закодированной в base64 |

### Возвращаемое значение

True, если указанная строка содержит действительный шрифт WOFF, иначе false

### См. также

* class [WoffFont](../../wofffont)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Fonts](../../../groupdocs.editor.htmlcss.resources.fonts)
* assembly [GroupDocs.Editor](../../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.editor.dll -->
