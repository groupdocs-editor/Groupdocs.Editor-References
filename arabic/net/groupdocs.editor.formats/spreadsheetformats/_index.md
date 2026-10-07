---
title: "تنسيقات جداول البيانات"
second_title: "مرجع API لـ GroupDocs.Editor لـ .NET"
description: "يضم جميع تنسيقات جداول البيانات الثنائية وXML والنصية باستثناء جميع التنسيقات النصية القائمة على الفواصل مع فواصل مثل CSV وTSV وذات الفواصل المنقوطة إلخ، التي يمكن حفظ المصنف فيها. تشمل الصيغ التالية Xls./spreadsheetformats/xls Xlt./spreadsheetformats/xlt Xlsx./spreadsheetformats/xlsx Xlsm./spreadsheetformats/xlsm Xlsb./spreadsheetformats/xlsb Xltx./spreadsheetformats/xltx Xltm./spreadsheetformats/xltm Xlam./spreadsheetformats/xlam SpreadsheetML./spreadsheetformats/spreadsheetml Ods./spreadsheetformats/ods Fods./spreadsheetformats/fods Sxc./spreadsheetformats/sxc Dif./spreadsheetformats/dif Csv./spreadsheetformats/csv Tsv./spreadsheetformats/tsv. تعرف على المزيد حول تنسيقات جداول البيانات هناhttps//wiki.fileformat.com/spreadsheet."
type: docs
weight: 130
url: /ar/net/groupdocs.editor.formats/spreadsheetformats/
---
## SpreadsheetFormats class

يضم جميع تنسيقات جداول البيانات الثنائية وXML والنصية (باستثناء جميع التنسيقات النصية القائمة على الفواصل مع فواصل مثل CSV وTSV وذات الفواصل المنقوطة إلخ)، التي يمكن حفظ المصنف فيها. تشمل الصيغ التالية: [`Xls`](./xls)، [`Xlt`](./xlt)، [`Xlsx`](./xlsx)، [`Xlsm`](./xlsm)، [`Xlsb`](./xlsb)، [`Xltx`](./xltx)، [`Xltm`](./xltm)، [`Xlam`](./xlam)، [`SpreadsheetML`](./spreadsheetml)، [`Ods`](./ods)، [`Fods`](./fods)، [`Sxc`](./sxc)، [`Dif`](./dif)، [`Csv`](./csv)، [`Tsv`](./tsv). تعرف على المزيد حول تنسيقات جداول البيانات [هنا](https://wiki.fileformat.com/spreadsheet).

```csharp
public class SpreadsheetFormats : DocumentFormatBase
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Extension](../../groupdocs.editor.formats.abstraction/documentformatbase/extension) { get; } | يحصل على امتداد الملف لتنسيق المستند. |
| [FormatFamily](../../groupdocs.editor.formats.abstraction/documentformatbase/formatfamily) { get; } | يحصل على عائلة التنسيق التي ينتمي إليها تنسيق المستند. |
| [Id](../../groupdocs.editor.formats.abstraction/formatfamilybase/id) { get; } | يحصل على المعرف الفريد لعائلة التنسيق. |
| [Mime](../../groupdocs.editor.formats.abstraction/documentformatbase/mime) { get; } | يحصل على نوع MIME لتنسيق المستند. |
| [Name](../../groupdocs.editor.formats.abstraction/formatfamilybase/name) { get; } | يحصل على اسم عائلة التنسيق. |
| static [All](../../groupdocs.editor.formats/spreadsheetformats/all) { get; } | يحصل على مجموعة قابلة للتعداد من جميع [`SpreadsheetFormats`](../spreadsheetformats). |

## الطرق

| الاسم | الوصف |
| --- | --- |
| static [FromExtension](../../groupdocs.editor.formats/spreadsheetformats/fromextension)(string) | يسترجع نسخة من النوع المحدد [`SpreadsheetFormats`](../spreadsheetformats) التي لها امتداد الملف المحدد. |
| [Equals](../../groupdocs.editor.formats.abstraction/formatfamilybase/equals)(FormatFamilyBase) | يحدد ما إذا كان هذا المثيل مساويًا للمثيل المحدد [`FormatFamilyBase`](../../groupdocs.editor.formats.abstraction/formatfamilybase). |
| [Equals](../../groupdocs.editor.formats.abstraction/documentformatbase/equals)(IDocumentFormat) | يحدد ما إذا كان هذا المثيل مساويًا للمثيل المحدد [`IDocumentFormat`](../../groupdocs.editor.formats.abstraction/idocumentformat). |
| override [Equals](../../groupdocs.editor.formats.abstraction/documentformatbase/equals)(object) | يحدد ما إذا كان هذا المثيل مساويًا للمثيل المحدد [`DocumentFormatBase`](../../groupdocs.editor.formats.abstraction/documentformatbase). |
| override [GetHashCode](../../groupdocs.editor.formats.abstraction/documentformatbase/gethashcode)() | يرجع رمز تجزئة (hash code) للكائن الحالي. |
| override [ToString](../../groupdocs.editor.formats.abstraction/formatfamilybase/tostring)() | يرجع سلسلة تمثل الكائن الحالي. |
| [explicit operator](../../groupdocs.editor.formats/spreadsheetformats/op_explicit) | يحوّل سلسلة تمثل امتداد ملف إلى كائن [`SpreadsheetFormats`](../spreadsheetformats). |

## الحقول

| الاسم | الوصف |
| --- | --- |
| static readonly [Csv](../../groupdocs.editor.formats/spreadsheetformats/csv) | القيم المفصولة بفواصل (CSV). تعرّف على المزيد حول هذا التنسيق [هنا](https://docs.fileformat.com/spreadsheet/csv/). |
| static readonly [Dif](../../groupdocs.editor.formats/spreadsheetformats/dif) | تنسيق تبادل البيانات (DIF). |
| static readonly [Fods](../../groupdocs.editor.formats/spreadsheetformats/fods) | جدول بيانات OpenDocument مسطح (FODS). |
| static readonly [Ods](../../groupdocs.editor.formats/spreadsheetformats/ods) | جدول بيانات OpenDocument (ODS). تعرّف على المزيد حول هذا التنسيق [هنا](https://wiki.fileformat.com/spreadsheet/ods). |
| static readonly [SpreadsheetML](../../groupdocs.editor.formats/spreadsheetformats/spreadsheetml) | SpreadsheetML — تنسيق XML لبرنامج Microsoft Office Excel 2002 و Excel 2003. |
| static readonly [Sxc](../../groupdocs.editor.formats/spreadsheetformats/sxc) | جدول بيانات XML لـ StarOffice أو OpenOffice.org Calc (SXC). |
| static readonly [Tsv](../../groupdocs.editor.formats/spreadsheetformats/tsv) | القيم المفصولة بعلامات جدولة (TSV). تعرّف على المزيد حول هذا التنسيق [هنا](https://docs.fileformat.com/spreadsheet/tsv/). |
| static readonly [Xlam](../../groupdocs.editor.formats/spreadsheetformats/xlam) | ملحق Excel (XLAM). |
| static readonly [Xls](../../groupdocs.editor.formats/spreadsheetformats/xls) | تنسيق ملف ثنائي Excel 97-2003 (XLS). تعرّف على المزيد حول هذا التنسيق [هنا](https://wiki.fileformat.com/spreadsheet/xls). |
| static readonly [Xlsb](../../groupdocs.editor.formats/spreadsheetformats/xlsb) | دفتر عمل Excel ثنائي (XLSB). تعرّف على المزيد حول هذا التنسيق [هنا](https://wiki.fileformat.com/spreadsheet/xlsb). |
| static readonly [Xlsm](../../groupdocs.editor.formats/spreadsheetformats/xlsm) | دفتر عمل Office Open XML مع تمكين الماكرو (XLSM). تعرّف على المزيد حول هذا التنسيق [هنا](https://wiki.fileformat.com/spreadsheet/xlsm). |
| static readonly [Xlsx](../../groupdocs.editor.formats/spreadsheetformats/xlsx) | دفتر عمل Office Open XML بدون ماكرو (XLSX). تعرّف على المزيد حول هذا التنسيق [هنا](https://wiki.fileformat.com/spreadsheet/xlsx). |
| static readonly [Xlt](../../groupdocs.editor.formats/spreadsheetformats/xlt) | قالب Excel 97-2003 (XLT). تعرّف على المزيد حول هذا التنسيق [هنا](https://wiki.fileformat.com/spreadsheet/xlt). |
| static readonly [Xltm](../../groupdocs.editor.formats/spreadsheetformats/xltm) | قالب Office Open XML مع تمكين الماكرو (XLTM). تعرّف على المزيد حول هذا التنسيق [هنا](https://wiki.fileformat.com/spreadsheet/xltm). |
| static readonly [Xltx](../../groupdocs.editor.formats/spreadsheetformats/xltx) | قالب Office Open XML بدون ماكرو (XLTX). تعرّف على المزيد حول هذا التنسيق [هنا](https://wiki.fileformat.com/spreadsheet/xltx). |

### انظر أيضًا

* class [DocumentFormatBase](../../groupdocs.editor.formats.abstraction/documentformatbase)
* namespace [GroupDocs.Editor.Formats](../../groupdocs.editor.formats)
* assembly [GroupDocs.Editor](../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ GroupDocs.editor.dll -->
