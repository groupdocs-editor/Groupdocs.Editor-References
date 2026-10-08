---
title: "DocumentFormatBase"
second_title: "GroupDocs.Editor para .NET Referencia de API"
description: "Representa la clase base para formatos de documento que proporciona funcionalidad común para instancias de formato."
type: docs
weight: 50
url: /es/net/groupdocs.editor.formats.abstraction/documentformatbase/
---
## DocumentFormatBase class

Representa la clase base para formatos de documento, proporcionando funcionalidad común para instancias de formato.

```csharp
public abstract class DocumentFormatBase : FormatFamilyBase, IDocumentFormat
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Extension](../../groupdocs.editor.formats.abstraction/documentformatbase/extension) { get; } | Obtiene la extensión de archivo del formato de documento. |
| [FormatFamily](../../groupdocs.editor.formats.abstraction/documentformatbase/formatfamily) { get; } | Obtiene la familia de formato a la que pertenece el formato de documento. |
| [Id](../../groupdocs.editor.formats.abstraction/formatfamilybase/id) { get; } | Obtiene el identificador único de la familia de formato. |
| [Mime](../../groupdocs.editor.formats.abstraction/documentformatbase/mime) { get; } | Obtiene el tipo MIME del formato de documento. |
| [Name](../../groupdocs.editor.formats.abstraction/formatfamilybase/name) { get; } | Obtiene el nombre de la familia de formato. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [Equals](../../groupdocs.editor.formats.abstraction/formatfamilybase/equals)(FormatFamilyBase) | Determina si esta instancia es igual a la instancia [`FormatFamilyBase`](../formatfamilybase) especificada. |
| [Equals](../../groupdocs.editor.formats.abstraction/documentformatbase/equals#equals_1)(IDocumentFormat) | Determina si esta instancia es igual a la instancia [`IDocumentFormat`](../idocumentformat) especificada. |
| override [Equals](../../groupdocs.editor.formats.abstraction/documentformatbase/equals#equals_2)(object) | Determina si esta instancia es igual a la instancia [`DocumentFormatBase`](../documentformatbase) especificada. |
| override [GetHashCode](../../groupdocs.editor.formats.abstraction/documentformatbase/gethashcode)() | Devuelve un código hash para el objeto actual. |
| override [ToString](../../groupdocs.editor.formats.abstraction/formatfamilybase/tostring)() | Devuelve una cadena que representa el objeto actual. |
| static [FromMime&lt;T&gt;](../../groupdocs.editor.formats.abstraction/documentformatbase/frommime)(string) | Recupera una instancia del tipo especificado *T* que tiene el tipo MIME especificado. |
| [implicit operator](../../groupdocs.editor.formats.abstraction/documentformatbase/op_implicit) | Convierte implícitamente una instancia de [`DocumentFormatBase`](../documentformatbase) a una cadena. |

### Ver también

* class [FormatFamilyBase](../formatfamilybase)
* interface [IDocumentFormat](../idocumentformat)
* namespace [GroupDocs.Editor.Formats.Abstraction](../../groupdocs.editor.formats.abstraction)
* assembly [GroupDocs.Editor](../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.editor.dll -->
