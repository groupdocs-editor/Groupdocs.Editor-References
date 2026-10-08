---
title: "DelimitedTextEditOptions"
second_title: "GroupDocs.Editor para .NET Referencia de API"
description: "Opciones para cargar documentos de Spreadsheet basados en texto, como CSV, basados en tabulaciones, etc., que utilizan un delimitador separador"
type: docs
weight: 810
url: /es/net/groupdocs.editor.options/delimitedtexteditoptions/
---
## DelimitedTextEditOptions class

Opciones para cargar documentos de hoja de cálculo basados en texto (CSV, basados en tabulaciones, etc.), que utilizan un separador (delimitador)

```csharp
public sealed class DelimitedTextEditOptions : IEditOptions
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [DelimitedTextEditOptions](delimitedtexteditoptions)(string) | Crea una instancia de la clase de opciones para texto delimitado con un separador (delimitador) obligatorio |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [ConvertDateTimeData](../../groupdocs.editor.options/delimitedtexteditoptions/convertdatetimedata) { get; set; } | Obtiene o establece un valor que indica si la cadena en el documento basado en texto se convierte en datos de fecha. El valor predeterminado es `false`. |
| [ConvertNumericData](../../groupdocs.editor.options/delimitedtexteditoptions/convertnumericdata) { get; set; } | Obtiene o establece un valor que indica si la cadena en el documento basado en texto se convierte en datos numéricos. El valor predeterminado es `false`. |
| [OptimizeMemoryUsage](../../groupdocs.editor.options/delimitedtexteditoptions/optimizememoryusage) { get; set; } | Habilita mecanismos de optimización de memoria durante el procesamiento del documento de entrada, lo que puede degradar el rendimiento en algunos casos especiales, pero por otro lado reduce el uso de memoria. Es útil al procesar documentos enormes y enfrentar OutOfMemoryException. El valor predeterminado es `false` (la optimización de memoria está deshabilitada para obtener un mejor rendimiento). |
| [Separator](../../groupdocs.editor.options/delimitedtexteditoptions/separator) { get; set; } | Permite especificar un separador (delimitador) de cadena para documentos de hoja de cálculo basados en texto |
| [TreatConsecutiveDelimitersAsOne](../../groupdocs.editor.options/delimitedtexteditoptions/treatconsecutivedelimitersasone) { get; set; } | Define si los delimitadores consecutivos deben tratarse como uno solo. Por defecto es `false`. |

### Observaciones

https://en.wikipedia.org/wiki/Delimiter-separated_values

### Ver también

* interface [IEditOptions](../ieditoptions)
* namespace [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.editor.dll -->
