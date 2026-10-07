---
title: "GetFormField"
second_title: "Référence API GroupDocs.Editor pour .NET"
description: "Obtient le champ de formulaire avec le nom et le type spécifiés."
type: docs
weight: 40
url: /fr/net/groupdocs.editor.words.fieldmanagement/formfieldcollection/getformfield/
---
## FormFieldCollection.GetFormField&lt;T&gt; method

Obtient le champ de formulaire avec le nom et le type spécifiés.

```csharp
public T GetFormField<T>(string name)
    where T : IFormField
```

| Paramètre | Description |
| --- | --- |
| T | Le type du champ de formulaire. |
| nom | Le nom du champ de formulaire. |

### Valeur de retour

Le champ de formulaire avec le nom et le type spécifiés, s'il est trouvé ; sinon, la valeur par défaut pour le type.

### Voir aussi

* interface [IFormField](../../iformfield)
* class [FormFieldCollection](../../formfieldcollection)
* namespace [GroupDocs.Editor.Words.FieldManagement](../../../groupdocs.editor.words.fieldmanagement)
* assembly [GroupDocs.Editor](../../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.editor.dll -->
