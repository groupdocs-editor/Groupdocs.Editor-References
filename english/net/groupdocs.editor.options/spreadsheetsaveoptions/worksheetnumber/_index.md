---
title: WorksheetNumber
second_title: GroupDocs.Editor for .NET API Reference
description: Allows to insert edited worksheet into copy of existing spreadsheet instead of creating a new singleworksheet spreadsheet default behavior. WorksheetNumber is a 1based number of a worksheet in the spreadsheet loaded in the Editor class. If it is 0 default value the new spreadsheet will be created with single edited worksheet. If it is greater or lesser then zero and there is valid spreadsheet loaded in the Editor class the edited worksheet that is represented by input EditableDocument instance will be inserted into this spreadsheet.
type: docs
weight: 50
url: /net/groupdocs.editor.options/spreadsheetsaveoptions/worksheetnumber/
---
## SpreadsheetSaveOptions.WorksheetNumber property

Allows to insert edited worksheet into copy of existing spreadsheet instead of creating a new single-worksheet spreadsheet (default behavior). WorksheetNumber is a 1-based number of a worksheet in the spreadsheet, loaded in the Editor class. If it is 0 (default value), the new spreadsheet will be created with single edited worksheet. If it is greater or lesser then zero, and there is valid spreadsheet, loaded in the Editor class, the edited worksheet, that is represented by input EditableDocument instance, will be inserted into this spreadsheet.

```csharp
public int WorksheetNumber { get; set; }
```

### Remarks

WorksheetNumber integer property, if it is not in default state (reserved value '0'), represents a worksheet number, so it starts from 1, not from zero, and its max value is the amount of all existing slides in a presentation. However, if specified value is greater then amount of all slides, GroupDocs.Editor will adjust it to mark the last worksheet. Negative values are also allowed and count worksheets from end. For example, "-1" implies last worksheet in a spreadsheet, "-2" — last but one, etc. Like with positive values, when negative worksheet number exceeds the total count of worksheets in the given spreadsheet, it will be adjusted to the first worksheet. The [`InsertAsNewWorksheet`](../insertasnewworksheet) boolean property is tightly coupled with this one.

### Examples

Given spreadsheet has 5 worksheets: WorksheetNumber = 0; — ignore given spreadsheet, create a new spreadsheet and put edited worksheet into it. WorksheetNumber = 1; — replace the first worksheet with edited WorksheetNumber = 2; — replace the second worksheet with edited WorksheetNumber = 5; — replace the last (5th) worksheet with edited WorksheetNumber = 6; — replace the last (5th) worksheet with edited, because 6 is greater then 5 and thus is adjusted WorksheetNumber = -1; — replace the last (5th) worksheet with edited, because "-1" means "last existing" WorksheetNumber = -2; — replace the 4th worksheet with edited WorksheetNumber = -3; — replace the 3rd worksheet with edited WorksheetNumber = -4; — replace the 2nd worksheet with edited WorksheetNumber = -5; — replace the first worksheet with edited WorksheetNumber = -6; — replace the first worksheet with edited, because "-6" is greater then 5 and thus is adjusted

### See Also

* class [SpreadsheetSaveOptions](../../spreadsheetsaveoptions)
* namespace [GroupDocs.Editor.Options](../../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.editor.dll -->
