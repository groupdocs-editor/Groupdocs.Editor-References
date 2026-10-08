---
title: "Lösenord"
second_title: "GroupDocs.Editor för .NET API-referens"
description: "Tillåter att ange, ändra och hämta lösenordet som kommer att användas för att öppna presentationsdokumentet om det är krypterat. Sätt till NULL eller en tom sträng för att ta bort lösenordet."
type: docs
weight: 20
url: /sv/net/groupdocs.editor.options/presentationloadoptions/password/
---
## PresentationLoadOptions.Password property

Tillåter att ange, ändra och hämta lösenordet som kommer att användas för att öppna Presentation-dokumentet, om det är kodat. Sätt till NULL eller en tom sträng för att ta bort lösenordet.

```csharp
public string Password { get; set; }
```

### Anmärkningar

Som standard har denna egenskap värdet NULL — lösenordet är inte angivet. Om inmatnings‑Presentation‑dokumentet är lösenordsskyddat är lösenordet obligatoriskt och ett undantag kommer att kastas om lösenordet inte anges eller är ogiltigt. Om inmatnings‑Presentation‑dokumentet INTE är lösenordsskyddat, men lösenordet är angivet, kommer det att ignoreras.

### Se även

* class [PresentationLoadOptions](../../presentationloadoptions)
* namespace [GroupDocs.Editor.Options](../../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../../)

<!-- REDIGERA INTE: genererad av xmldocmd för GroupDocs.editor.dll -->
