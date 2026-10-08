---
title: "LocaleId"
second_title: "GroupDocs.Editor för .NET API-referens"
description: "Hämtar eller anger locale‑ID för formulärfältet som representerar kultur‑ eller regioninställningarna som är kopplade till formulärfältet."
type: docs
weight: 30
url: /sv/net/groupdocs.editor.words.fieldmanagement/checkboxform/localeid/
---
## CheckBoxForm.LocaleId property

Hämtar eller anger lokal-ID för formulärfältet, vilket representerar kultur- eller regioninställningarna som är associerade med formulärfältet.

```csharp
public int LocaleId { get; set; }
```

### Anmärkningar

Egenskapen LocaleId specificerar en locale‑identifierare (LCID) som motsvarar en viss kultur eller region.

### Exempel

Följande exempel visar hur man sätter egenskapen LocaleId:

```csharp
Set the LocaleId to represent the English (United States) culture
checkBoxField.LocaleId = new CultureInfo("en-US").LCID;
```

### Se även

* class [CheckBoxForm](../../checkboxform)
* namespace [GroupDocs.Editor.Words.FieldManagement](../../../groupdocs.editor.words.fieldmanagement)
* assembly [GroupDocs.Editor](../../../)

<!-- REDIGERA INTE: genererad av xmldocmd för GroupDocs.editor.dll -->
