---
title: "GetHashCode"
second_title: "GroupDocs.Editor för .NET API-referens"
description: "Returnerar en hashkod för det aktuella objektet."
type: docs
weight: 40
url: /sv/net/groupdocs.editor.formats.abstraction/formatfamilybase/gethashcode/
---
## FormatFamilyBase.GetHashCode method

Returnerar en hashkod för det aktuella objektet.

```csharp
public override int GetHashCode()
```

### Returvärde

En hash‑kod för det aktuella objektet, lämplig för användning i hash‑algoritmer och datastrukturer som en hashtabell.

### Anmärkningar

Denna metod åsidosätter GetHashCode. Hash‑koden beräknas med objektets `Id`‑ och `Name`‑egenskaper. `unchecked`‑kontexten tillåter overflow, vilket är acceptabelt i ett hash‑kodberäkningssammanhang.

### Se även

* class [FormatFamilyBase](../../formatfamilybase)
* namespace [GroupDocs.Editor.Formats.Abstraction](../../../groupdocs.editor.formats.abstraction)
* assembly [GroupDocs.Editor](../../../)

<!-- REDIGERA INTE: genererad av xmldocmd för GroupDocs.editor.dll -->
