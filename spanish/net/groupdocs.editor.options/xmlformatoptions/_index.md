---
title: "XmlFormatOptions"
second_title: "GroupDocs.Editor para .NET Referencia de API"
description: "Contiene opciones que permiten ajustar el formato del documento XML cuando se representa como HTML"
type: docs
weight: 1280
url: /es/net/groupdocs.editor.options/xmlformatoptions/
---
## XmlFormatOptions class

Contiene opciones que permiten ajustar el formato del documento XML cuando se representa como HTML

```csharp
public sealed class XmlFormatOptions : IEditOptions
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [EachAttributeFromNewline](../../groupdocs.editor.options/xmlformatoptions/eachattributefromnewline) { get; set; } | Cuando está habilitado, cada par atributo-valor en cada elemento XML se colocará en una nueva línea. Por defecto es falso (deshabilitado) — todos los pares atributo-valor se colocan en una sola línea. |
| [IsDefault](../../groupdocs.editor.options/xmlformatoptions/isdefault) { get; } | Indica si esta instancia de opciones de formato XML tiene un valor predeterminado |
| [LeafTextNodesOnNewline](../../groupdocs.editor.options/xmlformatoptions/leaftextnodesonnewline) { get; set; } | Cuando está habilitado, los nodos de texto hoja (contenido textual dentro de los elementos XML que no tienen hijos) se renderizarán en una nueva línea con una sangría izquierda mayor. Por defecto es falso (deshabilitado) — los nodos de texto hoja se colocan en la misma línea que sus padres, sin nueva sangría. |
| [LeftIndent](../../groupdocs.editor.options/xmlformatoptions/leftindent) { get; set; } | Permite especificar un desplazamiento para la sangría izquierda de cada nueva línea. No puede ser un valor sin unidades distinto de cero. Por defecto es 10pt |

### Ver también

* interface [IEditOptions](../ieditoptions)
* namespace [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.editor.dll -->
