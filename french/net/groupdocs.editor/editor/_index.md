---
title: "Editor"
second_title: "Référence API GroupDocs.Editor pour .NET"
description: "Classe principale qui encapsule les méthodes de conversion. La classe Editor fournit des méthodes pour charger, modifier et enregistrer des documents de tous les formats pris en charge. Elle est jetable, donc utilisez une directive using ou libérez ses ressources manuellement via l’appel de la méthode `Dispose`. Le chargement du document est effectué via les constructeurs. La modification du document se fait via la méthode `Edit` et l’enregistrement du document résultant après modification se fait via la méthode `Save`."
type: docs
weight: 20
url: /fr/net/groupdocs.editor/editor/
---
## Editor class

Classe principale, qui encapsule les méthodes de conversion. La classe Editor fournit des méthodes de chargement, de modification et d'enregistrement des documents de tous les formats pris en charge. Elle est jetable, donc utilisez une directive 'using' ou libérez ses ressources manuellement via l'appel de la méthode 'Dispose()'. Le chargement du document est effectué via les constructeurs. La modification du document – via la méthode 'Edit' – et l'enregistrement du document résultant après modification – via la méthode 'Save'.

```csharp
public sealed class Editor : IAuxDisposable
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [Editor](editor#constructor)(DocumentFormatBase) | Initialise une nouvelle instance de la classe [`Editor`](../editor) et crée un nouveau document vide basé sur le format spécifié. |
| [Editor](editor#constructor_1)(Stream) | Initialise une nouvelle instance d'Editor avec le document d'entrée spécifié (sous forme de flux). |
| [Editor](editor#constructor_3)(string) | Initialise une nouvelle instance d'Editor avec le document d'entrée spécifié (sous forme de chemin de fichier complet) et les paramètres d'Editor. |
| [Editor](editor#constructor_2)(Stream, ILoadOptions) | Initialise une nouvelle instance d'Editor avec le document d'entrée spécifié (sous forme de flux) avec ses options de chargement. |
| [Editor](editor#constructor_4)(string, ILoadOptions) | Initialise une nouvelle instance d'Editor avec le document d'entrée spécifié (sous forme de chemin de fichier complet) avec ses options de chargement. |

## Propriétés

| Nom | Description |
| --- | --- |
| [FormFieldManager](../../groupdocs.editor/editor/formfieldmanager) { get; } | Fournit l'accès aux fonctionnalités de gestion des champs de formulaire dans le document. |
| [IsDisposed](../../groupdocs.editor/editor/isdisposed) { get; } | Indique si cette instance d'Editor a déjà été libérée et ne peut plus être utilisée (true) ou si elle n'a pas encore été libérée et est donc active (false). |

## Méthodes

| Nom | Description |
| --- | --- |
| [Dispose](../../groupdocs.editor/editor/dispose)() | Libère cette instance d'Editor, afin qu'elle libère toutes les ressources internes et devienne indisponible pour une utilisation ultérieure. |
| [Edit](../../groupdocs.editor/editor/edit#edit)() | Ouvre un document préalablement chargé pour l'édition en utilisant les options par défaut en générant et en renvoyant une instance de la classe '[`EditableDocument`](../editabledocument)', qui, à son tour, contient des méthodes pour produire du balisage HTML et les ressources associées. |
| [Edit](../../groupdocs.editor/editor/edit#edit_1)(IEditOptions) | Ouvre un document préalablement chargé pour l'édition en utilisant des options spécifiques au format en générant et en renvoyant une instance de la classe '[`EditableDocument`](../editabledocument)', qui, à son tour, contient des méthodes pour produire du balisage HTML et les ressources associées. |
| [GetDocumentInfo](../../groupdocs.editor/editor/getdocumentinfo)(string) | Renvoie les métadonnées du document qui a été chargé dans cette instance d'Editor. |
| [Save](../../groupdocs.editor/editor/save#save)(Stream) | Enregistre le contenu du document actuel dans le flux de sortie spécifié. |
| [Save](../../groupdocs.editor/editor/save#save_3)(EditableDocument, string) | Convertit le document édité spécifié, représenté par une instance de '[`EditableDocument`](../editabledocument)', en le document résultant au format déterminé à partir de l'extension du nom de fichier, et enregistre son contenu dans un fichier au chemin spécifié. |
| [Save](../../groupdocs.editor/editor/save#save_1)(Stream, WordProcessingSaveOptions) | Convertit le document original après modification (par exemple, [`FormFieldManager`](./formfieldmanager)), en le document résultant du format spécifié et enregistre son contenu dans le flux fourni. |
| [Save](../../groupdocs.editor/editor/save#save_2)(EditableDocument, Stream, ISaveOptions) | Convertit le document édité spécifié, représenté par une instance de '[`EditableDocument`](../editabledocument)', en le document résultant du format spécifié et enregistre son contenu dans le flux spécifié. |
| [Save](../../groupdocs.editor/editor/save#save_4)(EditableDocument, string, ISaveOptions) | Convertit le document édité spécifié, représenté par une instance de '[`EditableDocument`](../editabledocument)', en le document résultant du format spécifié et enregistre son contenu dans un fichier au chemin spécifié. |

## Événements

| Nom | Description |
| --- | --- |
| event [Disposed](../../groupdocs.editor/editor/disposed) | Événement qui se produit lorsque cette instance d'Editor est libérée avec toutes ses ressources internes. |

### Remarques

La classe Editor doit être considérée comme le point d'entrée et l'objet racine de GroupDocs.Editor. Toutes les opérations sont effectuées à l'aide de cette classe. L'utilisation typique de la classe Editor pour réaliser un pipeline complet d'édition de document est la suivante :

1. Chargez un document dans l'instance d'Editor via son constructeur.
2. Optionnellement, détectez le type de document à l'aide de la méthode [`GetDocumentInfo`](./getdocumentinfo).
3. Ouvrez un document pour l'édition en appelant la méthode [`Edit`](./edit) et en obtenant une instance de la classe [`EditableDocument`](../editabledocument) à partir de celle-ci.
4. Modifiez le contenu d'un document côté client en utilisant n'importe quel éditeur HTML WYSIWYG.
5. Créez une nouvelle instance de [`EditableDocument`](../editabledocument) à partir du contenu du document édité.
6. Enregistrez un document édité dans un format de sortie en appelant la méthode [`Save`](./save).
7. Libération d'une instance de la classe Editor via l'opérateur 'using' ou manuellement.

### Voir aussi

* interface [IAuxDisposable](../../groupdocs.editor.htmlcss.resources/iauxdisposable)
* namespace [GroupDocs.Editor](../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.editor.dll -->
