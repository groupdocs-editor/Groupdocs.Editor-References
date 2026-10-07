---
title: "HasInvalidFormFields"
second_title: "Référence API GroupDocs.Editor pour .NET"
description: "Vérifie si le document contient des champs de formulaire invalides."
type: docs
weight: 40
url: /fr/net/groupdocs.editor/formfieldmanager/hasinvalidformfields/
---
## FormFieldManager.HasInvalidFormFields method

Vérifie si le document contient des champs de formulaire invalides.

```csharp
public bool HasInvalidFormFields()
```

### Valeur de retour

`true` si le document contient un ou plusieurs champs de formulaire invalides ; sinon, `false`.

### Remarques

La méthode `HasInvalidFormFields` analyse le contenu du document pour déterminer s'il contient des champs de formulaire avec des noms invalides. Un champ de formulaire est considéré comme invalide s'il duplique un identifiant unique avec d'autres champs de formulaire et n'a pas de nom de signet unique associé. Ces noms de signet servent d'identifiants pour chaque champ de formulaire. Cette méthode est utile pour vérifier rapidement si le document nécessite une inspection supplémentaire et une éventuelle correction des noms de champs de formulaire. ; ; ;

### Voir aussi

* class [FormFieldManager](../../formfieldmanager)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.editor.dll -->
