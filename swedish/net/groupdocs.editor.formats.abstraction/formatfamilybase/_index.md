---
title: "FormatFamilyBase"
second_title: "GroupDocs.Editor för .NET API-referens"
description: "Representerar basklassen för formatfamiljer som tillhandahåller gemensam funktionalitet för formatfamiljeinstanser."
type: docs
weight: 60
url: /sv/net/groupdocs.editor.formats.abstraction/formatfamilybase/
---
## FormatFamilyBase class

Representerar basklassen för formatfamiljer och tillhandahåller gemensam funktionalitet för formatfamilje‑instanser.

```csharp
public abstract class FormatFamilyBase : IEquatable<FormatFamilyBase>
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [Id](../../groupdocs.editor.formats.abstraction/formatfamilybase/id) { get; } | Hämtar det unika identifieraren för formatfamiljen. |
| [Name](../../groupdocs.editor.formats.abstraction/formatfamilybase/name) { get; } | Hämtar namnet på formatfamiljen. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [Equals](../../groupdocs.editor.formats.abstraction/formatfamilybase/equals#equals)(FormatFamilyBase) | Bestämmer om denna instans är lika med den angivna [`FormatFamilyBase`](../formatfamilybase)-instansen. |
| override [Equals](../../groupdocs.editor.formats.abstraction/formatfamilybase/equals#equals_1)(object) | Bestämmer om denna instans är lika med den angivna [`FormatFamilyBase`](../formatfamilybase)-instansen. |
| override [GetHashCode](../../groupdocs.editor.formats.abstraction/formatfamilybase/gethashcode)() | Returnerar en hashkod för det aktuella objektet. |
| override [ToString](../../groupdocs.editor.formats.abstraction/formatfamilybase/tostring)() | Returnerar en sträng som representerar det aktuella objektet. |
| static [FromName&lt;T&gt;](../../groupdocs.editor.formats.abstraction/formatfamilybase/fromname)(string) | Hämtar en instans av den angivna typen *T* som har det angivna namnet. |
| static [FromValue&lt;T&gt;](../../groupdocs.editor.formats.abstraction/formatfamilybase/fromvalue)(int) | Hämtar en instans av den angivna typen *T* som har den angivna identifieraren. |
| static [GetAll&lt;T&gt;](../../groupdocs.editor.formats.abstraction/formatfamilybase/getall)() | Hämtar alla instanser av den angivna typen *T* som ärver från [`FormatFamilyBase`](../formatfamilybase). |
| [operator ==](../../groupdocs.editor.formats.abstraction/formatfamilybase/op_equality#op_equality) | Bestämmer om två [`FormatFamilyBase`](../formatfamilybase)-instanser är lika. (2 operatorer) |
| [explicit operator](../../groupdocs.editor.formats.abstraction/formatfamilybase/op_explicit#op_explicit_1) | Konverterar en sträng som representerar ett formatfamiljenamn till ett [`FormatFamilyBase`](../formatfamilybase)-objekt. (2 operatorer) |
| [implicit operator](../../groupdocs.editor.formats.abstraction/formatfamilybase/op_implicit#op_implicit) | Konverterar en [`FormatFamilyBase`](../formatfamilybase)-instans till ett heltal implicit. (2 operatorer) |
| [operator !=](../../groupdocs.editor.formats.abstraction/formatfamilybase/op_inequality#op_inequality) | Bestämmer om två [`FormatFamilyBase`](../formatfamilybase)-instanser inte är lika. (2 operatorer) |

### Anmärkningar

Denna klass är abstrakt och måste ärvas av en avledd klass som specificerar de faktiska formatfamiljedetaljerna.

### Se även

* namespace [GroupDocs.Editor.Formats.Abstraction](../../groupdocs.editor.formats.abstraction)
* assembly [GroupDocs.Editor](../../)

<!-- REDIGERA INTE: genererad av xmldocmd för GroupDocs.editor.dll -->
