---
title: "ICssDataType"
second_title: "مرجع API لـ GroupDocs.Editor لـ Node.js عبر Java"
description: "واجهة مشتركة لجميع أنواع بيانات CSS التي تُستخدم في خصائص CSS"
type: docs
weight: 15
url: /ar/nodejs-java/com.groupdocs.editor.htmlcss.css.datatypes/icssdatatype/
---
**All Implemented Interfaces:**
com.aspose.ms.System.IEquatable
```
public interface ICssDataType extends System.IEquatable<ICssDataType>
```

واجهة مشتركة لجميع أنواع بيانات CSS، التي تُستخدم في خصائص CSS.

## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [serializeDefault()](#serializeDefault--) | يجب أن تُعيد تمثيلًا نصيًا افتراضيًا للقيمة الحالية لل |
نوع البيانات
|
|  | [isDefault()](#isDefault--) | يجب تحديد ما إذا كانت القيمة الحالية لنوع البيانات هي القيمة الافتراضية |
قيمة لهذا النوع المحدد من البيانات أم لا
|
### serializeDefault() {#serializeDefault--}
```
public abstract String serializeDefault()
```


يجب أن تُعيد تمثيلًا نصيًا افتراضيًا للقيمة الحالية لل
نوع البيانات


**Returns:**
java.lang.String -
### isDefault() {#isDefault--}
```
public abstract boolean isDefault()
```


يجب تحديد ما إذا كانت القيمة الحالية لنوع البيانات هي القيمة الافتراضية
قيمة لهذا النوع المحدد من البيانات أم لا


**Returns:**
منطقي -
