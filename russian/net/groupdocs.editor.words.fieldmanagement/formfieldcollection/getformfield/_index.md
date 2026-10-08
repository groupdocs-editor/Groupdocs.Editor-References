---
title: "GetFormField"
second_title: "GroupDocs.Editor для .NET справочник API"
description: "Получает поле формы с указанным именем и типом."
type: docs
weight: 40
url: /ru/net/groupdocs.editor.words.fieldmanagement/formfieldcollection/getformfield/
---
## FormFieldCollection.GetFormField&lt;T&gt; method

Получает поле формы с указанным именем и типом.

```csharp
public T GetFormField<T>(string name)
    where T : IFormField
```

| Параметр | Описание |
| --- | --- |
| T | Тип поля формы. |
| name | Имя поля формы. |

### Возвращаемое значение

Поле формы с указанным именем и типом, если найдено; в противном случае возвращается значение по умолчанию для данного типа.

### См. также

* interface [IFormField](../../iformfield)
* class [FormFieldCollection](../../formfieldcollection)
* namespace [GroupDocs.Editor.Words.FieldManagement](../../../groupdocs.editor.words.fieldmanagement)
* assembly [GroupDocs.Editor](../../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.editor.dll -->
