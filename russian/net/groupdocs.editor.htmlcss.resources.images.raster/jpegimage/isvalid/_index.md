---
title: "IsValid"
second_title: "GroupDocs.Editor для .NET справочник API"
description: "Проверяет, является ли указанный поток допустимым JPEG‑изображением"
type: docs
weight: 30
url: /ru/net/groupdocs.editor.htmlcss.resources.images.raster/jpegimage/isvalid/
---
## IsValid(Stream) {#isvalid}

Проверяет, является ли указанный поток допустимым JPEG‑изображением

```csharp
public static bool IsValid(Stream binaryContent)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| binaryContent | Stream | Поток байтов, который, предположительно, содержит JPEG‑изображение. |

### Возвращаемое значение

True, если указанный поток содержит корректное JPEG‑изображение, иначе false.

### См. также

* class [JpegImage](../../jpegimage)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Images.Raster](../../../groupdocs.editor.htmlcss.resources.images.raster)
* assembly [GroupDocs.Editor](../../../)

---

## IsValid(string) {#isvalid_1}

Проверяет, является ли указанная строка в формате base64 допустимым JPEG‑изображением

```csharp
public static bool IsValid(string contentInBase64)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| contentInBase64 | String | Содержимое предполагаемого JPEG‑изображения в виде строки, закодированной в base64 |

### Возвращаемое значение

True, если указанная строка содержит действительное JPEG‑изображение, иначе false

### См. также

* class [JpegImage](../../jpegimage)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Images.Raster](../../../groupdocs.editor.htmlcss.resources.images.raster)
* assembly [GroupDocs.Editor](../../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.editor.dll -->
