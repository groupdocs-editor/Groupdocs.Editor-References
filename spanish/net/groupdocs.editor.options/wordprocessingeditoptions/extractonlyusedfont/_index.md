---
title: "ExtractOnlyUsedFont"
second_title: "GroupDocs.Editor para .NET Referencia de API"
description: "Obtiene o establece un valor que indica si solo se extraen los recursos de fuentes que se utilizan en el contenido textual del documento."
type: docs
weight: 40
url: /es/net/groupdocs.editor.options/wordprocessingeditoptions/extractonlyusedfont/
---
## WordProcessingEditOptions.ExtractOnlyUsedFont property

Obtiene o establece un valor que indica si solo se extraen los recursos de fuentes que se utilizan en el contenido textual del documento.

```csharp
public bool ExtractOnlyUsedFont { get; set; }
```

### Property Value

`true` si es necesario extraer solo los recursos de fuentes que se utilizan en el contenido de texto del documento; de lo contrario, `false`. El valor predeterminado es `false`.

### Observaciones

No todas las fuentes utilizadas en el documento WordProcessing se usan al 100 % de forma directa (aplicadas a algún texto). Puede haber una situación en la que la fuente esté referenciada en el documento e incluso esté incrustada, pero no se aplique a ningún fragmento de texto. Por ejemplo, una fuente puede estar asociada a un estilo, pero ese estilo no se aplique a ninguna parte del texto. Esta opción controla cómo procesar esos casos.

### Ver también

* class [WordProcessingEditOptions](../../wordprocessingeditoptions)
* namespace [GroupDocs.Editor.Options](../../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.editor.dll -->
