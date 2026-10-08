---
title: "UpdateFormFiled"
second_title: "GroupDocs.Editor för .NET API-referens"
description: "Uppdaterar formulärfält i dokumentet baserat på den tillhandahållna samlingen av formulärfält."
type: docs
weight: 70
url: /sv/net/groupdocs.editor/formfieldmanager/updateformfiled/
---
## FormFieldManager.UpdateFormFiled method

Uppdaterar formulärfält i dokumentet baserat på den tillhandahållna samlingen av formulärfält.

```csharp
public void UpdateFormFiled(FormFieldCollection formFieldCollection)
```

| Parameter | Type | Beskrivning |
| --- | --- | --- |
| formFieldCollection | FormFieldCollection | Samlingen av formulärfält som innehåller uppdateringarna som ska tillämpas på dokumentet. |

### Anmärkningar

Metoden `UpdateFormFiled` uppdaterar formulärfält i dokumentet baserat på den angivna *formFieldCollection*. Varje formulärfält i samlingen motsvarar ett formulärfält i dokumentet, och de uppdateringar som specificerats i samlingen tillämpas därefter. Metoden är användbar för att synkronisera formulärfältsdata mellan dokumentet och en extern källa, såsom ett användargränssnitt eller en databas.

### Se även

* class [FormFieldCollection](../../../groupdocs.editor.words.fieldmanagement/formfieldcollection)
* class [FormFieldManager](../../formfieldmanager)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

<!-- REDIGERA INTE: genererad av xmldocmd för GroupDocs.editor.dll -->
