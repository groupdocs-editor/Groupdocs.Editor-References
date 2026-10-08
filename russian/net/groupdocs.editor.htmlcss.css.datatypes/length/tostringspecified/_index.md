---
title: "ToStringSpecified"
second_title: "GroupDocs.Editor для .NET справочник API"
description: "Возвращает строковое представление этой длины в указанном типе единицы. Числовое значение будет преобразовано в соответствии с изменением типа единицы."
type: docs
weight: 260
url: /ru/net/groupdocs.editor.htmlcss.css.datatypes/length/tostringspecified/
---
## Length.ToStringSpecified method

Возвращает строковое представление этой длины в указанном типе единицы. Числовое значение будет преобразовано в соответствии с изменением типа единицы.

```csharp
public string ToStringSpecified(Unit unit)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| единица | Единица | Указанная единица, в которую этот экземпляр должен быть преобразован перед сериализацией в строку. Должна быть действительной. Не может быть без единицы. |

### Возвращаемое значение

Строковое представление

### Исключения

| исключение | условие |
| --- | --- |
| InvalidEnumArgumentException | Значение не определено |
| ArgumentOutOfRangeException | Значение без единицы запрещено |

### См. также

* enum [Unit](../../length.unit)
* struct [Length](../../length)
* namespace [GroupDocs.Editor.HtmlCss.Css.DataTypes](../../../groupdocs.editor.htmlcss.css.datatypes)
* assembly [GroupDocs.Editor](../../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.editor.dll -->
