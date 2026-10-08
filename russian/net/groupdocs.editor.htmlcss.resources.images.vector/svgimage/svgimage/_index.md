---
title: "SvgImage"
second_title: "GroupDocs.Editor для .NET справочник API"
description: "Создаёт новый экземпляр SvgImage из содержимого, представленного обычной строкой, и с указанным именем"
type: docs
weight: 10
url: /ru/net/groupdocs.editor.htmlcss.resources.images.vector/svgimage/svgimage/
---
## SvgImage(string, string) {#constructor_1}

Создаёт новый экземпляр SvgImage из содержимого, представленного в виде обычной строки, и с указанным именем

```csharp
public SvgImage(string name, string content)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| name | String | Имя SVG‑изображения. Не может быть null, пустым или состоять только из пробелов. |
| содержимое | String | Содержимое в виде обычной строки, которое содержит корректное XML‑совместимое содержимое SVG‑изображения. Не может быть null, пустым или состоять только из пробелов. Если это не SVG‑содержимое, будет выброшено исключение. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentException | Некоторые из параметров недействительны |
| [InvalidImageFormatException](../../../groupdocs.editor.htmlcss.exceptions/invalidimageformatexception) | Аргумент *content* содержит недопустимое SVG‑содержимое |

### См. также

* class [SvgImage](../../svgimage)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Images.Vector](../../../groupdocs.editor.htmlcss.resources.images.vector)
* assembly [GroupDocs.Editor](../../../)

---

## SvgImage(string, Stream) {#constructor}

Создаёт новый экземпляр SvgImage из содержимого, представленного в виде байтового потока, и с указанным именем

```csharp
public SvgImage(string name, Stream binaryContent)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| name | String | Имя SVG‑изображения. Не может быть null, пустым или состоять только из пробелов. |
| binaryContent | Stream | Содержимое в виде байтового потока. Чтение начинается с исходной позиции. Не может быть null. Должен быть доступен для чтения и перемещения. Если этот экземпляр будет освобождён, этот поток также будет освобождён. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentException |  |
| [InvalidImageFormatException](../../../groupdocs.editor.htmlcss.exceptions/invalidimageformatexception) |  |

### См. также

* class [SvgImage](../../svgimage)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Images.Vector](../../../groupdocs.editor.htmlcss.resources.images.vector)
* assembly [GroupDocs.Editor](../../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.editor.dll -->
