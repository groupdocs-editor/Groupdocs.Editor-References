---
title: "FromStartPageWithCount"
second_title: "GroupDocs.Editor para .NET Referencia de API"
description: "Crea un rango de páginas que comienza desde el número de página especificado y tiene la cantidad de páginas especificada o un recuento ilimitado de páginas hasta el final"
type: docs
weight: 50
url: /es/net/groupdocs.editor.options/pagerange/fromstartpagewithcount/
---
## PageRange.FromStartPageWithCount method

Crea un rango de páginas que comienza desde el número de página especificado y tiene una cantidad especificada de páginas, o un recuento ilimitado de páginas (hasta el final).

```csharp
public static PageRange FromStartPageWithCount(ushort startPageNumber, ushort pageCount)
```

| Parameter | Type | Descripción |
| --- | --- | --- |
| startPageNumber | UInt16 | Número de página desde el cual comienza el rango de páginas, inclusivamente. Los números de página son basados en 1, por lo que deben ser estrictamente mayores que cero |
| pageCount | UInt16 | Número de páginas, debe ser estrictamente mayor que cero. Si es cero, esto significa todas las páginas hasta el final de un documento |

### Valor devuelto

Nueva instancia de PageRange

### Ver también

* struct [PageRange](../../pagerange)
* namespace [GroupDocs.Editor.Options](../../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.editor.dll -->
