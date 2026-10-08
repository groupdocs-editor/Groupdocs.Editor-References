---
title: "FixInvalidFormFieldNames"
second_title: "GroupDocs.Editor för .NET API-referens"
description: "Fixar ogiltiga formulärfältsnamn i dokumentet genom att tillämpa angivna uppdateringar eller automatiskt generera unika namn."
type: docs
weight: 20
url: /sv/net/groupdocs.editor/formfieldmanager/fixinvalidformfieldnames/
---
## FormFieldManager.FixInvalidFormFieldNames method

Fixar ogiltiga formulärfältsnamn i dokumentet genom att tillämpa angivna uppdateringar eller automatiskt generera unika namn.

```csharp
public void FixInvalidFormFieldNames(IEnumerable<InvalidFormField> updateInvalidFormFieldNames)
```

| Parameter | Type | Beskrivning |
| --- | --- | --- |
| updateInvalidFormFieldNames | IEnumerable`1 | En samling av uppdateringar för ogiltiga formulärfältnamn. Varje uppdatering innehåller det ursprungliga namnet på formulärfältet och dess motsvarande nya namn. Om den lämnas tom kommer ogiltiga formulärfältnamn automatiskt att bytas ut för att säkerställa unikhet. |

### Anmärkningar

Metoden `FixInvalidFormFieldNames` löser namnkonflikter eller inkonsekvenser inom dokumentets formulärfält genom att tillämpa uppdateringar som specificerats i *updateInvalidFormFieldNames*-samlingen, eller automatiskt generera unika namn om samlingen är tom. Metoden är användbar när vissa formulärfältnamn är ogiltiga eller i konflikt med andra element i dokumentet och behöver korrigeras för att säkerställa korrekt funktionalitet. ; ;

### Se även

* class [InvalidFormField](../../../groupdocs.editor.words.fieldmanagement/invalidformfield)
* class [FormFieldManager](../../formfieldmanager)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

<!-- REDIGERA INTE: genererad av xmldocmd för GroupDocs.editor.dll -->
