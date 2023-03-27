---
title: RecognizeLists
second_title: GroupDocs.Editor voor .NET API-referentie
description: Hiermee kunt u opgeven hoe genummerde lijstitems worden herkend wanneer een document wordt geïmporteerd uit platte tekst. De standaardwaarde is waar.
type: docs
weight: 60
url: /nl/net/groupdocs.editor.options/texteditoptions/recognizelists/
---
## TextEditOptions.RecognizeLists property

Hiermee kunt u opgeven hoe genummerde lijstitems worden herkend wanneer een document wordt geïmporteerd uit platte tekst. De standaardwaarde is waar.

```csharp
public bool RecognizeLists { get; set; }
```

### Opmerkingen

Als deze optie is ingesteld op false, detecteert het lijstherkenningsalgoritme lijstalinea's wanneer lijstnummers eindigen met een punt, haakje rechts of opsommingstekens (zoals "•", "*", "-" of "o"). Als deze optie is ingesteld op true, worden witruimten ook gebruikt als scheidingstekens voor lijstnummers: het lijstherkenningsalgoritme voor nummering in Arabische stijl (1., 1.1.2.) gebruikt zowel witruimten als punttekens (".").

### Zie ook

* class [TextEditOptions](../../texteditoptions)
* naamruimte [GroupDocs.Editor.Options](../../texteditoptions)
* montage [GroupDocs.Editor](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->