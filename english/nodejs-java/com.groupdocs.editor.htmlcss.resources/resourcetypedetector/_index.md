---
title: ResourceTypeDetector
second_title: GroupDocs.Editor for Node.js via Java API Reference
description: Utility static methods for detecting resource types formats
type: docs
weight: 10
url: /nodejs-java/com.groupdocs.editor.htmlcss.resources/resourcetypedetector/
---
**Inheritance:**
java.lang.Object
```
public class ResourceTypeDetector
```

Utility static methods for detecting resource types (formats)
## Constructors

| Constructor | Description |
| --- | --- |
| [ResourceTypeDetector()](#ResourceTypeDetector--) |  |
## Methods

| Method | Description |
| --- | --- |
| [detectTypeFromFilename(String filename)](#detectTypeFromFilename-java.lang.String-) | Detects a type from specified filename and returns an instance of respective IResourceType |
| [tryDetectResource(InputStream inputResourceStream, String name, IResourceType assumptiveFormat)](#tryDetectResource-java.io.InputStream-java.lang.String-com.groupdocs.editor.htmlcss.resources.IResourceType-) | Tries to analyze an input stream and creates one of supportable HTML resources from it, taking into account a specified assumptive type, if it is not null |
### ResourceTypeDetector() {#ResourceTypeDetector--}
```
public ResourceTypeDetector()
```


### detectTypeFromFilename(String filename) {#detectTypeFromFilename-java.lang.String-}
```
public static IResourceType detectTypeFromFilename(String filename)
```


Detects a type from specified filename and returns an instance of respective IResourceType

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filename | java.lang.String | Input filename, from which this method will try to extract the resultant IResourceType implementation |

**Returns:**
[IResourceType](../../com.groupdocs.editor.htmlcss.resources/iresourcetype) - IResourceType implementation on success or NULL on failure
### tryDetectResource(InputStream inputResourceStream, String name, IResourceType assumptiveFormat) {#tryDetectResource-java.io.InputStream-java.lang.String-com.groupdocs.editor.htmlcss.resources.IResourceType-}
```
public static IHtmlResource tryDetectResource(InputStream inputResourceStream, String name, IResourceType assumptiveFormat)
```


Tries to analyze an input stream and creates one of supportable HTML resources from it, taking into account a specified assumptive type, if it is not null

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| inputResourceStream | java.io.InputStream | Input stream, which presumably contains an HTML resource. If invalid, an exception will be thrown. |
| name | java.lang.String | Resource name, which will be used for created and returned resource on success. Cannot be NULL, empty or whitespace |
| assumptiveFormat | [IResourceType](../../com.groupdocs.editor.htmlcss.resources/iresourcetype) | Assumed format of the input HTML resource, which is useful for achieving the best performance. If completely unknown, use the NULL value. May be incorrect, this will only worsen the performance. |

**Returns:**
[IHtmlResource](../../com.groupdocs.editor.htmlcss.resources/ihtmlresource) - Instance, which implements 'IHtmlResource' interface and represents one of supportable HTML resources on success, or NULL on failure
