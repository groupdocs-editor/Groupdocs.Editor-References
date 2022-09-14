---
title: AsposeWordsCollector
second_title: GroupDocs.Editor for Java API Reference
description: 
type: docs
weight: 14
url: /java/com.groupdocs.editor.metadata/asposewordscollector/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.metadata.AsposeCollectorBase](../../com.groupdocs.editor.metadata/asposecollectorbase)
```
public final class AsposeWordsCollector extends AsposeCollectorBase
```
## Constructors

| Constructor | Description |
| --- | --- |
| [AsposeWordsCollector()](#AsposeWordsCollector--) |  |
## Methods

| Method | Description |
| --- | --- |
| [hasDigitalSignature()](#hasDigitalSignature--) | Returns true if this document contains a digital signature. |
| [setDigitalSignature(boolean value)](#setDigitalSignature-boolean-) | Returns true if this document contains a digital signature. |
| [getEncoding()](#getEncoding--) | Gets the detected encoding if applicable to the current document format. |
| [setEncoding(Charset value)](#setEncoding-java.nio.charset.Charset-) | Gets the detected encoding if applicable to the current document format. |
### AsposeWordsCollector() {#AsposeWordsCollector--}
```
public AsposeWordsCollector()
```


### hasDigitalSignature() {#hasDigitalSignature--}
```
public final boolean hasDigitalSignature()
```


Returns true if this document contains a digital signature. This property merely informs that a digital signature is present on a document, but it does not specify whether the signature is valid or not.

--------------------

This property exists to help you sort documents that are digitally signed from those that are not. If you use Aspose.Words to modify and save a document that is digitally signed, then the digital signature will be lost. This is by design because a digital signature exists to guard the authenticity of a document. Using this property you can detect digitally signed documents before processing them in the same way as normal documents and take some action to avoid losing the digital signature, for example notify the user.

**Returns:**
boolean
### setDigitalSignature(boolean value) {#setDigitalSignature-boolean-}
```
public final void setDigitalSignature(boolean value)
```


Returns true if this document contains a digital signature. This property merely informs that a digital signature is present on a document, but it does not specify whether the signature is valid or not.

--------------------

This property exists to help you sort documents that are digitally signed from those that are not. If you use Aspose.Words to modify and save a document that is digitally signed, then the digital signature will be lost. This is by design because a digital signature exists to guard the authenticity of a document. Using this property you can detect digitally signed documents before processing them in the same way as normal documents and take some action to avoid losing the digital signature, for example notify the user.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getEncoding() {#getEncoding--}
```
public final Charset getEncoding()
```


Gets the detected encoding if applicable to the current document format. At the2022-02 the Aspose.Words detects encoding only for HTML documents.

**Returns:**
java.nio.charset.Charset
### setEncoding(Charset value) {#setEncoding-java.nio.charset.Charset-}
```
public final void setEncoding(Charset value)
```


Gets the detected encoding if applicable to the current document format. At the2022-02 the Aspose.Words detects encoding only for HTML documents.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.nio.charset.Charset |  |

