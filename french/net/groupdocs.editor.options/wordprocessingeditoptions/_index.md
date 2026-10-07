---
title: "WordProcessingEditOptions"
second_title: "Référence API GroupDocs.Editor pour .NET"
description: "Permet de spécifier des options personnalisées pour l'édition de documents de tous les formats WordProcessing Wordscompliant pris en charge, tels que DOCX, RTF, ODT, etc."
type: docs
weight: 1200
url: /fr/net/groupdocs.editor.options/wordprocessingeditoptions/
---
## WordProcessingEditOptions class

Permet de spécifier des options personnalisées pour l'édition de documents de tous les formats WordProcessing (conformes à Words) pris en charge, tels que DOC(X), RTF, ODT, etc.

```csharp
public class WordProcessingEditOptions : IEditOptions
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [WordProcessingEditOptions](wordprocessingeditoptions#constructor)() | Crée et renvoie une nouvelle instance de la classe WordProcessingEditOptions, où toutes les options sont définies à leurs valeurs par défaut. |
| [WordProcessingEditOptions](wordprocessingeditoptions#constructor_1)(bool) | Crée et renvoie une nouvelle instance de la classe WordProcessingEditOptions avec la pagination spécifiée et toutes les autres options par défaut. |

## Propriétés

| Nom | Description |
| --- | --- |
| [EnableLanguageInformation](../../groupdocs.editor.options/wordprocessingeditoptions/enablelanguageinformation) { get; set; } | Spécifie si les informations de langue sont exportées dans le balisage HTML sous forme d'attributs HTML 'lang'. Cette option peut être utile pour la conversion aller-retour des documents multilingues. Par défaut, elle est désactivée (false). |
| [EnablePagination](../../groupdocs.editor.options/wordprocessingeditoptions/enablepagination) { get; set; } | Permet d'activer ou de désactiver la pagination dans le document HTML résultant. Par défaut, elle est désactivée (false). |
| [ExtractOnlyUsedFont](../../groupdocs.editor.options/wordprocessingeditoptions/extractonlyusedfont) { get; set; } | Obtient ou définit une valeur indiquant s'il faut extraire uniquement les ressources de police utilisées dans le contenu textuel du document. |
| [FontExtraction](../../groupdocs.editor.options/wordprocessingeditoptions/fontextraction) { get; set; } | Responsable de l'extraction des ressources de police utilisées dans le document WordProcessing d'entrée. Par défaut, aucune police n'est extraite (NotExtract). |
| [InputControlsClassName](../../groupdocs.editor.options/wordprocessingeditoptions/inputcontrolsclassname) { get; set; } | Permet de spécifier un nom de classe, qui sera placé dans les attributs 'class' de chaque élément HTML représentant un champ du document WordProcessing d'entrée. Par défaut, il est NULL - les attributs 'class' ne sont pas appliqués. |
| [UseInlineStyles](../../groupdocs.editor.options/wordprocessingeditoptions/useinlinestyles) { get; set; } | Contrôle l'endroit où stocker les données de style et de mise en forme du document WordProcessing d'entrée : dans une feuille de style externe (`false`) ou sous forme de styles en ligne dans le balisage HTML (`true`). Par défaut, les styles externes sont utilisés (`false`). |

### Voir aussi

* interface [IEditOptions](../ieditoptions)
* namespace [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.editor.dll -->
