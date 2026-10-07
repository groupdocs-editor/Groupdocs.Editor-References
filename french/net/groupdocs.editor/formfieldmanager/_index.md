---
title: "FormFieldManager"
second_title: "Référence API GroupDocs.Editor pour .NET"
description: "Gestion d’un formulaire avec les champs de formulaire hérités. Les champs de formulaire hérités sont les types de champs qui étaient disponibles dans les versions antérieures du traitement de texte. Le groupe Legacy Forms, visible après avoir cliqué sur l’icône Legacy Tools, comprend trois types de champs de formulaire que vous pouvez insérer dans un document : texte, case à cocher, liste déroulante, date, etc. voir plus FormFieldType../groupdocs.editor.words.fieldmanagement/formfieldtype. Chacun de ces champs de formulaire permet à l’utilisateur du formulaire de sélectionner ou de saisir des informations du type que vous jugez approprié."
type: docs
weight: 40
url: /fr/net/groupdocs.editor/formfieldmanager/
---
## FormFieldManager class

Gestion d’un formulaire avec les champs de formulaire hérités. Les champs de formulaire hérités sont les types de champs qui étaient disponibles dans les versions antérieures du traitement de texte. Le groupe Legacy Forms (visible après avoir cliqué sur l’icône Legacy Tools) comprend trois types de champs de formulaire que vous pouvez insérer dans un document : texte, case à cocher, liste déroulante, date, etc., voir plus [`FormFieldType`](../../groupdocs.editor.words.fieldmanagement/formfieldtype). Chacun de ces champs de formulaire permet à l’utilisateur du formulaire de sélectionner ou de saisir des informations du type que vous jugez approprié.

```csharp
public sealed class FormFieldManager
```

## Propriétés

| Nom | Description |
| --- | --- |
| [FormFieldCollection](../../groupdocs.editor/formfieldmanager/formfieldcollection) { get; } | Obtient la collection de champs de formulaire dans le document. |

## Méthodes

| Nom | Description |
| --- | --- |
| [FixInvalidFormFieldNames](../../groupdocs.editor/formfieldmanager/fixinvalidformfieldnames)(IEnumerable&lt;InvalidFormField&gt;) | Corrige les noms de champs de formulaire invalides dans le document en appliquant les mises à jour spécifiées ou en générant automatiquement des noms uniques. |
| [GetInvalidFormFieldNames](../../groupdocs.editor/formfieldmanager/getinvalidformfieldnames)() | Récupère une collection de noms de champs de formulaire invalides du document. |
| [HasInvalidFormFields](../../groupdocs.editor/formfieldmanager/hasinvalidformfields)() | Vérifie si le document contient des champs de formulaire invalides. |
| [RemoveFormFields](../../groupdocs.editor/formfieldmanager/removeformfields)(IEnumerable&lt;IFormField&gt;) | Supprime plusieurs champs de formulaire du document. |
| [RemoveFormFiled](../../groupdocs.editor/formfieldmanager/removeformfiled)(IFormField) | Supprime un champ de formulaire spécifique du document. |
| [UpdateFormFiled](../../groupdocs.editor/formfieldmanager/updateformfiled)(FormFieldCollection) | Met à jour les champs de formulaire dans le document en fonction de la collection de champs de formulaire fournie. |

### Remarques

La classe [`FormFieldManager`](../formfieldmanager) fournit des fonctionnalités pour gérer les champs de formulaire dans un document. Elle permet aux utilisateurs d’obtenir, de mettre à jour, de corriger, de vérifier l’invalidité et de supprimer les champs de formulaire du document.

### Voir aussi

* namespace [GroupDocs.Editor](../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.editor.dll -->
