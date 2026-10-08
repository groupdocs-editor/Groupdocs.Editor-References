---
title: "FromNumber"
second_title: "GroupDocs.Editor для .NET справочник API"
description: "Создаёт fontweight из указанного числа"
type: docs
weight: 50
url: /ru/net/groupdocs.editor.htmlcss.css.properties/fontweight/fromnumber/
---
## FontWeight.FromNumber method

Создаёт font-weight из указанного числа.

```csharp
public static FontWeight FromNumber(ushort number)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| число | UInt16 | Беззнаковое целое, должно находиться в диапазоне [1..1000] |

### Возвращаемое значение

Новый экземпляр FontWeight или исключение

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentOutOfRangeException | Указанное число выходит за пределы диапазона [1..1000] |

### См. также

* struct [FontWeight](../../fontweight)
* namespace [GroupDocs.Editor.HtmlCss.Css.Properties](../../../groupdocs.editor.htmlcss.css.properties)
* assembly [GroupDocs.Editor](../../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.editor.dll -->
