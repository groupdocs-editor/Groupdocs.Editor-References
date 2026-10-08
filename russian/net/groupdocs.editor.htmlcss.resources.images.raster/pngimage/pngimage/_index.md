---
title: "PngImage"
second_title: "GroupDocs.Editor для .NET справочник API"
description: "Создаёт новый экземпляр PngImage из содержимого, представленного в виде base64encoded строки, и с указанным именем."
type: docs
weight: 10
url: /ru/net/groupdocs.editor.htmlcss.resources.images.raster/pngimage/pngimage/
---
## PngImage(string, string) {#constructor_1}

Создаёт новый экземпляр PngImage из содержимого, представленного в виде строки, закодированной в base64, и с указанным именем

```csharp
public PngImage(string name, string contentInBase64)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| name | String | Имя PNG‑изображения. Не может быть null, пустым или состоять только из пробелов. |
| contentInBase64 | String | Содержимое в виде base64‑закодированной строки. Не может быть null, пустым или состоять только из пробелов. Если это не содержимое PNG, будет выброшено исключение. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentException |  |
| [InvalidImageFormatException](../../../groupdocs.editor.htmlcss.exceptions/invalidimageformatexception) |  |

### См. также

* class [PngImage](../../pngimage)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Images.Raster](../../../groupdocs.editor.htmlcss.resources.images.raster)
* assembly [GroupDocs.Editor](../../../)

---

## PngImage(string, Stream) {#constructor}

Создаёт новый экземпляр PngImage из содержимого, представленного в виде байтового потока, и с указанным именем

```csharp
public PngImage(string name, Stream binaryContent)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| name | String | Имя PNG‑изображения. Не может быть null, пустым или состоять только из пробелов. |
| binaryContent | Stream | Содержимое в виде байтового потока. Чтение начинается с исходной позиции. Не может быть null. Должен быть доступен для чтения и перемещения. Если этот экземпляр будет освобождён, этот поток также будет освобождён. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentException |  |
| [InvalidImageFormatException](../../../groupdocs.editor.htmlcss.exceptions/invalidimageformatexception) |  |

### См. также

* class [PngImage](../../pngimage)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Images.Raster](../../../groupdocs.editor.htmlcss.resources.images.raster)
* assembly [GroupDocs.Editor](../../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.editor.dll -->
