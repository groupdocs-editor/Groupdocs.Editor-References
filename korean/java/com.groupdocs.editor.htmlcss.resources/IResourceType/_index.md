---
title: "IResourceType"
second_title: "GroupDocs.Editor for Java API 참조"
description: "알 수 없는 리소스 유형/포맷(이미지, 폰트, 텍스트)의 하나의 인스턴스를 나타냅니다"
type: docs
weight: 13
url: /ko/java/com.groupdocs.editor.htmlcss.resources/iresourcetype/
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
