---
title: "GetFirstDefined"
second_title: "GroupDocs.Editor для .NET справочник API"
description: "Возвращает первый тип шрифта из указанного набора, который не имеет значения Undefined, иначе возвращает тип шрифта Undefined, если все элементы имеют значение Undefined"
type: docs
weight: 80
url: /ru/net/groupdocs.editor.htmlcss.resources.fonts/fonttype/getfirstdefined/
---
## FontType.GetFirstDefined method

Возвращает первый тип шрифта из указанного набора, который не имеет значения "Undefined", или тип шрифта "Undefined" в противном случае (когда все элементы имеют значение "Undefined")

```csharp
public static FontType GetFirstDefined(params FontType[] fonts)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| шрифты | FontType[] | Одно или несколько значений FontType, NULL или пустая коллекция не допускаются |

### Возвращаемое значение

Первое значение FontType из указанной коллекции, которое не является Undefined, или Undefined, если все элементы являются Undefined

### См. также

* struct [FontType](../../fonttype)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Fonts](../../../groupdocs.editor.htmlcss.resources.fonts)
* assembly [GroupDocs.Editor](../../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.editor.dll -->
