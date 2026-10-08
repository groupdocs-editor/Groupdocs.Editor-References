---
title: "TryParse"
second_title: "GroupDocs.Editor для .NET справочник API"
description: "Пытается распознать указанное ключевое слово как корректное значение ключевого слова для fontstyle и вернуть его при успехе или NULL при неудаче."
type: docs
weight: 80
url: /ru/net/groupdocs.editor.htmlcss.css.properties/fontstyle/tryparse/
---
## FontStyle.TryParse method

Пытается распознать указанное ключевое слово как корректное значение ключевого слова 'font-style' и возвращает его при успехе или NULL при неудаче.

```csharp
public static bool TryParse(string keyword, out FontStyle result)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| keyword | String | Ключевое слово для разбора |
| result | FontStyle& | Результат, если разбор был успешным, иначе [`Normal`](../normal) |

### Возвращаемое значение

true, если разбор был успешным, иначе false

### См. также

* struct [FontStyle](../../fontstyle)
* namespace [GroupDocs.Editor.HtmlCss.Css.Properties](../../../groupdocs.editor.htmlcss.css.properties)
* assembly [GroupDocs.Editor](../../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.editor.dll -->
