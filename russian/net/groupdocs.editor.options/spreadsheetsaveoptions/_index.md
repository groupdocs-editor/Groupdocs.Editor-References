---
title: "SpreadsheetSaveOptions"
second_title: "GroupDocs.Editor для .NET справочник API"
description: "Позволяет указать пользовательские параметры для создания и сохранения документов Spreadsheet, совместимых с Excel."
type: docs
weight: 1130
url: /ru/net/groupdocs.editor.options/spreadsheetsaveoptions/
---
## SpreadsheetSaveOptions class

Позволяет задавать пользовательские параметры для создания и сохранения документов таблиц (соответствующих Excel)

```csharp
public sealed class SpreadsheetSaveOptions : ISaveOptions
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [SpreadsheetSaveOptions](spreadsheetsaveoptions#constructor)() | Этот конструктор без параметров создает новый экземпляр SpreadsheetSaveOptions с форматом вывода XLSX (может быть изменён затем через свойство [`OutputFormat`](./outputformat)) |
| [SpreadsheetSaveOptions](spreadsheetsaveoptions#constructor_1)(SpreadsheetFormats) | Создаёт новый экземпляр SpreadsheetSaveOptions с указанным обязательным форматом вывода Spreadsheet, при этом все остальные параметры имеют значения по умолчанию |

## Свойства

| Имя | Описание |
| --- | --- |
| [InsertAsNewWorksheet](../../groupdocs.editor.options/spreadsheetsaveoptions/insertasnewworksheet) { get; set; } | Логический флаг, который указывает, должна ли отредактированная рабочая листа заменить существующую рабочую листу в оригинальной таблице на позиции, указанной свойством [`WorksheetNumber`](./worksheetnumber), или она должна быть вставлена между существующей рабочей листой и предыдущей, без замены её содержимого. По умолчанию false — существующая рабочая листа будет заменена. Это свойство игнорируется, если значение свойства [`WorksheetNumber`](./worksheetnumber) установлено в '0'. |
| [OutputFormat](../../groupdocs.editor.options/spreadsheetsaveoptions/outputformat) { get; set; } | Позволяет указать формат Spreadsheet, который будет использоваться для сохранения документа |
| [Password](../../groupdocs.editor.options/spreadsheetsaveoptions/password) { get; set; } | Позволяет указать, изменить, получить или удалить пароль, который будет использоваться для шифрования сгенерированного документа Spreadsheet, если данный формат документа поддерживает защиту паролем. Укажите NULL или пустую строку для удаления (очистки) пароля. |
| [WorksheetNumber](../../groupdocs.editor.options/spreadsheetsaveoptions/worksheetnumber) { get; set; } | Позволяет вставить отредактированный рабочий лист в копию существующей таблицы вместо создания новой таблицы с одним листом (поведение по умолчанию). WorksheetNumber — это номер листа, начинающийся с 1, в таблице, загруженной в класс Editor. Если он равен 0 (значение по умолчанию), будет создана новая таблица с единственным отредактированным листом. Если он больше или меньше нуля, и существует действительная таблица, загруженная в класс Editor, отредактированный рабочий лист, представленный экземпляром EditableDocument, будет вставлен в эту таблицу. |
| [WorksheetNumbersToDelete](../../groupdocs.editor.options/spreadsheetsaveoptions/worksheetnumberstodelete) { get; set; } | Позволяет указать массив с номерами листов, начинающимися с 1, которые должны быть удалены из таблицы при её сохранении, в случае когда отредактированный лист вставляется в существующую таблицу |
| [WorksheetProtection](../../groupdocs.editor.options/spreadsheetsaveoptions/worksheetprotection) { get; set; } | Позволяет включить защиту листа для выходного документа Spreadsheet. По умолчанию NULL — защита не применяется. Не все форматы поддерживают защиту листа. |

### См. также

* interface [ISaveOptions](../isaveoptions)
* namespace [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.editor.dll -->
