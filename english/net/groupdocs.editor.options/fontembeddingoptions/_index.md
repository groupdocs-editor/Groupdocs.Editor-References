---
title: FontEmbeddingOptions
second_title: GroupDocs.Editor for .NET API Reference
description: Font embedding options controls which font resources should be embedded into the output WordProcessing or PDF document
type: docs
weight: 870
url: /net/groupdocs.editor.options/fontembeddingoptions/
---
## FontEmbeddingOptions enumeration

Font embedding options controls which font resources should be embedded into the output WordProcessing or PDF document

```csharp
public enum FontEmbeddingOptions
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| NotEmbed | `0` | Do not embed any font resource neither from EditableDocument nor from the system. Default value. |
| EmbedAll | `1` | Analize document content from input EditableDocument, find all used fonts and embed them into output WordProcessing or PDF document. In the first place GroupDocs.Editor takes fonts from font resources within EditableDocument. If they are insufficient or missing, then GroupDocs.Editor takes fonts from OS. |
| EmbedWithoutSystem | `2` | Exact to EmbedAll, but exclude those fonts, which are treated by OS as system fonts |

### Remarks

Font embedding options are applied during document saving (from intermediate EditableDocument into output WordProcessing or PDF format), this enum is included as a property in the WordProcessingSaveOptions and PdfSaveOptions, from where it should be used

### See Also

* namespace [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.editor.dll -->
