---
title: "FontEmbeddingOptions"
second_title: "GroupDocs.Editor para .NET Referencia de API"
description: "Las opciones de incrustación de fuentes controlan qué recursos de fuentes deben incrustarse en el documento de salida de procesamiento de texto o PDF"
type: docs
weight: 880
url: /es/net/groupdocs.editor.options/fontembeddingoptions/
---
## FontEmbeddingOptions enumeration

Las opciones de incrustación de fuentes controlan qué recursos de fuentes deben incrustarse en el documento de salida de procesamiento de texto o PDF

```csharp
public enum FontEmbeddingOptions
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| NotEmbed | `0` | No incruste ningún recurso de fuente ni de EditableDocument ni del sistema. Valor predeterminado. |
| EmbedAll | `1` | Analiza el contenido del documento del EditableDocument de entrada, encuentra todas las fuentes usadas y las incrusta en el documento de salida WordProcessing o PDF. En primer lugar, GroupDocs.Editor toma las fuentes de los recursos de fuentes dentro del EditableDocument. Si son insuficientes o faltan, entonces GroupDocs.Editor toma las fuentes del SO. |
| EmbedWithoutSystem | `2` | Exacto a EmbedAll, pero excluye aquellas fuentes que el SO trata como fuentes del sistema. |

### Observaciones

Las opciones de incrustación de fuentes se aplican durante el guardado del documento (desde el EditableDocument intermedio al formato de salida WordProcessing o PDF), este enum se incluye como una propiedad en WordProcessingSaveOptions y PdfSaveOptions, desde donde debe usarse.

### Ver también

* namespace [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.editor.dll -->
