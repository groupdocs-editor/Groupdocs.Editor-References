---
title: "PageRange"
second_title: "GroupDocs.Editor para .NET Referencia de API"
description: "Encapsula un rango de páginas que puede tener límites abiertos o cerrados. Por defecto está completamente abierto e incluye todas las páginas existentes. La numeración de páginas comienza en 1, no en 0."
type: docs
weight: 1030
url: /es/net/groupdocs.editor.options/pagerange/
---
## PageRange structure

Encapsula un rango de páginas, que puede tener límites abiertos o cerrados. Por defecto es "totalmente abierto" - incluye todas las páginas existentes. La numeración de páginas comienza en 1, no en 0.

```csharp
public struct PageRange : IEquatable<PageRange>
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Count](../../groupdocs.editor.options/pagerange/count) { get; } | Número de páginas dentro del rango. Si es 0, el rango de páginas se extiende hasta el final del documento sin importar cuántas páginas contiene. |
| [EndNumber](../../groupdocs.editor.options/pagerange/endnumber) { get; } | Número de página final exclusivo, hasta donde continúa este rango de páginas y donde se detiene de forma exclusiva. Si es 0, el rango de páginas se extiende hasta el final del documento. |
| [IsDefault](../../groupdocs.editor.options/pagerange/isdefault) { get; } | Indica si esta instancia representa un rango de páginas predeterminado "totalmente abierto", es decir, representa todas las páginas de un documento (true) o no (false). |
| [StartNumber](../../groupdocs.editor.options/pagerange/startnumber) { get; } | Número de página inicial inclusivo, desde el cual comienza este rango de páginas. Si es 1, el rango de páginas comienza en la primera página del documento. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| static [FromBeginningWithCount](../../groupdocs.editor.options/pagerange/frombeginningwithcount)(ushort) | Crea un rango de páginas que comienza desde la primera página y tiene una cantidad especificada de páginas. |
| static [FromStartPageTillEnd](../../groupdocs.editor.options/pagerange/fromstartpagetillend)(ushort) | Crea un rango de páginas que comienza desde el número de página especificado y continúa hasta el final del documento. |
| static [FromStartPageTillEndPage](../../groupdocs.editor.options/pagerange/fromstartpagetillendpage)(ushort, ushort) | Crea un rango de páginas que comienza desde el número de página especificado (inclusivamente) y continúa hasta el número de página especificado (exclusivamente). |
| static [FromStartPageWithCount](../../groupdocs.editor.options/pagerange/fromstartpagewithcount)(ushort, ushort) | Crea un rango de páginas que comienza desde el número de página especificado y tiene una cantidad especificada de páginas, o un recuento ilimitado de páginas (hasta el final). |
| [Equals](../../groupdocs.editor.options/pagerange/equals#equals)(PageRange) | Detecta si esta instancia de PageRange es igual a la especificada. |

## Campos

| Nombre | Descripción |
| --- | --- |
| static readonly [AllPages](../../groupdocs.editor.options/pagerange/allpages) | Representa todas las páginas existentes de un documento. Valor predeterminado. |

### Observaciones

Estructura inmutable que encapsula un rango de páginas, que no está relacionado con ningún documento específico, y puede representar un rango de páginas para cualquier documento.

### Ver también

* namespace [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.editor.dll -->
