---
title: "EotFont"
second_title: "GroupDocs.Editor для .NET справочник API"
description: "Создаёт новый класс EotFont из содержимого, представленного в виде строки, закодированной в base64, и с указанным именем"
type: docs
weight: 10
url: /ru/net/groupdocs.editor.htmlcss.resources.fonts/eotfont/eotfont/
---
## EotFont(string, string) {#constructor_1}

Создаёт новый класс EotFont из содержимого, представленного в виде строки, закодированной base64, и с указанным именем

```csharp
public EotFont(string eotName, string eotContentInBase64)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| eotName | String | Имя шрифта EOT. Не может быть null, пустым или содержать только пробелы. |
| eotContentInBase64 | String | Содержимое в виде строки, закодированной в base64. Не может быть null, пустым или содержать только пробелы. Если это не содержимое EOT, будет выброшено исключение. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentException |  |
| [InvalidImageFormatException](../../../groupdocs.editor.htmlcss.exceptions/invalidimageformatexception) |  |

### См. также

* class [EotFont](../../eotfont)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Fonts](../../../groupdocs.editor.htmlcss.resources.fonts)
* assembly [GroupDocs.Editor](../../../)

---

## EotFont(string, Stream) {#constructor}

Создаёт новый класс EotFont из содержимого, представленного в виде байтового потока, и с указанным именем

```csharp
public EotFont(string eotName, Stream eotBinaryContent)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| eotName | String | Имя шрифта EOT. Не может быть null, пустым или содержать только пробелы. |
| eotBinaryContent | Stream | Содержимое в виде байтового потока. Чтение начинается с исходной позиции. Не может быть null. Должен быть доступен для чтения и перемещения. Если этот экземпляр будет освобождён, этот поток также будет освобождён. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentException |  |
| [InvalidImageFormatException](../../../groupdocs.editor.htmlcss.exceptions/invalidimageformatexception) |  |

### См. также

* class [EotFont](../../eotfont)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Fonts](../../../groupdocs.editor.htmlcss.resources.fonts)
* assembly [GroupDocs.Editor](../../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.editor.dll -->
