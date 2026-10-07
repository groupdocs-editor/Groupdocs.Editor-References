---
title: "GetInvalidFormFieldNames"
second_title: "Référence API GroupDocs.Editor pour .NET"
description: "Récupère une collection de noms de champs de formulaire invalides du document."
type: docs
weight: 30
url: /fr/net/groupdocs.editor/formfieldmanager/getinvalidformfieldnames/
---
## FormFieldManager.GetInvalidFormFieldNames method

Récupère une collection de noms de champs de formulaire invalides du document.

```csharp
public IEnumerable<InvalidFormField> GetInvalidFormFieldNames()
```

### Valeur de retour

Une collection énumérable de chaînes représentant les noms des champs de formulaire invalides trouvés dans le document.

### Remarques

La méthode `GetInvalidFormFieldNames` analyse le contenu du document pour identifier les champs de formulaire avec des noms invalides. Elle renvoie une collection de chaînes contenant les noms de ces champs de formulaire invalides. Un champ de formulaire est considéré comme invalide s'il duplique un identifiant unique avec d'autres champs de formulaire et n'a pas de nom de signet unique associé. Ces noms de signet servent d'identifiants pour chaque champ de formulaire. La collection renvoyée conserve l'ordre des noms de champs de formulaire tel qu'ils apparaissent dans le document. Cette méthode est utile pour détecter et analyser les problèmes de nommage au sein des champs de formulaire, qui peuvent devoir être résolus en utilisant la méthode [`FixInvalidFormFieldNames`](../fixinvalidformfieldnames).

### Voir aussi

* class [InvalidFormField](../../../groupdocs.editor.words.fieldmanagement/invalidformfield)
* class [FormFieldManager](../../formfieldmanager)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.editor.dll -->
