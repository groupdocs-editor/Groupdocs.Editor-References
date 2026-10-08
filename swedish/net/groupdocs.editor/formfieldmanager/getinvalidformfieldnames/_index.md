---
title: "GetInvalidFormFieldNames"
second_title: "GroupDocs.Editor för .NET API-referens"
description: "Hämtar en samling av ogiltiga formulärfältsnamn från dokumentet."
type: docs
weight: 30
url: /sv/net/groupdocs.editor/formfieldmanager/getinvalidformfieldnames/
---
## FormFieldManager.GetInvalidFormFieldNames method

Hämtar en samling av ogiltiga formulärfältsnamn från dokumentet.

```csharp
public IEnumerable<InvalidFormField> GetInvalidFormFieldNames()
```

### Returvärde

En uppräkningsbar samling av strängar som representerar namnen på ogiltiga formulärfält som hittats i dokumentet.

### Anmärkningar

Metoden `GetInvalidFormFieldNames` skannar dokumentets innehåll för att identifiera formulärfält med ogiltiga namn. Den returnerar en samling av strängar som innehåller namnen på dessa ogiltiga formulärfält. Ett formulärfält anses vara ogiltigt om det duplicerar en unik identifierare med andra formulärfält och inte har ett unikt bokmärkesnamn kopplat till sig. Dessa bokmärkesnamn fungerar som identifierare för varje formulärfält. Den returnerade samlingen behåller ordningen på formulärfältnamnen som de förekommer i dokumentet. Metoden är användbar för att upptäcka och analysera namngivningsproblem inom formulärfält, vilka kan behöva åtgärdas med hjälp av metoden [`FixInvalidFormFieldNames`](../fixinvalidformfieldnames).

### Se även

* class [InvalidFormField](../../../groupdocs.editor.words.fieldmanagement/invalidformfield)
* class [FormFieldManager](../../formfieldmanager)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

<!-- REDIGERA INTE: genererad av xmldocmd för GroupDocs.editor.dll -->
