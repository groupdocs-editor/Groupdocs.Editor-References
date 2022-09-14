---
title: TextualResourceParser
second_title: GroupDocs.Editor for Java API Reference
description: 
type: docs
weight: 13
url: /java/com.groupdocs.editor.htmlcss.resources.textual/textualresourceparser/
---
**Inheritance:**
java.lang.Object
```
public class TextualResourceParser
```
## Constructors

| Constructor | Description |
| --- | --- |
| [TextualResourceParser()](#TextualResourceParser--) |  |
## Methods

| Method | Description |
| --- | --- |
| [parse(String textContent, String name, TextType assumptiveType)](#parse-java.lang.String-java.lang.String-com.groupdocs.editor.htmlcss.resources.textual.TextType-) |  |
| [parse(System.IO.Stream binaryContent, String name, System.Text.Encoding contentEncoding, TextType assumptiveType)](#parse-com.aspose.ms.System.IO.Stream-java.lang.String-com.aspose.ms.System.Text.Encoding-com.groupdocs.editor.htmlcss.resources.textual.TextType-) |  |
### TextualResourceParser() {#TextualResourceParser--}
```
public TextualResourceParser()
```


### parse(String textContent, String name, TextType assumptiveType) {#parse-java.lang.String-java.lang.String-com.groupdocs.editor.htmlcss.resources.textual.TextType-}
```
public static TextResourceBase parse(String textContent, String name, TextType assumptiveType)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| textContent | java.lang.String |  |
| name | java.lang.String |  |
| assumptiveType | [TextType](../../com.groupdocs.editor.htmlcss.resources.textual/texttype) |  |

**Returns:**
[TextResourceBase](../../com.groupdocs.editor.htmlcss.resources.textual/textresourcebase)
### parse(System.IO.Stream binaryContent, String name, System.Text.Encoding contentEncoding, TextType assumptiveType) {#parse-com.aspose.ms.System.IO.Stream-java.lang.String-com.aspose.ms.System.Text.Encoding-com.groupdocs.editor.htmlcss.resources.textual.TextType-}
```
public static TextResourceBase parse(System.IO.Stream binaryContent, String name, System.Text.Encoding contentEncoding, TextType assumptiveType)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| binaryContent | com.aspose.ms.System.IO.Stream |  |
| name | java.lang.String |  |
| contentEncoding | com.aspose.ms.System.Text.Encoding |  |
| assumptiveType | [TextType](../../com.groupdocs.editor.htmlcss.resources.textual/texttype) |  |

**Returns:**
[TextResourceBase](../../com.groupdocs.editor.htmlcss.resources.textual/textresourcebase)
