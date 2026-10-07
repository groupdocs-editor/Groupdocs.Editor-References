---
title: "GetHashCode"
second_title: "مرجع API لـ GroupDocs.Editor لـ .NET"
description: "يرجع رمز تجزئة (hash code) للكائن الحالي."
type: docs
weight: 40
url: /ar/net/groupdocs.editor.formats.abstraction/formatfamilybase/gethashcode/
---
## FormatFamilyBase.GetHashCode method

يرجع رمز تجزئة (hash code) للكائن الحالي.

```csharp
public override int GetHashCode()
```

### قيمة الإرجاع

رمز تجزئة (hash code) للكائن الحالي، مناسب للاستخدام في خوارزميات التجزئة وهياكل البيانات مثل جدول التجزئة.

### ملاحظات

تُعيد هذه الطريقة تعريف GetHashCode. يتم حساب رمز التجزئة باستخدام خصائص الكائن `Id` و `Name`. يسمح السياق `unchecked` بحدوث تجاوز السعة، وهو مقبول في سياق حساب رمز التجزئة.

### انظر أيضًا

* class [FormatFamilyBase](../../formatfamilybase)
* namespace [GroupDocs.Editor.Formats.Abstraction](../../../groupdocs.editor.formats.abstraction)
* assembly [GroupDocs.Editor](../../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ GroupDocs.editor.dll -->
