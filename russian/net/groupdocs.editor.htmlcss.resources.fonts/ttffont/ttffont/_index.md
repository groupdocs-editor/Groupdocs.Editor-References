---
title: "TtfFont"
second_title: "GroupDocs.Editor для .NET справочник API"
description: "Создаёт новый класс TtfFont из содержимого, представленного в виде строки, закодированной в base64, и с указанным именем"
type: docs
weight: 10
url: /ru/net/groupdocs.editor.htmlcss.resources.fonts/ttffont/ttffont/
---
## TtfFont(string, string) {#constructor_1}

Создаёт новый класс TtfFont из содержимого, представленного в виде строки, закодированной base64, и с указанным именем

```csharp
public TtfFont(string name, string contentInBase64)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| name | String | Имя шрифта TTF. Не может быть null, пустым или содержать только пробелы. |
| contentInBase64 | String | Содержимое в виде строки, закодированной в base64. Не может быть null, пустым или содержать только пробелы. Если это не содержимое TTF, будет выброшено исключение. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentException |  |
| [InvalidImageFormatException](../../../groupdocs.editor.htmlcss.exceptions/invalidimageformatexception) |  |

### См. также

* class [TtfFont](../../ttffont)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Fonts](../../../groupdocs.editor.htmlcss.resources.fonts)
* assembly [GroupDocs.Editor](../../../)

---

## TtfFont(string, Stream) {#constructor}

Создаёт новый класс TtfFont из содержимого, представленного в виде байтового потока, и с указанным именем

```csharp
public TtfFont(string name, Stream binaryContent)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| name | String | Имя шрифта TTF. Не может быть null, пустым или содержать только пробелы. |
| binaryContent | Stream | Содержимое в виде байтового потока. Чтение начинается с исходной позиции. Не может быть null. Должен быть доступен для чтения и перемещения. Если этот экземпляр будет освобождён, этот поток также будет освобождён. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentException |  |
| [InvalidFontFormatException](../../../groupdocs.editor.htmlcss.exceptions/invalidfontformatexception) | Выбрасывается, когда указанное бинарное содержимое нельзя корректно интерпретировать как действительный шрифт TTF |

### См. также

* class [TtfFont](../../ttffont)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Fonts](../../../groupdocs.editor.htmlcss.resources.fonts)
* assembly [GroupDocs.Editor](../../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.editor.dll -->
