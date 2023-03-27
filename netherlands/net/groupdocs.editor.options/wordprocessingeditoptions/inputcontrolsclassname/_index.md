---
title: InputControlsClassName
second_title: GroupDocs.Editor voor .NET API-referentie
description: Maakt het mogelijk om een klassenaam te specificeren die wordt geplaatst bij de klasseattributen in elk HTMLelement die een bepaald veld vertegenwoordigt in het tekstverwerkingsdocument. Standaard is NULL  klasseattributen worden niet toegepast.
type: docs
weight: 60
url: /nl/net/groupdocs.editor.options/wordprocessingeditoptions/inputcontrolsclassname/
---
## WordProcessingEditOptions.InputControlsClassName property

Maakt het mogelijk om een klassenaam te specificeren, die wordt geplaatst bij de 'klasse'-attributen in elk HTML-element, die een bepaald veld vertegenwoordigt in het tekstverwerkingsdocument. Standaard is NULL - 'klasse'-attributen worden niet toegepast.

```csharp
public string InputControlsClassName { get; set; }
```

### Opmerkingen

Bijna alle formaten uit de WordProcessing-formaatfamilie bevatten velden — specifieke documententiteiten, waarmee invoergegevens van gebruikers kunnen worden verkregen. Er is een grote verscheidenheid aan velden: tekstvakken, selectievakjes, keuzelijsten met invoervak, vervolgkeuzelijsten, knoppen, datum-/tijdkiezers, enz. Ze zijn allemaal vertaald in de meest geschikte HTML-structuren en -elementen, met behoud van de ingevoerde gebruiker gegevens, indien aanwezig in het invoerdocument. In specifieke use-cases is het alleen nodig om ingevoerde gegevens aan de clientzijde te verzamelen in plaats van de volledige inhoud van het document te bewerken. Voor een dergelijk geval is het vereist om invoerbesturingselementen op de een of andere manier te identificeren om ze op te halen met hun gegevens aan de clientzijde. Met deze eigenschap kan een klassenaam worden opgegeven, die wordt toegepast voor elk invoerbesturingselement in HTML-opmaak, zodat clientcode de HTML-documentstructuur kan doorkruisen en gegevens kan verzamelen.

### Zie ook

* class [WordProcessingEditOptions](../../wordprocessingeditoptions)
* naamruimte [GroupDocs.Editor.Options](../../wordprocessingeditoptions)
* montage [GroupDocs.Editor](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->