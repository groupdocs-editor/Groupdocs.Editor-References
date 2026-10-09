---
title: "IHtmlResource"
second_title: "مرجع API لـ GroupDocs.Editor لـ Node.js عبر Java"
description: "يمثل نسخة واحدة من مورد HTML غير المعروف، صورة نقطية أو متجهة، ورقة أنماط، خط، نص، مورد CSS XML إلخ"
type: docs
weight: 12
url: /ar/nodejs-java/com.groupdocs.editor.htmlcss.resources/ihtmlresource/
---
**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.resources.IAuxDisposable](../../com.groupdocs.editor.htmlcss.resources/iauxdisposable)
```
public interface IHtmlResource extends IAuxDisposable
```

يمثل نسخة واحدة من مورد HTML غير المعروف (صورة نقطية أو متجهة،
ورقة أنماط، خط، نص (CSS, XML) إلخ)

## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getName()](#getName--) | اسم مورد HTML |
|
|  | [getFilenameWithExtension()](#getFilenameWithExtension--) | اسم الملف الصحيح للمورد المحدد مع الملف المناسب |
الامتداد
|
|  | [getType()](#getType--) | نوع مورد HTML |
|
|  | [getByteContent()](#getByteContent--) | محتوى مورد HTML على شكل تدفق بايت |
|
|  | [getTextContent()](#getTextContent--) | محتوى مورد HTML على شكل سلسلة نصية مشفرة بقاعدة64 |
للموارد الثنائية أو نص بسيط للموارد النصية
|
|  | [save(String fullPathToFile)](#save-java.lang.String-) | يحفظ المورد الحالي إلى الملف المحدد |
|
### getName() {#getName--}
```
public abstract String getName()
```


اسم مورد HTML


**Returns:**
java.lang.String -
### getFilenameWithExtension() {#getFilenameWithExtension--}
```
public abstract String getFilenameWithExtension()
```


اسم الملف الصحيح للمورد المحدد مع الملف المناسب
الامتداد


**Returns:**
java.lang.String -
### getType() {#getType--}
```
public abstract IResourceType getType()
```


نوع مورد HTML


**Returns:**
[IResourceType](../../com.groupdocs.editor.htmlcss.resources/iresourcetype) - 
### getByteContent() {#getByteContent--}
```
public abstract InputStream getByteContent()
```


محتوى مورد HTML على شكل تدفق بايت


**Returns:**
java.io.InputStream
### getTextContent() {#getTextContent--}
```
public abstract String getTextContent()
```


محتوى مورد HTML على شكل سلسلة نصية مشفرة بقاعدة64
للموارد الثنائية أو نص بسيط للموارد النصية


**Returns:**
java.lang.String
### save(String fullPathToFile) {#save-java.lang.String-}
```
public abstract void save(String fullPathToFile)
```


يحفظ المورد الحالي إلى الملف المحدد


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | fullPathToFile | java.lang.String | المسار الكامل للملف الذي سيتم إنشاؤه أو إعادة كتابته بمحتوى المورد الحالي |
|

