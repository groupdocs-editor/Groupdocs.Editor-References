---
title: "UpdateFormFiled"
second_title: "GroupDocs.Editor для .NET справочник API"
description: "Обновляет поля формы в документе на основе предоставленной коллекции полей формы."
type: docs
weight: 70
url: /ru/net/groupdocs.editor/formfieldmanager/updateformfiled/
---
## FormFieldManager.UpdateFormFiled method

Обновляет поля формы в документе на основе предоставленной коллекции полей формы.

```csharp
public void UpdateFormFiled(FormFieldCollection formFieldCollection)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| formFieldCollection | FormFieldCollection | Коллекция полей формы, содержащая обновления, которые необходимо применить к документу. |

### Замечания

Метод `UpdateFormFiled` обновляет поля формы в документе на основе предоставленной *formFieldCollection*. Каждое поле формы в коллекции соответствует полю формы в документе, и указанные в коллекции обновления применяются соответственно. Этот метод полезен для синхронизации данных полей формы между документом и внешним источником, таким как пользовательский интерфейс или база данных.

### См. также

* class [FormFieldCollection](../../../groupdocs.editor.words.fieldmanagement/formfieldcollection)
* class [FormFieldManager](../../formfieldmanager)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.editor.dll -->
