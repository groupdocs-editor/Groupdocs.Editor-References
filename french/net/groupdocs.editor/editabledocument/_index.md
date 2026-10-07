---
title: "EditableDocument"
second_title: "Référence API GroupDocs.Editor pour .NET"
description: "Document intermédiaire qui contient le contenu avant et après la modification"
type: docs
weight: 10
url: /fr/net/groupdocs.editor/editabledocument/
---
## EditableDocument class

Document intermédiaire, qui contient le contenu avant et après la modification.

```csharp
public sealed class EditableDocument : IAuxDisposable
```

## Propriétés

| Nom | Description |
| --- | --- |
| [AllResources](../../groupdocs.editor/editabledocument/allresources) { get; } | Renvoie une liste de toutes les ressources existantes : toutes les feuilles de style, les images du HTML et toutes les feuilles de style, les polices, l'audio |
| [Audio](../../groupdocs.editor/editabledocument/audio) { get; } | Renvoie une liste de ressources audio |
| [Css](../../groupdocs.editor/editabledocument/css) { get; } | Permet d'obtenir les ressources de feuilles de style (CSS) (à la fois externes et intégrées, mais pas en ligne), qui sont utilisées par ce document HTML |
| [Fonts](../../groupdocs.editor/editabledocument/fonts) { get; } | Permet d'obtenir les ressources de polices externes, qui sont utilisées par ce document HTML |
| [Images](../../groupdocs.editor/editabledocument/images) { get; } | Permet d'obtenir les ressources d'images externes (images raster et vectorielles), qui sont utilisées par ce document HTML |
| [IsDisposed](../../groupdocs.editor/editabledocument/isdisposed) { get; } | Détermine si ce document Editable a déjà été libéré (true) ou non (false) |

## Méthodes

| Nom | Description |
| --- | --- |
| static [FromFile](../../groupdocs.editor/editabledocument/fromfile)(string, string) | Fabrique statique qui crée une instance de EditableDocument à partir d'un fichier HTML, spécifié par le chemin du fichier *.html lui‑-même et d'un dossier contenant les ressources liées |
| static [FromMarkup](../../groupdocs.editor/editabledocument/frommarkup#frommarkup)(string) | Fabrique statique qui crée une instance de [`EditableDocument`](../editabledocument) à partir du balisage HTML spécifié |
| static [FromMarkup](../../groupdocs.editor/editabledocument/frommarkup#frommarkup_1)(string, IEnumerable&lt;IHtmlResource&gt;) | Fabrique statique qui crée une instance de EditableDocument à partir du balisage HTML spécifié et d'un ensemble de ressources liées correspondantes |
| static [FromMarkupAndResourceFolder](../../groupdocs.editor/editabledocument/frommarkupandresourcefolder)(string, string) | Fabrique statique qui crée une instance de EditableDocument à partir d'un balisage HTML spécifié et à partir des ressources situées dans le dossier indiqué par le chemin complet |
| [Dispose](../../groupdocs.editor/editabledocument/dispose)() | Libère cette instance de document Editable, en libérant son contenu et en rendant ses méthodes et propriétés inutilisables |
| [GetBodyContent](../../groupdocs.editor/editabledocument/getbodycontent#getbodycontent)() | Renvoie le corps du document HTML (contenu interne entre les balises BODY d'ouverture et de fermeture, sans ces balises) sous forme de chaîne. |
| [GetBodyContent](../../groupdocs.editor/editabledocument/getbodycontent#getbodycontent_1)(string) | Renvoie le corps du document HTML (contenu interne entre les balises BODY d'ouverture et de fermeture, sans ces balises) sous forme de chaîne, où les liens vers les ressources externes contiennent le modèle spécifié avec des espaces réservés. |
| [GetContent](../../groupdocs.editor/editabledocument/getcontent#getcontent)() | Renvoie le contenu complet du document HTML sous forme de chaîne. |
| [GetContent](../../groupdocs.editor/editabledocument/getcontent#getcontent_1)(string, string) | Renvoie le contenu complet du document HTML sous forme de chaîne, où les liens vers les ressources externes contiennent le modèle spécifié avec des espaces réservés. |
| [GetContent&lt;TStream&gt;](../../groupdocs.editor/editabledocument/getcontent#getcontent_2)(TStream, Encoding) | Renvoie le contenu complet du document HTML sous forme de flux d'octets en écrivant ce contenu dans le flux spécifié avec l'encodage texte indiqué |
| [GetCssContent](../../groupdocs.editor/editabledocument/getcsscontent#getcsscontent)() | Renvoie le contenu de toutes les feuilles de style externes sous forme d'une liste de chaînes, chaque chaîne représentant une feuille de style. Renvoie une liste vide s'il n'existe aucun CSS pour ce document. |
| [GetCssContent](../../groupdocs.editor/editabledocument/getcsscontent#getcsscontent_1)(string, string) | Renvoie le contenu de toutes les feuilles de style externes sous forme d'une liste de chaînes, chaque chaîne représentant une feuille de style. Le préfixe spécifié sera appliqué à chaque lien vers la ressource externe dans chaque feuille de style résultante. Renvoie une liste vide s'il n'existe aucun CSS pour ce document. |
| [GetEmbeddedHtml](../../groupdocs.editor/editabledocument/getembeddedhtml)() | Renvoie l'intégralité du contenu de ce document HTML avec toutes les ressources associées sous forme d'une chaîne unique, où toutes les ressources sont intégrées dans le balisage HTML sous forme codée en base64. |
| [Save](../../groupdocs.editor/editabledocument/save#save_1)(string) | Enregistre ce document HTML dans le fichier au chemin spécifié, où le balisage HTML sera stocké, ainsi que dans le dossier d'accompagnement contenant les ressources. |
| [Save](../../groupdocs.editor/editabledocument/save#save_2)(string, string) | Enregistre ce document HTML dans le fichier au chemin spécifié, où le balisage HTML sera stocké, ainsi que dans le dossier d'accompagnement contenant les ressources, qui se trouve au chemin indiqué. |
| [Save](../../groupdocs.editor/editabledocument/save#save)(TextWriter, HtmlSaveOptions) | Enregistre le contenu de ce [`EditableDocument`](../editabledocument) en tant que document HTML dans le rédacteur de texte spécifié, tandis que le deuxième paramètre d'options permet de personnaliser la procédure d'enregistrement et de spécifier le rappel de sauvegarde des ressources |

## Événements

| Nom | Description |
| --- | --- |
| event [Disposed](../../groupdocs.editor/editabledocument/disposed) | Événement qui se produit lorsque ce document Editable est éliminé, immédiatement après la fin du processus de libération. |

### Remarques

Une instance de la classe `EditableDocument` peut être produite par la méthode '[`Edit`](../editor/edit)' ou créée par l'utilisateur lui‑même à l'aide de fabriques statiques. `EditableDocument` stocke internement le document dans son propre format fermé, qui est compatible (convertible) avec tous les formats d'importation et d'exportation pris en charge par GroupDocs.Editor. Afin de rendre le document modifiable dans n'importe quel éditeur WYSIWYG côté client (comme CKEditor ou TinyMCE), `EditableDocument` fournit des méthodes pour générer du balisage HTML et produire des ressources qui peuvent être acceptées par l'utilisateur.

### Voir aussi

* interface [IAuxDisposable](../../groupdocs.editor.htmlcss.resources/iauxdisposable)
* namespace [GroupDocs.Editor](../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.editor.dll -->
