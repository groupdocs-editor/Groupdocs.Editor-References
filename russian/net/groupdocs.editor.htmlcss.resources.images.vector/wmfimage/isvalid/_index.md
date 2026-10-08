---
title: "IsValid"
second_title: "GroupDocs.Editor для .NET справочник API"
description: "Проверяет, является ли указанный поток действительным WMF‑изображением"
type: docs
weight: 90
url: /ru/net/groupdocs.editor.htmlcss.resources.images.vector/wmfimage/isvalid/
---
## IsValid(Stream) {#isvalid}

Проверяет, является ли указанный поток действительным WMF‑изображением

```csharp
public static bool IsValid(Stream binaryContent)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| binaryContent | Stream | Входной поток байтов. Не может быть NULL, должен поддерживать чтение и перемещение. |

### Возвращаемое значение

True, если указанный поток содержит корректное WMF‑изображение, иначе false

### См. также

* class [WmfImage](../../wmfimage)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Images.Vector](../../../groupdocs.editor.htmlcss.resources.images.vector)
* assembly [GroupDocs.Editor](../../../)

---

## IsValid(string) {#isvalid_1}

Проверяет, является ли указанная строка, закодированная в base64, действительным WMF‑изображением

```csharp
public static bool IsValid(string contentInBase64)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| contentInBase64 | String | Входная строка, в которой содержимое изображения WMF хранится в кодировке base64. Не может быть NULL или пустой. |

### Возвращаемое значение

True, если указанная строка содержит корректное изображение WMF, иначе false

### См. также

* class [WmfImage](../../wmfimage)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Images.Vector](../../../groupdocs.editor.htmlcss.resources.images.vector)
* assembly [GroupDocs.Editor](../../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.editor.dll -->
