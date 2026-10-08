---
title: "FixInvalidFormFieldNames"
second_title: "GroupDocs.Editor для .NET справочник API"
description: "Исправляет недействительные имена полей формы в документе, применяя указанные обновления или автоматически генерируя уникальные имена."
type: docs
weight: 20
url: /ru/net/groupdocs.editor/formfieldmanager/fixinvalidformfieldnames/
---
## FormFieldManager.FixInvalidFormFieldNames method

Исправляет недействительные имена полей формы в документе, применяя указанные обновления или автоматически генерируя уникальные имена.

```csharp
public void FixInvalidFormFieldNames(IEnumerable<InvalidFormField> updateInvalidFormFieldNames)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| updateInvalidFormFieldNames | IEnumerable`1 | Коллекция обновлений для недействительных имен полей формы. Каждое обновление содержит исходное имя поля формы и соответствующее новое имя. Если коллекция пуста, недействительные имена полей формы будут автоматически переименованы для обеспечения уникальности. |

### Замечания

Метод `FixInvalidFormFieldNames` разрешает конфликты имен или несоответствия в полях формы документа, применяя обновления, указанные в коллекции *updateInvalidFormFieldNames*, или автоматически генерируя уникальные имена, если коллекция пуста. Этот метод полезен, когда некоторые имена полей формы недействительны или конфликтуют с другими элементами документа и требуют исправления для обеспечения правильной работы. ; ;

### См. также

* class [InvalidFormField](../../../groupdocs.editor.words.fieldmanagement/invalidformfield)
* class [FormFieldManager](../../formfieldmanager)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.editor.dll -->
