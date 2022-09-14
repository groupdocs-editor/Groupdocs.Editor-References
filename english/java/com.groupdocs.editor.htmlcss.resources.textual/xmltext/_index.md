---
title: XmlText
second_title: GroupDocs.Editor for Java API Reference
description:  Represents one textual resource which is a XML.
type: docs
weight: 14
url: /java/com.groupdocs.editor.htmlcss.resources.textual/xmltext/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.htmlcss.resources.textual.TextResourceBase](../../com.groupdocs.editor.htmlcss.resources.textual/textresourcebase)
```
public final class XmlText extends TextResourceBase
```

Represents one textual resource, which is a XML.
## Constructors

| Constructor | Description |
| --- | --- |
| [XmlText(String name, String textualContent, System.Text.Encoding originalEncoding)](#XmlText-java.lang.String-java.lang.String-com.aspose.ms.System.Text.Encoding-) |  |
| [XmlText(String name, System.IO.Stream binaryContent, System.Text.Encoding originalEncoding)](#XmlText-java.lang.String-com.aspose.ms.System.IO.Stream-com.aspose.ms.System.Text.Encoding-) |  |
## Methods

| Method | Description |
| --- | --- |
| [getParsedDocument()](#getParsedDocument--) |  |
| [getType()](#getType--) | Returns TextType.Xml |
### XmlText(String name, String textualContent, System.Text.Encoding originalEncoding) {#XmlText-java.lang.String-java.lang.String-com.aspose.ms.System.Text.Encoding-}
```
public XmlText(String name, String textualContent, System.Text.Encoding originalEncoding)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String |  |
| textualContent | java.lang.String |  |
| originalEncoding | com.aspose.ms.System.Text.Encoding |  |

### XmlText(String name, System.IO.Stream binaryContent, System.Text.Encoding originalEncoding) {#XmlText-java.lang.String-com.aspose.ms.System.IO.Stream-com.aspose.ms.System.Text.Encoding-}
```
public XmlText(String name, System.IO.Stream binaryContent, System.Text.Encoding originalEncoding)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String |  |
| binaryContent | com.aspose.ms.System.IO.Stream |  |
| originalEncoding | com.aspose.ms.System.Text.Encoding |  |

### getParsedDocument() {#getParsedDocument--}
```
public final System.Xml.XmlDocument getParsedDocument()
```




**Returns:**
com.aspose.ms.System.Xml.XmlDocument
### getType() {#getType--}
```
public TextType getType()
```


Returns TextType.Xml

**Returns:**
[TextType](../../com.groupdocs.editor.htmlcss.resources.textual/texttype)
