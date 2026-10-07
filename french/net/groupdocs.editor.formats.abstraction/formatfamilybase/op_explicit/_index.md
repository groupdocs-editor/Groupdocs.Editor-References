---
title: "op_Explicit"
second_title: "Référence API GroupDocs.Editor pour .NET"
description: "Convertit une chaîne représentant un nom de famille de format en un objet FormatFamilyBasegroupdocs.editor.formats.abstraction/formatfamilybase."
type: docs
weight: 100
url: /fr/net/groupdocs.editor.formats.abstraction/formatfamilybase/op_explicit/
---
## explicit operator {#op_explicit_1}

Convertit une chaîne représentant un nom de famille de format en un objet [`FormatFamilyBase`](../../formatfamilybase).

```csharp
public static explicit operator FormatFamilyBase(string family)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| famille | String | Le nom de la famille de format à convertir. |

### Valeur de retour

Un objet [`FormatFamilyBase`](../../formatfamilybase) correspondant au nom de famille de format spécifié.

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | Lancée lorsque le nom de famille de format spécifié est invalide. |

### Voir aussi

* class [FormatFamilyBase](../../formatfamilybase)
* namespace [GroupDocs.Editor.Formats.Abstraction](../../../groupdocs.editor.formats.abstraction)
* assembly [GroupDocs.Editor](../../../)

---

## explicit operator {#op_explicit}

Convertit un entier représentant un ID de famille de format en un objet [`FormatFamilyBase`](../../formatfamilybase).

```csharp
public static explicit operator FormatFamilyBase(int id)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| id | Int32 | L’ID de la famille de format à convertir. |

### Valeur de retour

Un objet [`FormatFamilyBase`](../../formatfamilybase) correspondant à l’ID de famille de format spécifié.

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | Lancée lorsque l’ID de famille de format spécifié est invalide. |

### Voir aussi

* class [FormatFamilyBase](../../formatfamilybase)
* namespace [GroupDocs.Editor.Formats.Abstraction](../../../groupdocs.editor.formats.abstraction)
* assembly [GroupDocs.Editor](../../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.editor.dll -->
