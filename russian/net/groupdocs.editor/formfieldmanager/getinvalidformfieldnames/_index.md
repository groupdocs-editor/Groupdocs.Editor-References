---
title: "GetInvalidFormFieldNames"
second_title: "GroupDocs.Editor для .NET справочник API"
description: "Возвращает коллекцию недействительных имён полей формы из документа."
type: docs
weight: 30
url: /ru/net/groupdocs.editor/formfieldmanager/getinvalidformfieldnames/
---
## FormFieldManager.GetInvalidFormFieldNames method

Возвращает коллекцию недействительных имён полей формы из документа.

```csharp
public IEnumerable<InvalidFormField> GetInvalidFormFieldNames()
```

### Возвращаемое значение

Перечисляемая коллекция строк, представляющая имена недействительных полей формы, найденных в документе.

### Замечания

Метод `GetInvalidFormFieldNames` сканирует содержимое документа, чтобы определить поля формы с недействительными именами. Он возвращает коллекцию строк, содержащих имена этих недействительных полей формы. Поле формы считается недействительным, если оно дублирует уникальный идентификатор с другими полями формы и не имеет уникального имени закладки, связанного с ним. Эти имена закладок служат идентификаторами для каждого поля формы. Возвращаемая коллекция сохраняет порядок имен полей формы в том виде, в каком они появляются в документе. Этот метод полезен для обнаружения и анализа проблем с именованием полей формы, которые могут потребовать исправления с помощью метода [`FixInvalidFormFieldNames`](../fixinvalidformfieldnames).

### См. также

* class [InvalidFormField](../../../groupdocs.editor.words.fieldmanagement/invalidformfield)
* class [FormFieldManager](../../formfieldmanager)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.editor.dll -->
