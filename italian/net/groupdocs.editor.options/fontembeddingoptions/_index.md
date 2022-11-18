---
title: FontEmbeddingOptions
second_title: GroupDocs.Editor per Riferimento API .NET
description: Le opzioni di incorporamento dei caratteri controllano quali risorse dei caratteri devono essere incorporate nel documento WordProcessing o PDF di output
type: docs
weight: 740
url: /it/net/groupdocs.editor.options/fontembeddingoptions/
---
## FontEmbeddingOptions enumeration

Le opzioni di incorporamento dei caratteri controllano quali risorse dei caratteri devono essere incorporate nel documento WordProcessing o PDF di output

```csharp
public enum FontEmbeddingOptions : byte
```

### I valori

| Nome | Valore | Descrizione |
| --- | --- | --- |
| NotEmbed | `0` | Non incorpora alcuna risorsa font né da EditableDocument né dal sistema. Valore predefinito. |
| EmbedAll | `1` | Analizza il contenuto del documento dall'input EditableDocument, trova tutti i font utilizzati e incorporali nel documento WordProcessing o PDF di output. In primo luogo GroupDocs.Editor prende i font dalle risorse dei font all'interno di EditableDocument. Se sono insufficienti o mancanti, GroupDocs.Editor prende i caratteri dal sistema operativo. |
| EmbedWithoutSystem | `2` | Esatto aEmbedAll , ma escludi quei caratteri, che vengono trattati dal sistema operativo come caratteri di sistema |

### Osservazioni

Le opzioni di incorporamento dei caratteri vengono applicate durante il salvataggio del documento (da EditableDocument intermedio al formato WordProcessing o PDF di output), questo enum è incluso come proprietà in WordProcessingSaveOptions e PdfSaveOptions, da dove dovrebbe essere utilizzato

### Guarda anche

* spazio dei nomi [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* assemblea [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->