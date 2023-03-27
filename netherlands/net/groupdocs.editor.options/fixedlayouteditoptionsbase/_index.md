---
title: FixedLayoutEditOptionsBase
second_title: GroupDocs.Editor voor .NET API-referentie
description: Abstracte basisklasse voor de opties voor alle documenten met formaten met een vaste layout zoals PDF en XPS
type: docs
weight: 880
url: /nl/net/groupdocs.editor.options/fixedlayouteditoptionsbase/
---
## FixedLayoutEditOptionsBase class

Abstracte basisklasse voor de opties voor alle documenten met formaten met een vaste lay-out, zoals PDF en XPS

```csharp
public abstract class FixedLayoutEditOptionsBase : IEditOptions
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [EnablePagination](../../groupdocs.editor.options/fixedlayouteditoptionsbase/enablepagination) { get; set; } | Maakt het mogelijk om paginering (true) of deactiveren (false) in het resulterende HTML-document in te schakelen. Standaard is uitgeschakeld (false). |
| [Pages](../../groupdocs.editor.options/fixedlayouteditoptionsbase/pages) { get; set; } | Maakt het mogelijk om een paginabereik in te stellen om te verwerken. Standaard worden alle pagina's van een document met een vaste lay-out verwerkt. |
| [SkipImages](../../groupdocs.editor.options/fixedlayouteditoptionsbase/skipimages) { get; set; } | Haalt of stelt de vlag in die aangeeft of afbeeldingen moeten worden overgeslagen bij het converteren van het ingevoerde document met vaste lay-out naar de resulterende HTML. Standaard is false - afbeeldingen blijven behouden. |

### Zie ook

* interface [IEditOptions](../ieditoptions)
* naamruimte [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* montage [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->