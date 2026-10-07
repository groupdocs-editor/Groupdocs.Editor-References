---
title: "DelimitedTextSaveOptions"
second_title: "Référence API GroupDocs.Editor pour .NET"
description: "Ce constructeur sans paramètres crée une nouvelle instance de DelimitedTextSaveOptions avec un point-virgule comme séparateur par défaut ; il peut ensuite être modifié via la propriété Separatorgroupdocs.editor.options/delimitedtextsaveoptions/separator."
type: docs
weight: 10
url: /fr/net/groupdocs.editor.options/delimitedtextsaveoptions/delimitedtextsaveoptions/
---
## DelimitedTextSaveOptions() {#constructor}

Ce constructeur sans paramètres crée une nouvelle instance de DelimitedTextSaveOptions avec un point-virgule (;) comme séparateur par défaut (peut être modifié ensuite via la propriété [`Separator`](../separator)).

```csharp
public DelimitedTextSaveOptions()
```

### Voir aussi

* class [DelimitedTextSaveOptions](../../delimitedtextsaveoptions)
* namespace [GroupDocs.Editor.Options](../../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../../)

---

## DelimitedTextSaveOptions(string) {#constructor_1}

Crée une instance de la classe d'options pour le texte délimité avec un séparateur obligatoire (délimiteur)

```csharp
public DelimitedTextSaveOptions(string separator)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| separator | String | Séparateur de chaîne (délimiteur), qui ne peut pas être NULL ou vide. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | Est levée lorsque le séparateur spécifié est nul ou une chaîne vide. |

### Voir aussi

* class [DelimitedTextSaveOptions](../../delimitedtextsaveoptions)
* namespace [GroupDocs.Editor.Options](../../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.editor.dll -->
