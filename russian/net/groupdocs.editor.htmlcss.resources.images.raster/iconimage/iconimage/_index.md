---
title: "IconImage"
second_title: "GroupDocs.Editor для .NET справочник API"
description: "Создаёт новый экземпляр IconImage из содержимого, представленного в виде строки base64 и с указанным именем"
type: docs
weight: 10
url: /ru/net/groupdocs.editor.htmlcss.resources.images.raster/iconimage/iconimage/
---
## IconImage(string, string) {#constructor_1}

Создаёт новый экземпляр IconImage из содержимого, представленного в виде строки, закодированной в base64, и с указанным именем

```csharp
public IconImage(string name, string contentInBase64)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| name | String | Имя ICON‑изображения. Не может быть null, пустым или содержать только пробелы. |
| contentInBase64 | String | Содержимое в виде строки base64. Не может быть null, пустым или содержать только пробелы. Если это не содержимое ICON, будет выброшено исключение. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentException |  |
| [InvalidImageFormatException](../../../groupdocs.editor.htmlcss.exceptions/invalidimageformatexception) |  |

### См. также

* class [IconImage](../../iconimage)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Images.Raster](../../../groupdocs.editor.htmlcss.resources.images.raster)
* assembly [GroupDocs.Editor](../../../)

---

## IconImage(string, Stream) {#constructor}

Создаёт новый экземпляр IconImage из содержимого, представленного в виде потока байтов, и с указанным именем

```csharp
public IconImage(string name, Stream binaryContent)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| name | String | Имя ICON‑изображения. Не может быть null, пустым или содержать только пробелы. |
| binaryContent | Stream | Содержимое в виде байтового потока. Чтение начинается с исходной позиции. Не может быть null. Должен быть доступен для чтения и перемещения. Если этот экземпляр будет освобождён, этот поток также будет освобождён. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentException |  |
| [InvalidImageFormatException](../../../groupdocs.editor.htmlcss.exceptions/invalidimageformatexception) |  |

### См. также

* class [IconImage](../../iconimage)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Images.Raster](../../../groupdocs.editor.htmlcss.resources.images.raster)
* assembly [GroupDocs.Editor](../../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.editor.dll -->
