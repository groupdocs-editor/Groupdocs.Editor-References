---
title: "Mot de passe"
second_title: "Référence API GroupDocs.Editor pour .NET"
description: "Permet de spécifier, modifier et obtenir le mot de passe qui sera utilisé pour ouvrir le document Presentation s'il est chiffré. Définissez-le sur NULL ou une chaîne vide afin de supprimer le mot de passe."
type: docs
weight: 20
url: /fr/net/groupdocs.editor.options/presentationloadoptions/password/
---
## PresentationLoadOptions.Password property

Permet de spécifier, modifier et obtenir le mot de passe qui sera utilisé pour ouvrir le document Presentation, s'il est chiffré. Définissez-le sur NULL ou une chaîne vide afin de supprimer le mot de passe.

```csharp
public string Password { get; set; }
```

### Remarques

Par défaut, cette propriété a la valeur NULL — le mot de passe n'est pas défini. Si le document Presentation d'entrée est protégé par un mot de passe, celui-ci est obligatoire et une exception sera levée si le mot de passe n'est pas spécifié ou est invalide. Si le document Presentation d'entrée n'est PAS protégé par un mot de passe, mais qu'un mot de passe est défini, il sera ignoré.

### Voir aussi

* class [PresentationLoadOptions](../../presentationloadoptions)
* namespace [GroupDocs.Editor.Options](../../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.editor.dll -->
