---
title: "TextEditOptions"
second_title: "GroupDocs.Editor para .NET Referencia de API"
description: "Permite especificar opciones personalizadas para cargar documentos de texto plano TXT."
type: docs
weight: 1150
url: /es/net/groupdocs.editor.options/texteditoptions/
---
## TextEditOptions class

Permite especificar opciones personalizadas para cargar documentos de texto plano (TXT)

```csharp
public class TextEditOptions : IEditOptions
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [TextEditOptions](texteditoptions)() | El constructor predeterminado. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Direction](../../groupdocs.editor.options/texteditoptions/direction) { get; set; } | Permite especificar la dirección del flujo de texto en el documento de texto plano de entrada. Por defecto es de izquierda a derecha. |
| [EnablePagination](../../groupdocs.editor.options/texteditoptions/enablepagination) { get; set; } | Permite habilitar o deshabilitar la paginación en el documento HTML resultante. Por defecto está deshabilitada (false). |
| [Encoding](../../groupdocs.editor.options/texteditoptions/encoding) { get; set; } | Codificación de caracteres del documento de texto, que se aplicará al abrirlo. |
| [LeadingSpaces](../../groupdocs.editor.options/texteditoptions/leadingspaces) { get; set; } | Obtiene o establece la opción preferida para el manejo de espacios iniciales. Por defecto convierte los espacios iniciales en sangría izquierda. |
| [RecognizeLists](../../groupdocs.editor.options/texteditoptions/recognizelists) { get; set; } | Permite especificar cómo se reconocen los elementos de listas numeradas cuando el documento se importa desde formato de texto plano. El valor predeterminado es verdadero. |
| [TrailingSpaces](../../groupdocs.editor.options/texteditoptions/trailingspaces) { get; set; } | Obtiene o establece la opción preferida para el manejo de espacios finales. Por defecto trunca todos los espacios finales. |

### Ver también

* interface [IEditOptions](../ieditoptions)
* namespace [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.editor.dll -->
