---
title: "IResourceType"
second_title: "GroupDocs.Editor για Node.js μέσω Java API Reference"
description: "Αντιπροσωπεύει ένα αντικείμενο του άγνωστου τύπου/μορφής πόρου εικόνας γραμματοσειράς κειμένου"
type: docs
weight: 13
url: /el/nodejs-java/com.groupdocs.editor.htmlcss.resources/iresourcetype/
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
