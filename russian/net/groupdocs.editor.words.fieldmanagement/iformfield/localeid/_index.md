---
title: "LocaleId"
second_title: "GroupDocs.Editor для .NET справочник API"
description: "Получает или задает идентификатор локали поля формы, который представляет культуру или региональные настройки, связанные с полем формы."
type: docs
weight: 20
url: /ru/net/groupdocs.editor.words.fieldmanagement/iformfield/localeid/
---
## IFormField.LocaleId property

Получает или задает идентификатор локали поля формы, который представляет культуру или региональные настройки, связанные с полем формы.

```csharp
public int LocaleId { get; set; }
```

### Замечания

Свойство LocaleId указывает идентификатор локали (LCID), соответствующий определённой культуре или региону.

### Примеры

В следующем примере показано, как установить свойство LocaleId:

```csharp
Set the LocaleId to represent the English (United States) culture
field.LocaleId = new CultureInfo("en-US").LCID;
```

### См. также

* interface [IFormField](../../iformfield)
* namespace [GroupDocs.Editor.Words.FieldManagement](../../../groupdocs.editor.words.fieldmanagement)
* assembly [GroupDocs.Editor](../../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.editor.dll -->
