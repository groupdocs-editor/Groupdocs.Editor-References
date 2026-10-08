---
title: "IDocumentInfo"
second_title: "GroupDocs.Editor para .NET Referencia de API"
description: "Interfaz común para todos los envoltorios de metadatos de archivos"
type: docs
weight: 740
url: /es/net/groupdocs.editor.metadata/idocumentinfo/
---
## IDocumentInfo interface

Interfaz común para todos los envoltorios de metadatos de archivos

```csharp
public interface IDocumentInfo
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Format](../../groupdocs.editor.metadata/idocumentinfo/format) { get; } | En el tipo de implementación debe devolver un formato de documento como un único valor de un tipo, que represente una familia de formatos y herede de la interfaz IDocumentFormat |
| [IsEncrypted](../../groupdocs.editor.metadata/idocumentinfo/isencrypted) { get; } | Indica si un archivo específico está cifrado y requiere contraseña para abrirse. Para los tipos de documento que no pueden ser cifrados (como todos los basados en texto) siempre debe devolver 'false'. |
| [PageCount](../../groupdocs.editor.metadata/idocumentinfo/pagecount) { get; } | En el tipo de implementación debe devolver el recuento (número) de páginas u otras entidades similares dependientes del formato (pestañas, diapositivas, etc.). Para esas familias de tipos que no tienen algo similar (como documentos de texto plano o XML) debe devolver 1. |
| [Size](../../groupdocs.editor.metadata/idocumentinfo/size) { get; } | Tamaño del documento en bytes |

### Ver también

* namespace [GroupDocs.Editor.Metadata](../../groupdocs.editor.metadata)
* assembly [GroupDocs.Editor](../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.editor.dll -->
