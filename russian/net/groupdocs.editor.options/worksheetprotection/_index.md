---
title: "WorksheetProtection"
second_title: "GroupDocs.Editor для .NET справочник API"
description: "Инкапсулирует параметры защиты листа, позволяющие защитить лист в выходном документе Spreadsheet от изменения указанного типа с использованием заданного пароля."
type: docs
weight: 1250
url: /ru/net/groupdocs.editor.options/worksheetprotection/
---
## WorksheetProtection class

Инкапсулирует параметры защиты листа, позволяющие защитить лист в выходном документе Spreadsheet от изменения указанного типа с использованием заданного пароля.

```csharp
public sealed class WorksheetProtection
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [WorksheetProtection](worksheetprotection#constructor)() | Создаёт новый экземпляр с параметрами по умолчанию. Если не изменён и передан в SpreadsheetSaveOptions, защита листа применена не будет. |
| [WorksheetProtection](worksheetprotection#constructor_1)(WorksheetProtectionType, string) | Создаёт новый экземпляр с указанным типом защиты листа и паролем. |

## Свойства

| Имя | Описание |
| --- | --- |
| [Password](../../groupdocs.editor.options/worksheetprotection/password) { get; set; } | Пароль, используемый для защиты листа. Если NULL или пустая строка, защита применена не будет. |
| [ProtectionType](../../groupdocs.editor.options/worksheetprotection/protectiontype) { get; set; } | Позволяет указать тип защиты листа. По умолчанию — 'None' — защита не применяется. |

### Замечания

Большинство форматов Spreadsheet, таких как XLSX, позволяют защищать лист от редактирования паролем. Этот класс позволяет включить такую защиту и задать её параметры.

### См. также

* namespace [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.editor.dll -->
