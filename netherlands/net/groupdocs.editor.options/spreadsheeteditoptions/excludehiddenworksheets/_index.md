---
title: ExcludeHiddenWorksheets
second_title: GroupDocs.Editor voor .NET API-referentie
description: Maakt het mogelijk om verborgen werkbladen uit te sluiten in het spreadsheetinvoerdocument zodat ze volledig worden genegeerd. Standaard is false  verborgen werkbladen zijn beschikbaar en worden normaal verwerkt.
type: docs
weight: 20
url: /nl/net/groupdocs.editor.options/spreadsheeteditoptions/excludehiddenworksheets/
---
## SpreadsheetEditOptions.ExcludeHiddenWorksheets property

Maakt het mogelijk om verborgen werkbladen uit te sluiten in het spreadsheet-invoerdocument, zodat ze volledig worden genegeerd. Standaard is false - verborgen werkbladen zijn beschikbaar en worden normaal verwerkt.

```csharp
public bool ExcludeHiddenWorksheets { get; set; }
```

### Opmerkingen

Verschillende binaire spreadsheetformaten (zoals XLSX) ondersteunen het concept van verborgen werkbladen (tabbladen). Document van een dergelijk formaat, als het meer dan één werkblad heeft, kan extra verborgen werkbladen bevatten. Standaard zijn dergelijke verborgen werkbladen beschikbaar voor verwerking, maar met deze optie is het mogelijk ze te negeren, alsof deze verborgen werkbladen afwezig zijn en niet bestaan. Als deze optie is ingeschakeld, kunt u geen verborgen werkblad selecteren met de '[`WorksheetIndex`](../worksheetindex) eigendom.

### Zie ook

* class [SpreadsheetEditOptions](../../spreadsheeteditoptions)
* naamruimte [GroupDocs.Editor.Options](../../spreadsheeteditoptions)
* montage [GroupDocs.Editor](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->