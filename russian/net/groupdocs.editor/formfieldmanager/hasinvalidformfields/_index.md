---
title: "HasInvalidFormFields"
second_title: "GroupDocs.Editor для .NET справочник API"
description: "Проверяет, содержит ли документ какие-либо недействительные поля формы."
type: docs
weight: 40
url: /ru/net/groupdocs.editor/formfieldmanager/hasinvalidformfields/
---
## FormFieldManager.HasInvalidFormFields method

Проверяет, содержит ли документ какие-либо недействительные поля формы.

```csharp
public bool HasInvalidFormFields()
```

### Возвращаемое значение

`true` если документ содержит одно или несколько недействительных полей формы; иначе `false`.

### Замечания

Метод `HasInvalidFormFields` сканирует содержимое документа, чтобы определить, содержит ли он какие‑либо поля формы с недействительными именами. Поле формы считается недействительным, если оно дублирует уникальный идентификатор с другими полями формы и не имеет уникального имени закладки, связанного с ним. Эти имена закладок служат идентификаторами для каждого поля формы. Этот метод полезен для быстрой проверки, требуется ли дальнейший осмотр документа и потенциальное исправление имен полей формы. ; ; ;

### См. также

* class [FormFieldManager](../../formfieldmanager)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.editor.dll -->
