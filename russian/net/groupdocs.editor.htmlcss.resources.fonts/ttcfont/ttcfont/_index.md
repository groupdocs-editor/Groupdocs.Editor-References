---
title: "TtcFont"
second_title: "GroupDocs.Editor для .NET справочник API"
description: "Создаёт новый класс TtcFont из содержимого, представленного в виде строки, закодированной в base64, и с указанным именем"
type: docs
weight: 10
url: /ru/net/groupdocs.editor.htmlcss.resources.fonts/ttcfont/ttcfont/
---
## TtcFont(string, string) {#constructor_1}

Создаёт новый класс TtcFont из содержимого, представленного в виде строки, закодированной в base64, и с указанным именем

```csharp
public TtcFont(string name, string contentInBase64)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| name | String | Имя шрифта TTC. Не может быть null, пустым или состоящим только из пробелов. |
| contentInBase64 | String | Содержимое в виде строки, закодированной в base64. Не может быть null, пустым или состоящим только из пробелов. Если это не TTC‑содержимое, будет выброшено исключение. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentException | Любая из входных строк является `null`, пустой или состоит только из пробельных символов |
| [InvalidImageFormatException](../../../groupdocs.editor.htmlcss.exceptions/invalidimageformatexception) | Содержимое аргумента *contentInBase64* не может быть распознано как действительный шрифт TTC |

### См. также

* class [TtcFont](../../ttcfont)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Fonts](../../../groupdocs.editor.htmlcss.resources.fonts)
* assembly [GroupDocs.Editor](../../../)

---

## TtcFont(string, Stream) {#constructor}

Создаёт новый класс TtcFont из содержимого, представленного в виде потока байтов, и с указанным именем

```csharp
public TtcFont(string name, Stream binaryContent)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| name | String | Имя шрифта TTC. Не может быть null, пустым или состоящим только из пробелов. |
| binaryContent | Stream | Содержимое в виде байтового потока. Чтение начинается с исходной позиции. Не может быть null. Должен быть доступен для чтения и перемещения. Если этот экземпляр будет освобождён, этот поток также будет освобождён. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentException | Аргумент *name* является `null`, пустым или состоит только из пробельных символов |
| [InvalidFontFormatException](../../../groupdocs.editor.htmlcss.exceptions/invalidfontformatexception) | Выбрасывается, когда указанное бинарное содержимое нельзя корректно интерпретировать как действительный шрифт TTF |

### См. также

* class [TtcFont](../../ttcfont)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Fonts](../../../groupdocs.editor.htmlcss.resources.fonts)
* assembly [GroupDocs.Editor](../../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.editor.dll -->
