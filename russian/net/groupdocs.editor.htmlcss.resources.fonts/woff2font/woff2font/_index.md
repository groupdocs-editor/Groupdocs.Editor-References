---
title: "Woff2Font"
second_title: "GroupDocs.Editor для .NET справочник API"
description: "Создаёт новый класс Woff2Font из содержимого, представленного в виде строки, закодированной base64, и с указанным именем"
type: docs
weight: 10
url: /ru/net/groupdocs.editor.htmlcss.resources.fonts/woff2font/woff2font/
---
## Woff2Font(string, string) {#constructor_1}

Создаёт новый класс Woff2Font из содержимого, представленного в виде строки, закодированной base64, и с указанным именем

```csharp
public Woff2Font(string name, string contentInBase64)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| name | String | Имя шрифта WOFF2. Не может быть null, пустым или состоять только из пробелов. |
| contentInBase64 | String | Содержимое в виде строки, закодированной base64. Не может быть null, пустым или состоять только из пробелов. Если это не содержимое WOFF2, будет выброшено исключение. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentException |  |
| [InvalidImageFormatException](../../../groupdocs.editor.htmlcss.exceptions/invalidimageformatexception) |  |

### См. также

* class [Woff2Font](../../woff2font)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Fonts](../../../groupdocs.editor.htmlcss.resources.fonts)
* assembly [GroupDocs.Editor](../../../)

---

## Woff2Font(string, Stream) {#constructor}

Создаёт новый класс Woff2Font из содержимого, представленного в виде потока байтов, и с указанным именем

```csharp
public Woff2Font(string name, Stream binaryContent)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| name | String | Имя шрифта WOFF2. Не может быть null, пустым или состоять только из пробелов. |
| binaryContent | Stream | Содержимое в виде потока байтов. Чтение начинается с исходной позиции. Не может быть null. Должен быть читаемым и перемещаемым. Если этот экземпляр будет освобождён, этот поток также будет освобождён. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentException |  |
| [InvalidImageFormatException](../../../groupdocs.editor.htmlcss.exceptions/invalidimageformatexception) |  |

### См. также

* class [Woff2Font](../../woff2font)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Fonts](../../../groupdocs.editor.htmlcss.resources.fonts)
* assembly [GroupDocs.Editor](../../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.editor.dll -->
