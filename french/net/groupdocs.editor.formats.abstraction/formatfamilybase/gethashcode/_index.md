---
title: "GetHashCode"
second_title: "Référence API GroupDocs.Editor pour .NET"
description: "Renvoie un code de hachage pour l'objet actuel."
type: docs
weight: 40
url: /fr/net/groupdocs.editor.formats.abstraction/formatfamilybase/gethashcode/
---
## FormatFamilyBase.GetHashCode method

Renvoie un code de hachage pour l'objet actuel.

```csharp
public override int GetHashCode()
```

### Valeur de retour

Un code de hachage pour l'objet actuel, adapté à une utilisation dans les algorithmes de hachage et les structures de données comme une table de hachage.

### Remarques

Cette méthode remplace GetHashCode. Le code de hachage est calculé en utilisant les propriétés `Id` et `Name` de l'objet. Le contexte `unchecked` autorise le dépassement, ce qui est acceptable dans le contexte du calcul d'un code de hachage.

### Voir aussi

* class [FormatFamilyBase](../../formatfamilybase)
* namespace [GroupDocs.Editor.Formats.Abstraction](../../../groupdocs.editor.formats.abstraction)
* assembly [GroupDocs.Editor](../../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.editor.dll -->
