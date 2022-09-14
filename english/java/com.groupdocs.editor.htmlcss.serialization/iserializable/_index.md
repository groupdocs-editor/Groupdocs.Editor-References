---
title: ISerializable
second_title: GroupDocs.Editor for Java API Reference
description:  Represents an object which supports serialization to a string or to any
 TextWriter implementation using specific serialization options
type: docs
weight: 17
url: /java/com.groupdocs.editor.htmlcss.serialization/iserializable/
---```
public interface ISerializable
```

Represents an object, which supports serialization to a string or to any TextWriter implementation using specific serialization options
## Methods

| Method | Description |
| --- | --- |
| [serialize(ISerializationOptions serializationOptions)](#serialize-com.groupdocs.editor.htmlcss.serialization.ISerializationOptions-) | In implementing type returns a serialized representation of an object as a string |
| [serialize(ISerializationOptions serializationOptions, System.IO.TextWriter output)](#serialize-com.groupdocs.editor.htmlcss.serialization.ISerializationOptions-com.aspose.ms.System.IO.TextWriter-) | In implementing type writes a serialized representation of an object to the specified output TextWriter implementation |
### serialize(ISerializationOptions serializationOptions) {#serialize-com.groupdocs.editor.htmlcss.serialization.ISerializationOptions-}
```
public abstract String serialize(ISerializationOptions serializationOptions)
```


In implementing type returns a serialized representation of an object as a string

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| serializationOptions | [ISerializationOptions](../../com.groupdocs.editor.htmlcss.serialization/iserializationoptions) | Serialization options. Not all properties should be used, but argument should not be null |

**Returns:**
java.lang.String - Resultant string
### serialize(ISerializationOptions serializationOptions, System.IO.TextWriter output) {#serialize-com.groupdocs.editor.htmlcss.serialization.ISerializationOptions-com.aspose.ms.System.IO.TextWriter-}
```
public abstract void serialize(ISerializationOptions serializationOptions, System.IO.TextWriter output)
```


In implementing type writes a serialized representation of an object to the specified output TextWriter implementation

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| serializationOptions | [ISerializationOptions](../../com.groupdocs.editor.htmlcss.serialization/iserializationoptions) | Serialization options. Not all properties should be used, but argument should not be null |
| output | com.aspose.ms.System.IO.TextWriter | TextWriter instance, to which resultant text will be written. Should not be null. |

