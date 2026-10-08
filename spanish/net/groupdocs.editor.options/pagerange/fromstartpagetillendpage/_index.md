---
title: "FromStartPageTillEndPage"
second_title: "GroupDocs.Editor para .NET Referencia de API"
description: "Crea un rango de páginas que comienza desde el número de página especificado de forma inclusiva y continúa hasta el número de página especificado de forma exclusiva"
type: docs
weight: 40
url: /es/net/groupdocs.editor.options/pagerange/fromstartpagetillendpage/
---
## PageRange.FromStartPageTillEndPage method

Crea un rango de páginas que comienza desde el número de página especificado (inclusivamente) y continúa hasta el número de página especificado (exclusivamente).

```csharp
public static PageRange FromStartPageTillEndPage(ushort startPageNumber, ushort endPageNumber)
```

| Parameter | Type | Descripción |
| --- | --- | --- |
| startPageNumber | UInt16 | Número de página desde el cual comienza el rango de páginas, inclusivamente. Los números de página son basados en 1, por lo que deben ser estrictamente mayores que cero |
| endPageNumber | UInt16 | Número de página hasta el cual continúa el rango de páginas, exclusivamente. Los números de página son basados en 1, por lo que deben ser estrictamente mayores que cero, y también deben ser estrictamente mayores que *startPageNumber* |

### Ver también

* struct [PageRange](../../pagerange)
* namespace [GroupDocs.Editor.Options](../../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.editor.dll -->
