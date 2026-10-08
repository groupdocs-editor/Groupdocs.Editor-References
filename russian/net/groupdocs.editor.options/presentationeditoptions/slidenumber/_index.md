---
title: "SlideNumber"
second_title: "GroupDocs.Editor для .NET справочник API"
description: "Позволяет указать номера слайдов, которые должны быть открыты для редактирования."
type: docs
weight: 30
url: /ru/net/groupdocs.editor.options/presentationeditoptions/slidenumber/
---
## PresentationEditOptions.SlideNumber property

Позволяет указать номера слайдов, которые следует открыть для редактирования.

```csharp
public int SlideNumber { get; set; }
```

### Замечания

Номер слайда — это нулевой индекс слайда, позволяющий указать и выбрать один конкретный слайд из презентации для редактирования. Если значение меньше 0, будет выбран первый слайд (то же, что SlideNumber = 0). Если значение больше количества всех слайдов в презентации, будет выбран последний слайд. Если входная презентация содержит только один слайд, эта опция будет игнорироваться, и единственный слайд будет отредактирован. При попытке открыть для редактирования скрытый слайд, когда опция [`ShowHiddenSlides`](../showhiddenslides) установлена в 'false', будет выброшено исключение.

### См. также

* class [PresentationEditOptions](../../presentationeditoptions)
* namespace [GroupDocs.Editor.Options](../../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.editor.dll -->
