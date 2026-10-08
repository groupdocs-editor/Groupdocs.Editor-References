---
title: "Пароль"
second_title: "GroupDocs.Editor для .NET справочник API"
description: "Позволяет указать, изменить и получить пароль, который будет использоваться для открытия документа Presentation, если он зашифрован. Установите NULL или пустую строку, чтобы удалить пароль."
type: docs
weight: 20
url: /ru/net/groupdocs.editor.options/presentationloadoptions/password/
---
## PresentationLoadOptions.Password property

Позволяет указать, изменить и получить пароль, который будет использоваться для открытия документа Presentation, если он зашифрован. Установите NULL или пустую строку, чтобы удалить пароль.

```csharp
public string Password { get; set; }
```

### Замечания

По умолчанию это свойство имеет значение NULL — пароль не установлен. Если входной документ Presentation защищён паролем, пароль обязателен, и будет выброшено исключение, если пароль не указан или неверен. Если входной документ Presentation НЕ защищён паролем, но пароль установлен, он будет игнорироваться.

### См. также

* class [PresentationLoadOptions](../../presentationloadoptions)
* namespace [GroupDocs.Editor.Options](../../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.editor.dll -->
