---
title: SpreadsheetFormats
second_title: GroupDocs.Editor لمرجع .NET API
description: يشمل جميع تنسيقات جداول البيانات الثنائية و XML والنصية باستثناء جميع التنسيقات القائمة على المحدد النصي بفاصل مثل CSV و TSV والفاصلة المنقوطة وما إلى ذلك  حيث يمكن حفظ المصنف. يتضمن التنسيقات التالية Dif./spreadsheetformats/dif  Fods./spreadsheetformats/fods  Ods./spreadsheetformats/ods  Sxc./spreadsheetformats/sxc  Xlam./spreadsheetformats/xlam  Xls./spreadsheetformats/xls  Xlsb./spreadsheetformats/xlsb  Xlsm./spreadsheetformats/xlsm  Xlsx./spreadsheetformats/xlsx  Xlt./spreadsheetformats/xlt  Xltm./spreadsheetformats/xltm  Xltx./spreadsheetformats/xltx . تعرف على المزيد حول تنسيقات جداول البياناتهناhttps//wiki.fileformat.com/spreadsheet .
type: docs
weight: 130
url: /ar/net/groupdocs.editor.formats/spreadsheetformats/
---
## SpreadsheetFormats structure

يشمل جميع تنسيقات جداول البيانات الثنائية و XML والنصية (باستثناء جميع التنسيقات القائمة على المحدد النصي بفاصل مثل CSV و TSV والفاصلة المنقوطة وما إلى ذلك) ، حيث يمكن حفظ المصنف. يتضمن التنسيقات التالية: [`Dif`](./dif) ، [`Fods`](./fods) ، [`Ods`](./ods) ، [`Sxc`](./sxc) ، [`Xlam`](./xlam) ، [`Xls`](./xls) ، [`Xlsb`](./xlsb) ، [`Xlsm`](./xlsm) ، [`Xlsx`](./xlsx) ، [`Xlt`](./xlt) ، [`Xltm`](./xltm) ، [`Xltx`](./xltx) . تعرف على المزيد حول تنسيقات جداول البيانات[هنا](https://wiki.fileformat.com/spreadsheet) .

```csharp
public struct SpreadsheetFormats : IDocumentFormat, IEquatable<SpreadsheetFormats>
```

## الخصائص

| اسم | وصف |
| --- | --- |
| [Extension](../../groupdocs.editor.formats/spreadsheetformats/extension) { get; } | إرجاع امتداد (بدون النقطة البادئة) لتنسيق جدول البيانات هذا بأحرف صغيرة |
| [Mime](../../groupdocs.editor.formats/spreadsheetformats/mime) { get; } | إرجاع رمز MIME لهذا التنسيق |
| [Name](../../groupdocs.editor.formats/spreadsheetformats/name) { get; } | إرجاع الاسم الكامل الرسمي لتنسيق جدول البيانات هذا |

## طُرق

| اسم | وصف |
| --- | --- |
| static [FromExtension](../../groupdocs.editor.formats/spreadsheetformats/fromextension)(string) | إرجاع مثيل[`SpreadsheetFormats`](../spreadsheetformats) الهيكل ، المرتبط بامتداد اسم الملف المحدد ، أو يطرح استثناءً ، إذا كان التمديد لا يمكن تحليله بشكل صحيح |
| [Equals](../../groupdocs.editor.formats/spreadsheetformats/equals#equals)(IDocumentFormat) | تحديد ما إذا كان هذا المثيل مساويًا لمثيل IDocumentFormat المحدد الآخر. |
| override [Equals](../../groupdocs.editor.formats/spreadsheetformats/equals#equals_2)(object) | تحديد ما إذا كان هذا المثيل مساويًا للكائن المحدد الآخر ، والذي يُفترض أنه من SpreadsheetFormats |
| [Equals](../../groupdocs.editor.formats/spreadsheetformats/equals#equals_1)(SpreadsheetFormats) | تحديد ما إذا كان هذا المثيل مساويًا لـ SpreadsheetFormats المحدد الآخر ، example |
| override [GetHashCode](../../groupdocs.editor.formats/spreadsheetformats/gethashcode)() | إرجاع رمز تجزئة غير قابل للتغيير في هذا المثال |
| [operator ==](../../groupdocs.editor.formats/spreadsheetformats/op_equality) | لفحص مثيلين معينين من SpreadsheetFormats على المساواة |
| [operator !=](../../groupdocs.editor.formats/spreadsheetformats/op_inequality) | لفحص مثيلين معينين من SpreadsheetFormats على عدم المساواة |

## مجالات

| اسم | وصف |
| --- | --- |
| static readonly [Csv](../../groupdocs.editor.formats/spreadsheetformats/csv) | تمثل مستندات القيم المفصولة بفواصل (CSV) نصًا عاديًا يحتوي على سجلات البيانات بقيم مفصولة بفواصل. كل سطر في ملف CSV هو رقم قياسي جديد من مجموعة السجلات الموجودة في الملف. تعرف على المزيد حول تنسيق الملف هذا[هنا](https://docs.fileformat.com/spreadsheet/csv/) . |
| static readonly [Dif](../../groupdocs.editor.formats/spreadsheetformats/dif) | تنسيق تبادل البيانات (DIF) |
| static readonly [Fods](../../groupdocs.editor.formats/spreadsheetformats/fods) | جدول بيانات OpenDocument مسطح (FODS) - يتم تخزينه كمستند XML واحد غير مضغوط |
| static readonly [Ods](../../groupdocs.editor.formats/spreadsheetformats/ods) | يشير جدول بيانات OpenDocument (ODS) إلى تنسيق OpenDocument Spreadsheet Document الذي يمكن للمستخدم تحريره. يتم تخزين البيانات داخل ملف ODF في صفوف وأعمدة. تعرف على المزيد حول تنسيق الملف هذا[هنا](https://wiki.fileformat.com/spreadsheet/ods) . |
| static readonly [SpreadsheetML](../../groupdocs.editor.formats/spreadsheetformats/spreadsheetml) | SpreadsheetML - تنسيق Microsoft Office Excel 2002 و Excel 2003 XML |
| static readonly [Sxc](../../groupdocs.editor.formats/spreadsheetformats/sxc) | StarOffice أو OpenOffice.org Calc XML Spreadsheet (SXC) |
| static readonly [Tsv](../../groupdocs.editor.formats/spreadsheetformats/tsv) | يمثل تنسيق ملف قيم مفصولة بعلامات جدولة (TSV) بيانات مفصولة بعلامات تبويب بتنسيق نص عادي. يتم استخدام تنسيق الملف ، المماثل لـ CSV ، لتنظيم البيانات بطريقة منظمة من أجل الاستيراد والتصدير بين التطبيقات المختلفة. تعرف على المزيد حول تنسيق الملف هذا[هنا](https://docs.fileformat.com/spreadsheet/tsv/) . |
| static readonly [Xlam](../../groupdocs.editor.formats/spreadsheetformats/xlam) | وظيفة Excel الإضافية (XLAM) |
| static readonly [Xls](../../groupdocs.editor.formats/spreadsheetformats/xls) | Excel 97-2003 Binary File Format (XLS) يمثل الملفات التي يمكن إنشاؤها بواسطة Microsoft Excel بالإضافة إلى برامج جداول البيانات المماثلة الأخرى مثل OpenOffice Calc أو Apple Numbers. تعرف على المزيد حول تنسيق الملف هذا[هنا](https://wiki.fileformat.com/spreadsheet/xls) . |
| static readonly [Xlsb](../../groupdocs.editor.formats/spreadsheetformats/xlsb) | Excel Binary Workbook (XLSB) يحدد تنسيق ملف Excel الثنائي ، وهو عبارة عن مجموعة من السجلات والهياكل التي تحدد محتوى مصنف Excel. تعرف على المزيد حول تنسيق الملف هذا[هنا](https://wiki.fileformat.com/spreadsheet/xlsb) . |
| static readonly [Xlsm](../../groupdocs.editor.formats/spreadsheetformats/xlsm) | Office Open XML Workbook Macro-Enabled (XLSM) هو نوع من ملفات Spreasheet التي تدعم وحدات الماكرو . تعرف على المزيد حول تنسيق الملف هذا[هنا](https://wiki.fileformat.com/spreadsheet/xlsm) . |
| static readonly [Xlsx](../../groupdocs.editor.formats/spreadsheetformats/xlsx) | Office Open XML Workbook Macro-Free (XLSX) يمثل المستندات التي قدمتها Microsoft مع إصدار Microsoft Office 2007. تعرف على المزيد حول تنسيق الملف هذا[هنا](https://wiki.fileformat.com/spreadsheet/xlsx) . |
| static readonly [Xlt](../../groupdocs.editor.formats/spreadsheetformats/xlt) | قالب Excel 97-2003 (XLT) يمثل ملفات القوالب التي تم إنشاؤها باستخدام Microsoft Excel وهو تطبيق جداول بيانات يأتي كجزء من مجموعة Microsoft Office. دعم Microsoft Office 97-2003 إنشاء ملفات XLT جديدة بالإضافة إلى فتحها. تعرف على المزيد حول تنسيق الملف هذا[هنا](https://wiki.fileformat.com/spreadsheet/xlt) . |
| static readonly [Xltm](../../groupdocs.editor.formats/spreadsheetformats/xltm) | Office Open XML Template Macro-Enabled (XLTM) يمثل الملفات التي تم إنشاؤها بواسطة Microsoft Excel كملفات قوالب ممكنة بماكرو. تتشابه ملفات XLTM مع XLTX من حيث البنية بخلاف أن أحدثها لا يدعم إنشاء ملفات القوالب باستخدام وحدات الماكرو. تعرف على المزيد حول تنسيق الملف هذا[هنا](https://wiki.fileformat.com/spreadsheet/xltm) . |
| static readonly [Xltx](../../groupdocs.editor.formats/spreadsheetformats/xltx) | يمثل ملف Office Open XML Template Macro-Free (XLTX) قالب Microsoft Excel الذي يستند إلى مواصفات تنسيق ملف Office OpenXML. يتم استخدامه لإنشاء ملف قالب قياسي يمكن استخدامه لإنشاء ملفات XLSX التي تعرض نفس الإعدادات المحددة في ملف XLTX . تعرف على المزيد حول تنسيق الملف هذا[هنا](https://wiki.fileformat.com/spreadsheet/xltx) . |
| static readonly [All](../../groupdocs.editor.formats/spreadsheetformats/all) | إرجاع فئة داخلية توفر احتمالات لا تعد ولا تحصى على جميع تنسيقات جداول البيانات الحالية |

## أعضاء آخرون

| اسم | وصف |
| --- | --- |
| class [AllEnumerable](spreadsheetformats.allenumerable) | تطبيقات I واجهة عامة قابلة للعدد ، والتي تتيح إمكانية "foreach" لنوع SpreadsheetFormats type |

### أنظر أيضا

* interface [IDocumentFormat](../idocumentformat)
* مساحة الاسم [GroupDocs.Editor.Formats](../../groupdocs.editor.formats)
* المجسم [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->
