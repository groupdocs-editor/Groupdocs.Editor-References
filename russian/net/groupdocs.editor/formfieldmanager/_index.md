---
title: "FormFieldManager"
second_title: "GroupDocs.Editor для .NET справочник API"
description: "Управляйте формой с устаревшими полями формы. Устаревшие поля формы — это типы полей, которые были доступны в более ранних версиях обработки Word. Группа Legacy Forms, видимая после щелчка по значку Legacy Tools, включает три типа полей формы, которые вы можете вставить в документ: текст, флажок, выпадающий список, дата и т.д. см. больше FormFieldType../groupdocs.editor.words.fieldmanagement/formfieldtype. Каждый из этих полей формы позволяет пользователю формы выбирать или вводить информацию соответствующего типа."
type: docs
weight: 40
url: /ru/net/groupdocs.editor/formfieldmanager/
---
## FormFieldManager class

Управляйте формой с устаревшими полями формы. Устаревшие поля формы — это типы полей, которые были доступны в более ранних версиях обработки Word. Группа Legacy Forms (видимая после щелчка по значку Legacy Tools) включает три типа полей формы, которые вы можете вставить в документ: текст, флажок, выпадающий список, дата и т.д., см. больше [`FormFieldType`](../../groupdocs.editor.words.fieldmanagement/formfieldtype). Каждый из этих полей формы позволяет пользователю формы выбирать или вводить информацию соответствующего типа.

```csharp
public sealed class FormFieldManager
```

## Свойства

| Имя | Описание |
| --- | --- |
| [FormFieldCollection](../../groupdocs.editor/formfieldmanager/formfieldcollection) { get; } | Получает коллекцию полей формы в документе. |

## Методы

| Имя | Описание |
| --- | --- |
| [FixInvalidFormFieldNames](../../groupdocs.editor/formfieldmanager/fixinvalidformfieldnames)(IEnumerable&lt;InvalidFormField&gt;) | Исправляет недействительные имена полей формы в документе, применяя указанные обновления или автоматически генерируя уникальные имена. |
| [GetInvalidFormFieldNames](../../groupdocs.editor/formfieldmanager/getinvalidformfieldnames)() | Возвращает коллекцию недействительных имён полей формы из документа. |
| [HasInvalidFormFields](../../groupdocs.editor/formfieldmanager/hasinvalidformfields)() | Проверяет, содержит ли документ какие-либо недействительные поля формы. |
| [RemoveFormFields](../../groupdocs.editor/formfieldmanager/removeformfields)(IEnumerable&lt;IFormField&gt;) | Удаляет несколько полей формы из документа. |
| [RemoveFormFiled](../../groupdocs.editor/formfieldmanager/removeformfiled)(IFormField) | Удаляет конкретное поле формы из документа. |
| [UpdateFormFiled](../../groupdocs.editor/formfieldmanager/updateformfiled)(FormFieldCollection) | Обновляет поля формы в документе на основе предоставленной коллекции полей формы. |

### Замечания

Класс [`FormFieldManager`](../formfieldmanager) предоставляет функциональность для работы с полями формы в документе. Он позволяет пользователям получать, обновлять, исправлять, проверять на недействительность и удалять поля формы из документа.

### См. также

* namespace [GroupDocs.Editor](../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.editor.dll -->
