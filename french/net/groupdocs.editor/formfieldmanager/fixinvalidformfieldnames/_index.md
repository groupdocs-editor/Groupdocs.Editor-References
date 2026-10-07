---
title: "FixInvalidFormFieldNames"
second_title: "Référence API GroupDocs.Editor pour .NET"
description: "Corrige les noms de champs de formulaire invalides dans le document en appliquant les mises à jour spécifiées ou en générant automatiquement des noms uniques."
type: docs
weight: 20
url: /fr/net/groupdocs.editor/formfieldmanager/fixinvalidformfieldnames/
---
## FormFieldManager.FixInvalidFormFieldNames method

Corrige les noms de champs de formulaire invalides dans le document en appliquant les mises à jour spécifiées ou en générant automatiquement des noms uniques.

```csharp
public void FixInvalidFormFieldNames(IEnumerable<InvalidFormField> updateInvalidFormFieldNames)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| updateInvalidFormFieldNames | IEnumerable`1 | Une collection de mises à jour pour les noms de champs de formulaire invalides. Chaque mise à jour contient le nom original du champ de formulaire et son nouveau nom correspondant. Si elle est laissée vide, les noms de champs de formulaire invalides seront automatiquement renommés afin d'assurer leur unicité. |

### Remarques

La méthode `FixInvalidFormFieldNames` résout les conflits ou incohérences de nommage au sein des champs de formulaire du document en appliquant les mises à jour spécifiées dans la collection *updateInvalidFormFieldNames*, ou en générant automatiquement des noms uniques si la collection est vide. Cette méthode est utile lorsque certains noms de champs de formulaire sont invalides ou en conflit avec d'autres éléments du document, et doivent être corrigés pour garantir un fonctionnement correct. ; ;

### Voir aussi

* class [InvalidFormField](../../../groupdocs.editor.words.fieldmanagement/invalidformfield)
* class [FormFieldManager](../../formfieldmanager)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.editor.dll -->
