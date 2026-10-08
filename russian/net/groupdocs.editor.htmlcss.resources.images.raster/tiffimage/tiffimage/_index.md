---
title: "TiffImage"
second_title: "GroupDocs.Editor для .NET справочник API"
description: "Создаёт новый экземпляр TiffImage из содержимого, представленного в виде base64encoded строки, и с указанным именем."
type: docs
weight: 10
url: /ru/net/groupdocs.editor.htmlcss.resources.images.raster/tiffimage/tiffimage/
---
## TiffImage(string, string) {#constructor_1}

Создаёт новый экземпляр TiffImage из содержимого, представленного в виде строки, закодированной в base64, и с указанным именем

```csharp
public TiffImage(string name, string contentInBase64)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| name | String | Имя TIFF‑изображения. Не может быть null, пустым или состоять только из пробелов. |
| contentInBase64 | String | Содержимое в виде base64‑закодированной строки. Не может быть null, пустым или состоять только из пробелов. Если это не содержимое TIFF, будет выброшено исключение. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentException |  |
| [InvalidImageFormatException](../../../groupdocs.editor.htmlcss.exceptions/invalidimageformatexception) |  |

### См. также

* class [TiffImage](../../tiffimage)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Images.Raster](../../../groupdocs.editor.htmlcss.resources.images.raster)
* assembly [GroupDocs.Editor](../../../)

---

## TiffImage(string, Stream) {#constructor}

Создаёт новый экземпляр GifImage из содержимого, представленного в виде байтового потока, и с указанным именем

```csharp
public TiffImage(string name, Stream binaryContent)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| name | String | Имя GIF‑изображения. Не может быть null, пустым или состоять только из пробелов. |
| binaryContent | Stream | Содержимое в виде байтового потока. Чтение начинается с исходной позиции. Не может быть null. Должен быть доступен для чтения и перемещения. Если этот экземпляр будет освобождён, этот поток также будет освобождён. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentException |  |
| [InvalidImageFormatException](../../../groupdocs.editor.htmlcss.exceptions/invalidimageformatexception) |  |

### См. также

* class [TiffImage](../../tiffimage)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Images.Raster](../../../groupdocs.editor.htmlcss.resources.images.raster)
* assembly [GroupDocs.Editor](../../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.editor.dll -->
