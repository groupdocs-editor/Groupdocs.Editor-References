---
title: "BmpImage"
second_title: "GroupDocs.Editor для .NET справочник API"
description: "Создаёт новый экземпляр BmpImage из содержимого, представленного в виде строки, закодированной в base64, и с указанным именем"
type: docs
weight: 10
url: /ru/net/groupdocs.editor.htmlcss.resources.images.raster/bmpimage/bmpimage/
---
## BmpImage(string, string) {#constructor_1}

Создаёт новый экземпляр BmpImage из содержимого, представленного в виде строки, закодированной в base64, и с указанным именем

```csharp
public BmpImage(string name, string contentInBase64)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| name | String | Имя BMP‑изображения. Не может быть null, пустым или состоящим только из пробелов. |
| contentInBase64 | String | Содержимое в виде строки, закодированной в base64. Не может быть null, пустым или состоящим только из пробелов. Если это не BMP‑содержимое, будет выброшено исключение. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentException |  |
| [InvalidImageFormatException](../../../groupdocs.editor.htmlcss.exceptions/invalidimageformatexception) |  |

### См. также

* class [BmpImage](../../bmpimage)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Images.Raster](../../../groupdocs.editor.htmlcss.resources.images.raster)
* assembly [GroupDocs.Editor](../../../)

---

## BmpImage(string, Stream) {#constructor}

Создаёт новый экземпляр BmpImage из содержимого, представленного в виде потока байтов, и с указанным именем

```csharp
public BmpImage(string name, Stream binaryContent)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| name | String | Имя BMP‑изображения. Не может быть null, пустым или состоящим только из пробелов. |
| binaryContent | Stream | Содержимое в виде байтового потока. Чтение начинается с исходной позиции. Не может быть null. Должен быть доступен для чтения и перемещения. Если этот экземпляр будет освобождён, этот поток также будет освобождён. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentException |  |
| [InvalidImageFormatException](../../../groupdocs.editor.htmlcss.exceptions/invalidimageformatexception) |  |

### См. также

* class [BmpImage](../../bmpimage)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Images.Raster](../../../groupdocs.editor.htmlcss.resources.images.raster)
* assembly [GroupDocs.Editor](../../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.editor.dll -->
