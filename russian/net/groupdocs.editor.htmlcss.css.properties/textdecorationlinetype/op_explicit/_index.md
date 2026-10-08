---
title: "op_Explicit"
second_title: "GroupDocs.Editor для .NET справочник API"
description: "Преобразует конкретный байт (8‑битный октет) в соответствующий TextDecorationLineTypegroupdocs.editor.htmlcss.css.properties/textdecorationlinetype, бросает исключение, если приведение недопустимо"
type: docs
weight: 180
url: /ru/net/groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/op_explicit/
---
## explicit operator {#op_explicit_1}

Преобразует конкретный байт (8‑битный октет) в соответствующий [`TextDecorationLineType`](../../textdecorationlinetype), бросает исключение, если приведение недопустимо

```csharp
public static explicit operator TextDecorationLineType(byte octet)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| октет | Байт | 8‑битный октет (битовое поле), где первые 5 битов равны нулю, а последние 3 указывают флаги |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentOutOfRangeException | Указанный *октет* имеет недопустимое значение |

### См. также

* struct [TextDecorationLineType](../../textdecorationlinetype)
* namespace [GroupDocs.Editor.HtmlCss.Css.Properties](../../../groupdocs.editor.htmlcss.css.properties)
* assembly [GroupDocs.Editor](../../../)

---

## explicit operator {#op_explicit}

Преобразует указанный экземпляр [`TextDecorationLineType`](../../textdecorationlinetype) в эквивалентный октет (8‑битное битовое поле)

```csharp
public static explicit operator byte(TextDecorationLineType input)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| input | TextDecorationLineType | Экземпляр [`TextDecorationLineType`](../../textdecorationlinetype) для приведения |

### См. также

* struct [TextDecorationLineType](../../textdecorationlinetype)
* namespace [GroupDocs.Editor.HtmlCss.Css.Properties](../../../groupdocs.editor.htmlcss.css.properties)
* assembly [GroupDocs.Editor](../../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.editor.dll -->
