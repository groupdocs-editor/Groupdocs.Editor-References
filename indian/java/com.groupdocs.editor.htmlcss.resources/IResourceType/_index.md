---
title: "IResourceType"
second_title: "GroupDocs.Editor for Java API संदर्भ"
description: "अज्ञात संसाधन प्रकार/फ़ॉर्मेट (छवि, फ़ॉन्ट, टेक्स्ट) का एक उदाहरण दर्शाता है"
type: docs
weight: 13
url: /hi/java/com.groupdocs.editor.htmlcss.resources/iresourcetype/
---```
public interface IResourceType
```

Represents one instance of the unknown resource type/format (image, font, text)

## Methods

| Method | Description |
| --- | --- |
| [getFormalName()](#getFormalName--) | Formal name of the resource type
 |
| [getFileExtension()](#getFileExtension--) | File extension for the specified resource type without dot divider
 |
| [getMimeCode()](#getMimeCode--) | MIME code for the specific resource type
 |
### getFormalName() {#getFormalName--}
```
public abstract String getFormalName()
```


Formal name of the resource type


**Returns:**
java.lang.String
### getFileExtension() {#getFileExtension--}
```
public abstract String getFileExtension()
```


File extension for the specified resource type without dot divider


**Returns:**
java.lang.String
### getMimeCode() {#getMimeCode--}
```
public abstract String getMimeCode()
```


MIME code for the specific resource type


**Returns:**
java.lang.String
