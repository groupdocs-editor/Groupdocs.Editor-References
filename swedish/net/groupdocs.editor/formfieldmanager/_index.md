---
title: "FormFieldManager"
second_title: "GroupDocs.Editor för .NET API-referens"
description: "Hantera ett formulär med äldre formulärfält. Äldre formulärfält är de fälttyper som fanns i tidigare versioner av Word‑behandling. Legacy‑Forms‑gruppen som blir synlig efter att du klickat på ikonen Legacy Tools innehåller tre typer av formulärfält som du kan infoga i ett dokument: text, kryssruta, rullgardin, datum osv. se mer FormFieldType../groupdocs.editor.words.fieldmanagement/formfieldtype. Varje av dessa formulärfält låter användaren av formuläret välja eller ange information av den typ du anser lämplig."
type: docs
weight: 40
url: /sv/net/groupdocs.editor/formfieldmanager/
---
## FormFieldManager class

Hantera ett formulär med äldre formulärfält. Äldre formulärfält är de fälttyper som fanns i tidigare versioner av Word‑behandling. Legacy‑Forms‑gruppen (synlig efter att du klickat på ikonen Legacy Tools) innehåller tre typer av formulärfält som du kan infoga i ett dokument: text, kryssruta, rullgardin, datum osv., se mer [`FormFieldType`](../../groupdocs.editor.words.fieldmanagement/formfieldtype). Varje av dessa formulärfält låter användaren av formuläret välja eller ange information av den typ du anser lämplig.

```csharp
public sealed class FormFieldManager
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [FormFieldCollection](../../groupdocs.editor/formfieldmanager/formfieldcollection) { get; } | Hämtar samlingen av formulärfält i dokumentet. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [FixInvalidFormFieldNames](../../groupdocs.editor/formfieldmanager/fixinvalidformfieldnames)(IEnumerable&lt;InvalidFormField&gt;) | Fixar ogiltiga formulärfältsnamn i dokumentet genom att tillämpa angivna uppdateringar eller automatiskt generera unika namn. |
| [GetInvalidFormFieldNames](../../groupdocs.editor/formfieldmanager/getinvalidformfieldnames)() | Hämtar en samling av ogiltiga formulärfältsnamn från dokumentet. |
| [HasInvalidFormFields](../../groupdocs.editor/formfieldmanager/hasinvalidformfields)() | Kontrollerar om dokumentet innehåller några ogiltiga formulärfält. |
| [RemoveFormFields](../../groupdocs.editor/formfieldmanager/removeformfields)(IEnumerable&lt;IFormField&gt;) | Tar bort flera formulärfält från dokumentet. |
| [RemoveFormFiled](../../groupdocs.editor/formfieldmanager/removeformfiled)(IFormField) | Tar bort ett specifikt formulärfält från dokumentet. |
| [UpdateFormFiled](../../groupdocs.editor/formfieldmanager/updateformfiled)(FormFieldCollection) | Uppdaterar formulärfält i dokumentet baserat på den tillhandahållna samlingen av formulärfält. |

### Anmärkningar

Klassen [`FormFieldManager`](../formfieldmanager) tillhandahåller funktionalitet för att hantera formulärfält i ett dokument. Den låter användare hämta, uppdatera, fixa, kontrollera ogiltighet och ta bort formulärfält från dokumentet.

### Se även

* namespace [GroupDocs.Editor](../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../)

<!-- REDIGERA INTE: genererad av xmldocmd för GroupDocs.editor.dll -->
