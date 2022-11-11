---
title: Editor
second_title: Référence de l'API GroupDocs.Editor pour .NET
description: Classe principale qui encapsule les méthodes de conversion. La classe Editor fournit des méthodes pour charger modifier et enregistrer des documents de tous les formats pris en charge. Il est jetable utilisez donc une directive using ou supprimez ses ressources manuellement via lappel de méthode Dispose. Le chargement des documents est effectué via des constructeurs. Modification du document  via la méthode Modifier et enregistrement dans le document résultant après modification  via la méthode Enregistrer.
type: docs
weight: 20
url: /fr/net/groupdocs.editor/editor/
---
## Editor class

Classe principale, qui encapsule les méthodes de conversion. La classe Editor fournit des méthodes pour charger, modifier et enregistrer des documents de tous les formats pris en charge. Il est jetable, utilisez donc une directive 'using' ou supprimez ses ressources manuellement via l'appel de méthode 'Dispose()'. Le chargement des documents est effectué via des constructeurs. Modification du document - via la méthode "Modifier" et enregistrement dans le document résultant après modification - via la méthode "Enregistrer".

```csharp
public sealed class Editor : IAuxDisposable
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [Editor](editor#constructor)(Func&lt;Stream&gt;) | Initialise la nouvelle instance de l'éditeur avec le document d'entrée spécifié (sous forme de flux) |
| [Editor](editor#constructor_2)(string) | Initialise la nouvelle instance de l'éditeur avec le document d'entrée spécifié (en tant que chemin de fichier complet) |
| [Editor](editor#constructor_1)(Func&lt;Stream&gt;, Func&lt;ILoadOptions&gt;) | Initialise la nouvelle instance de l'éditeur avec le document d'entrée spécifié (sous forme de flux) avec ses options de chargement |
| [Editor](editor#constructor_3)(string, Func&lt;ILoadOptions&gt;) | Initialise la nouvelle instance de l'éditeur avec le document d'entrée spécifié (en tant que chemin de fichier complet) avec ses options de chargement |

## Propriétés

| Nom | La description |
| --- | --- |
| [IsDisposed](../../groupdocs.editor/editor/isdisposed) { get; } | Indique si cette instance de l'éditeur a déjà été supprimée et ne peut plus être utilisée (true) ou si elle n'a pas encore été supprimée et est donc active (false) |

## Méthodes

| Nom | La description |
| --- | --- |
| [Dispose](../../groupdocs.editor/editor/dispose)() | Supprime cette instance d'Editor, afin qu'elle libère toutes les ressources internes et devienne indisponible pour une utilisation ultérieure |
| [Edit](../../groupdocs.editor/editor/edit#edit)() | Ouvre un document précédemment chargé pour le modifier à l'aide des options par défaut en générant et renvoyant une instance de '[`EditableDocument`](../editabledocument) classe, qui, à son tour, contient des méthodes pour produire le balisage HTML et les ressources associées. |
| [Edit](../../groupdocs.editor/editor/edit#edit_1)(IEditOptions) | Ouvre un document précédemment chargé pour modification à l'aide d'options spécifiques au format spécifiées en générant et renvoyant une instance de '[`EditableDocument`](../editabledocument) classe, qui, à son tour, contient des méthodes pour produire le balisage HTML et les ressources associées. |
| [GetDocumentInfo](../../groupdocs.editor/editor/getdocumentinfo)(string) | Renvoie les métadonnées sur le document, qui a été chargée dans cette instance 'Editor' |
| [Save](../../groupdocs.editor/editor/save#save)(EditableDocument, Stream, ISaveOptions) | Convertit le document modifié spécifié, représenté comme une instance de '[`EditableDocument`](../editabledocument) , au document résultant du format spécifié et enregistre son contenu dans le stream spécifié |
| [Save](../../groupdocs.editor/editor/save#save_1)(EditableDocument, string, ISaveOptions) | Convertit le document modifié spécifié, représenté comme une instance de '[`EditableDocument`](../editabledocument) , au document résultant du format spécifié et enregistre son contenu dans le fichier par chemin de fichier spécifié |

## Événements

| Nom | La description |
| --- | --- |
| event [Disposed](../../groupdocs.editor/editor/disposed) | Événement, qui se produit lorsque cette instance de l'éditeur est supprimée avec toutes ses ressources internes |

### Remarques

La classe Editor doit être considérée comme un point d'entrée et l'objet racine de GroupDocs.Editor. Toutes les opérations sont effectuées à l'aide de cette classe. L'utilisation typique de la classe Editor pour effectuer un pipeline d'édition de document complet est la suivante :

1. Chargez un document dans l'instance de l'éditeur via son constructeur.
2. En option, détectez un type de document à l'aide d'un[`GetDocumentInfo`](./getdocumentinfo) méthode.
3. Ouvrez un document pour le modifier en appelant un[`Edit`](./edit) méthode et obtenir une instance de[`EditableDocument`](../editabledocument) classe de celui-ci.
4. Modification du contenu d'un document côté client à l'aide de n'importe quel éditeur HTML WYSIWYG.
5. Création d'une nouvelle instance de[`EditableDocument`](../editabledocument) à partir du contenu du document modifié.
6. Enregistrer un document édité dans un format de sortie en appelant un[`Save`](./save) méthode.
7. Disposer d'une instance de la classe Editor via l'opérateur 'using' ou manuellement.

### Voir également

* interface [IAuxDisposable](../../groupdocs.editor.htmlcss.resources/iauxdisposable)
* espace de noms [GroupDocs.Editor](../../groupdocs.editor)
* Assemblée [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->
