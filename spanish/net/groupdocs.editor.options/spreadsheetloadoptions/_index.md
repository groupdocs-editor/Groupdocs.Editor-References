---
title: "SpreadsheetLoadOptions"
second_title: "GroupDocs.Editor para .NET Referencia de API"
description: "Contiene opciones para cargar documentos binarios de Spreadsheet Cells compatibles con Excel, como XLSX, ODS, etc., en la clase Editor"
type: docs
weight: 1120
url: /es/net/groupdocs.editor.options/spreadsheetloadoptions/
---
## SpreadsheetLoadOptions class

Contiene opciones para cargar documentos binarios de Hoja de cálculo (Cells, compatibles con Excel) como XLS(X), ODS, etc., en la clase Editor

```csharp
public sealed class SpreadsheetLoadOptions : ILoadOptions
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [SpreadsheetLoadOptions](spreadsheetloadoptions)() | Constructor predeterminado sin parámetros: todos los parámetros tienen valores por defecto |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [OptimizeMemoryUsage](../../groupdocs.editor.options/spreadsheetloadoptions/optimizememoryusage) { get; set; } | Habilita mecanismos de optimización de memoria durante el procesamiento del documento de entrada, lo que puede degradar el rendimiento en algunos casos especiales, pero por otro lado reduce el uso de memoria. Es útil al procesar documentos enormes y enfrentar OutOfMemoryException. El valor predeterminado es false (la optimización de memoria está deshabilitada para obtener un mejor rendimiento). |
| [Password](../../groupdocs.editor.options/spreadsheetloadoptions/password) { get; set; } | Permite especificar, modificar y obtener la contraseña que se usará para abrir el documento Spreadsheet, si está codificado. Establézcalo en NULL o cadena vacía para no usar la contraseña (valor predeterminado). |

### Ver también

* interface [ILoadOptions](../iloadoptions)
* namespace [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.editor.dll -->
