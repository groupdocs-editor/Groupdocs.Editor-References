---
title: "IResourceType"
second_title: "GroupDocs.Editor für Java API-Referenz"
description: "Stellt eine Instanz des unbekannten Ressourcentyps/-formats Bild Schriftart Text dar"
type: docs
weight: 13
url: /de/java/com.groupdocs.editor.htmlcss.resources/iresourcetype/
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
