---
title: SvgImagesEmbedding
second_title: GroupDocs.Editor for Java API Reference
description: Represents three possible ways how to reference SVG images in HTML document during serialization
type: docs
weight: 15
url: /java/com.groupdocs.editor.htmlcss.serialization/svgimagesembedding/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class SvgImagesEmbedding extends System.Enum
```

Represents three possible ways how to reference SVG images in HTML document during serialization
## Fields

| Field | Description |
| --- | --- |
| [External](#External) | SVG is located as separate file/resource and is referenced in HTML using IMG element with 'src' attribute |
| [EmbeddedInline](#EmbeddedInline) | SVG content is inlined - embedded directly inside HTML markup using SVG elements with sub-elements |
| [EmbeddedBase64](#EmbeddedBase64) | SVG content is embedded inside HTML markup in base64 form, stored inside 'src' attribute in IMG element |
### External {#External}
```
public static final byte External
```


SVG is located as separate file/resource and is referenced in HTML using IMG element with 'src' attribute

### EmbeddedInline {#EmbeddedInline}
```
public static final byte EmbeddedInline
```


SVG content is inlined - embedded directly inside HTML markup using SVG elements with sub-elements

--------------------

https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia\_and\_embedding/Adding\_vector\_graphics\_to\_the\_Web\#how\_to\_include\_svg\_code\_inside\_your\_html

### EmbeddedBase64 {#EmbeddedBase64}
```
public static final byte EmbeddedBase64
```


SVG content is embedded inside HTML markup in base64 form, stored inside 'src' attribute in IMG element

