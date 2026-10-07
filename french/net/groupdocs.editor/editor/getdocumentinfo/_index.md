---
title: "GetDocumentInfo"
second_title: "Référence API GroupDocs.Editor pour .NET"
description: "Renvoie les métadonnées du document qui a été chargé dans cette instance d'Editor"
type: docs
weight: 70
url: /fr/net/groupdocs.editor/editor/getdocumentinfo/
---
## Editor.GetDocumentInfo method

Renvoie les métadonnées du document qui a été chargé dans cette instance d'Editor.

```csharp
public IDocumentInfo GetDocumentInfo(string password)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| password | String | L'utilisateur peut spécifier un mot de passe pour un document, si ce document est chiffré avec le mot de passe. Peut être NULL ou une chaîne vide, ce qui équivaut à l'absence de mot de passe. Pour les formats de document qui ne disposent pas de fonction de protection par mot de passe, cet argument sera ignoré. Si le document est chiffré et que le mot de passe n'est pas spécifié dans le paramètre "*password*", mais qu'il a été spécifié auparavant dans les options de chargement lors de la création de cette instance [`Editor`](../../editor), il sera utilisé. |

### Valeur de retour

Héritier spécifique au format de l'interface [`IDocumentInfo`](../../../groupdocs.editor.metadata/idocumentinfo), qui indique le format détecté avec des métadonnées propres au format, ou NULL, si le document n'a pas été reconnu comme pris en charge ou est corrompu.

### Exceptions

| exception | condition |
| --- | --- |
| ObjectDisposedException | Est lancée lorsque l'instance Editor a déjà été libérée lors de l'appel de "GetDocumentInfo" |
| [PasswordRequiredException](../../passwordrequiredexception) | Est lancée lorsque le document chargé est protégé par un mot de passe, mais que le mot de passe n'a pas été spécifié dans le paramètre "*password*" ni dans les options de chargement lors de la création de l'instance |
| [IncorrectPasswordException](../../incorrectpasswordexception) | Est lancée lorsque le document chargé est protégé par un mot de passe, le mot de passe est spécifié, mais est incorrect |
| InvalidOperationException | Est lancée lorsqu'une erreur inattendue d'origine inconnue s'est produite |

### Remarques

La méthode GetDocumentInfo est utile lorsqu'il n'est pas clair quel est le format du document d'entrée, s'il est protégé par un mot de passe et/ou combien de pages/feuilles de calcul/diapositives il contient. En se basant sur ces métadonnées, renvoyées par GetDocumentInfo, il est possible d'ajuster correctement les options de chargement et d'édition pour le pipeline de traitement principal.

La méthode GetDocumentInfo renvoie toujours l'intégralité des données, elle n'est pas affectée par le mode d'essai, son utilisation ne consomme pas les octets ou crédits utilisés.

**Learn more**

* Learn more about obtaining document specific properties in code: [How to get document info using GroupDocs.Editor](https://docs.groupdocs.com/display/editornet/Extracting+document+metainfo)

### Voir aussi

* interface [IDocumentInfo](../../../groupdocs.editor.metadata/idocumentinfo)
* class [Editor](../../editor)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.editor.dll -->
