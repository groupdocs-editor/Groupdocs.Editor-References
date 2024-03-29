---
title: FixedLayoutEditOptionsBase
second_title: GroupDocs.Editor für .NET-API-Referenz
description: Abstrakte Basisklasse für die Optionen für alle Dokumente mit festem Layout wie PDF und XPS
type: docs
weight: 880
url: /de/net/groupdocs.editor.options/fixedlayouteditoptionsbase/
---
## FixedLayoutEditOptionsBase class

Abstrakte Basisklasse für die Optionen für alle Dokumente mit festem Layout wie PDF und XPS

```csharp
public abstract class FixedLayoutEditOptionsBase : IEditOptions
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [EnablePagination](../../groupdocs.editor.options/fixedlayouteditoptionsbase/enablepagination) { get; set; } | Ermöglicht das Aktivieren (true) oder Deaktivieren (false) der Paginierung im resultierenden HTML-Dokument. Standardmäßig ist deaktiviert (false). |
| [Pages](../../groupdocs.editor.options/fixedlayouteditoptionsbase/pages) { get; set; } | Ermöglicht das Festlegen eines zu verarbeitenden Seitenbereichs. Standardmäßig werden alle Seiten eines Dokuments mit festem Layout verarbeitet. |
| [SkipImages](../../groupdocs.editor.options/fixedlayouteditoptionsbase/skipimages) { get; set; } | Ruft das Flag ab oder setzt es, das angibt, ob Bilder übersprungen werden müssen, während das eingegebene Dokument mit festem Layout in das resultierende HTML konvertiert wird. Standard ist „false“ – Bilder bleiben erhalten. |

### Siehe auch

* interface [IEditOptions](../ieditoptions)
* namensraum [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* Montage [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->
