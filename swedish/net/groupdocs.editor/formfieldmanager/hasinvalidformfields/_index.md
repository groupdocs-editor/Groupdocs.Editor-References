---
title: "HasInvalidFormFields"
second_title: "GroupDocs.Editor för .NET API-referens"
description: "Kontrollerar om dokumentet innehåller några ogiltiga formulärfält."
type: docs
weight: 40
url: /sv/net/groupdocs.editor/formfieldmanager/hasinvalidformfields/
---
## FormFieldManager.HasInvalidFormFields method

Kontrollerar om dokumentet innehåller några ogiltiga formulärfält.

```csharp
public bool HasInvalidFormFields()
```

### Returvärde

`true` om dokumentet innehåller ett eller flera ogiltiga formulärfält; annars `false`.

### Anmärkningar

Metoden `HasInvalidFormFields` skannar dokumentets innehåll för att avgöra om det innehåller några formulärfält med ogiltiga namn. Ett formulärfält anses ogiltigt om det duplicerar en unik identifierare med andra formulärfält och inte har ett unikt bokmärkesnamn kopplat till sig. Dessa bokmärkesnamn fungerar som identifierare för varje formulärfält. Metoden är användbar för att snabbt kontrollera om dokumentet kräver ytterligare granskning och eventuell korrigering av formulärfältnamn. ; ; ;

### Se även

* class [FormFieldManager](../../formfieldmanager)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

<!-- REDIGERA INTE: genererad av xmldocmd för GroupDocs.editor.dll -->
