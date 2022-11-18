---
title: Password
second_title: GroupDocs.Editor för .NET API-referens
description: Gör det möjligt att specificera ändra och erhålla lösenordet som kommer att användas för att öppna presentationsdokumentet om det är kodat. Ställ in på NULL eller tom sträng för att ta bort lösenordet.
type: docs
weight: 20
url: /sv/net/groupdocs.editor.options/presentationloadoptions/password/
---
## PresentationLoadOptions.Password property

Gör det möjligt att specificera, ändra och erhålla lösenordet som kommer att användas för att öppna presentationsdokumentet, om det är kodat. Ställ in på NULL eller tom sträng för att ta bort lösenordet.

```csharp
public string Password { get; set; }
```

### Anmärkningar

Som standard har den här egenskapen NULL-värde — lösenordet är inte inställt. Om inmatat presentationsdokument är lösenordsskyddat är lösenordet obligatoriskt och ett undantag kommer att kastas om lösenordet inte anges eller är ogiltigt. Om det inmatade presentationsdokumentet INTE är lösenordsskyddat, men lösenordet är inställt, kommer det att ignoreras.

### Se även

* class [PresentationLoadOptions](../../presentationloadoptions)
* namnutrymme [GroupDocs.Editor.Options](../../presentationloadoptions)
* hopsättning [GroupDocs.Editor](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->