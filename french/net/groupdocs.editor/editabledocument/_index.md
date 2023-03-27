---
title: EditableDocument
second_title: Référence de l'API GroupDocs.Editor pour .NET
description: Document intermédiaire qui contient du contenu avant et après lédition
type: docs
weight: 10
url: /fr/net/groupdocs.editor/editabledocument/
---
## EditableDocument class

Document intermédiaire, qui contient du contenu avant et après l'édition

```csharp
public sealed class EditableDocument : IAuxDisposable
```

## Propriétés

| Nom | La description |
| --- | --- |
| [AllResources](../../groupdocs.editor/editabledocument/allresources) { get; } | Renvoie une liste de toutes les ressources existantes : toutes les feuilles de style, images HTML et toutes les feuilles de style, polices, audio |
| [Audio](../../groupdocs.editor/editabledocument/audio) { get; } | Renvoie une liste de ressources audio |
| [Css](../../groupdocs.editor/editabledocument/css) { get; } | Renvoie une liste de ressources CSS |
| [Fonts](../../groupdocs.editor/editabledocument/fonts) { get; } | Permet d'obtenir des ressources de polices externes, qui sont utilisées par ce document HTML |
| [Images](../../groupdocs.editor/editabledocument/images) { get; } | Permet d'obtenir des ressources d'images externes (images raster et vectorielles), qui sont utilisées par ce document HTML |
| [IsDisposed](../../groupdocs.editor/editabledocument/isdisposed) { get; } | Détermine si ce document modifiable a déjà été supprimé (true) ou non (false) |

## Méthodes

| Nom | La description |
| --- | --- |
| static [FromFile](../../groupdocs.editor/editabledocument/fromfile)(string, string) | Usine statique, qui crée une instance de EditableDocument à partir d'un fichier HTML, qui est spécifié par un chemin vers le fichier *.html lui-même et un dossier avec des ressources liées |
| static [FromMarkup](../../groupdocs.editor/editabledocument/frommarkup)(string, IEnumerable&lt;IHtmlResource&gt;) | Usine statique, qui crée une instance de EditableDocument à partir du balisage HTML spécifié et d'un ensemble de ressources liées correspondantes |
| static [FromMarkupAndResourceFolder](../../groupdocs.editor/editabledocument/frommarkupandresourcefolder)(string, string) | Usine statique, qui crée une instance de EditableDocument à partir d'un balisage HTML spécifié et de ressources, situées dans le dossier, spécifié par le chemin complet |
| [Dispose](../../groupdocs.editor/editabledocument/dispose)() | Supprime cette instance de document modifiable, supprimant son contenu et rendant ses méthodes et propriétés non fonctionnelles |
| [GetBodyContent](../../groupdocs.editor/editabledocument/getbodycontent#getbodycontent)() | Renvoie un corps du document HTML (contenu interne entre les balises BODY d'ouverture et de fermeture sans ces balises) sous forme de chaîne. |
| [GetBodyContent](../../groupdocs.editor/editabledocument/getbodycontent#getbodycontent_1)(string) | Renvoie un corps du document HTML (contenu interne entre les balises BODY d'ouverture et de fermeture sans ces balises) sous forme de chaîne, où les liens vers les ressources externes contiennent le préfixe spécifié. |
| [GetContent](../../groupdocs.editor/editabledocument/getcontent#getcontent)() | Renvoie le contenu global du document HTML sous forme de chaîne. |
| [GetContent](../../groupdocs.editor/editabledocument/getcontent#getcontent_1)(string, string) | Renvoie le contenu global du document HTML sous forme de chaîne, où les liens vers les ressources externes contiennent le préfixe spécifié. |
| [GetCssContent](../../groupdocs.editor/editabledocument/getcsscontent#getcsscontent)() | Renvoie le contenu de toutes les feuilles de style externes sous forme de liste de chaînes, où une chaîne représente une feuille de style. Renvoie une liste vide, s'il n'y a pas de CSS pour ce document. |
| [GetCssContent](../../groupdocs.editor/editabledocument/getcsscontent#getcsscontent_1)(string, string) | Renvoie le contenu de toutes les feuilles de style externes sous forme de liste de chaînes, où une chaîne représente une feuille de style. Le préfixe spécifié sera appliqué à chaque lien vers la ressource externe dans chaque feuille de style résultante. Renvoie une liste vide, s'il n'y a pas de CSS pour cela document. |
| [GetEmbeddedHtml](../../groupdocs.editor/editabledocument/getembeddedhtml)() | Renvoie tout le contenu de ce document HTML avec toutes les ressources associées sous la forme d'une chaîne unique, où toutes les ressources sont intégrées à l'intérieur du balisage HTML sous une forme encodée en base64. |
| [Save](../../groupdocs.editor/editabledocument/save#save)(string) | Enregistre ce document HTML dans le fichier sur le chemin spécifié, où le balisage HTML sera stocké, et dans le dossier d'accompagnement avec les ressources. |
| [Save](../../groupdocs.editor/editabledocument/save#save_1)(string, string) | Enregistre ce document HTML dans le fichier sur le chemin spécifié, où le balisage HTML sera stocké, et dans le dossier d'accompagnement avec les ressources, qui se trouve sur le chemin spécifié. |

## Événements

| Nom | La description |
| --- | --- |
| event [Disposed](../../groupdocs.editor/editabledocument/disposed) | Événement, qui se produit lorsque ce document modifiable est supprimé, juste après la fin du processus de suppression |

### Remarques

Une instance de la classe EditableDocument peut être produite par le '[`Edit`](../editor/edit) ou créé par l'utilisateur lui-même à l'aide de fabriques statiques. EditableDocument stocke en interne le document dans son propre format fermé, qui est compatible (convertible) avec tous les formats d'importation et d'exportation, pris en charge par GroupDocs.Editor. Afin de rendre le document modifiable dans n'importe quel éditeur côté client WYSIWYG (comme CKEditor ou TinyMCE), EditableDocument fournit des méthodes pour générer du balisage HTML et produire des ressources, qui peuvent être acceptées par l'utilisateur.

### Voir également

* interface [IAuxDisposable](../../groupdocs.editor.htmlcss.resources/iauxdisposable)
* espace de noms [GroupDocs.Editor](../../groupdocs.editor)
* Assemblée [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->
