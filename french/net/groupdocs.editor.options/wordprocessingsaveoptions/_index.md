---
title: "WordProcessingSaveOptions"
second_title: "Référence API GroupDocs.Editor pour .NET"
description: "Permet de spécifier des options personnalisées pour générer et enregistrer des documents compatibles WordProcessing après leur édition"
type: docs
weight: 1240
url: /fr/net/groupdocs.editor.options/wordprocessingsaveoptions/
---
## WordProcessingSaveOptions class

Permet de spécifier des options personnalisées pour générer et enregistrer des documents conformes à WordProcessing après leur édition

```csharp
public sealed class WordProcessingSaveOptions : ICloneable, ISaveOptions
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [WordProcessingSaveOptions](wordprocessingsaveoptions#constructor)() | Ce constructeur sans paramètres crée une nouvelle instance de WordProcessingSaveOptions avec le format de sortie DOCX (pouvant ensuite être modifié via la propriété [`OutputFormat`](./outputformat)) |
| [WordProcessingSaveOptions](wordprocessingsaveoptions#constructor_1)(WordProcessingFormats) | Crée une nouvelle instance de WordProcessingSaveOptions avec le format de sortie WordProcessing obligatoire spécifié, tandis que tous les autres paramètres sont par défaut |

## Propriétés

| Nom | Description |
| --- | --- |
| [EnablePagination](../../groupdocs.editor.options/wordprocessingsaveoptions/enablepagination) { get; set; } | Permet d'activer ou de désactiver la pagination qui sera utilisée lors de l'enregistrement du document WordProcessing. Si le document original a été ouvert et modifié en mode pagination, cette option doit également être activée. Désactivée par défaut. |
| [FontEmbedding](../../groupdocs.editor.options/wordprocessingsaveoptions/fontembedding) { get; set; } | Responsable de l'incorporation des ressources de police dans le document WordProcessing de sortie. Par défaut, aucune police n'est incorporée (NotEmbed). |
| [Locale](../../groupdocs.editor.options/wordprocessingsaveoptions/locale) { get; set; } | Permet de définir un remplacement de la locale (langue) par défaut pour le document WordProcessing, qui sera appliqué lors de sa création. Lorsqu'elle n'est pas spécifiée (valeur par défaut), MS Word (ou un autre programme) détectera (ou choisira) la locale du document en fonction de ses propres paramètres ou d'autres facteurs. |
| [LocaleBi](../../groupdocs.editor.options/wordprocessingsaveoptions/localebi) { get; set; } | Permet de définir un remplacement de la locale (langue) pour le texte RTL (de droite à gauche) du document WordProcessing, qui sera appliqué lors de sa création. Lorsqu'elle n'est pas spécifiée (valeur par défaut), MS Word (ou un autre programme) détectera (ou choisira) la locale RTL du document en fonction de ses propres paramètres ou d'autres facteurs. |
| [LocaleFarEast](../../groupdocs.editor.options/wordprocessingsaveoptions/localefareast) { get; set; } | Permet de remplacer la locale (langue) du document WordProcessing pour le texte est-asiatique, qui sera appliqué lors de sa création. Lorsqu'elle n'est pas spécifiée (valeur par défaut), MS Word (ou un autre programme) détectera (ou choisira) la locale est-asiatique du document en fonction de ses propres paramètres ou d'autres facteurs. |
| [OptimizeMemoryUsage](../../groupdocs.editor.options/wordprocessingsaveoptions/optimizememoryusage) { get; set; } | Active les mécanismes d'optimisation de la mémoire lors de la génération de documents à partir de HTML, ce qui dégrade les performances en contrepartie d'une réduction de l'utilisation de la mémoire. Activer cette option (true) peut réduire considérablement la consommation de mémoire lors de la génération de gros documents, au prix d'un temps d'enregistrement plus lent. La valeur par défaut est false (l'optimisation de la mémoire est désactivée afin d'obtenir de meilleures performances). |
| [OutputFormat](../../groupdocs.editor.options/wordprocessingsaveoptions/outputformat) { get; set; } | Permet de spécifier un format WordProcessing qui sera utilisé pour enregistrer le document |
| [Password](../../groupdocs.editor.options/wordprocessingsaveoptions/password) { get; set; } | Permet de spécifier, modifier, obtenir ou supprimer un mot de passe qui sera utilisé pour chiffrer le document WordProcessing généré. Indiquez NULL ou une chaîne vide pour supprimer (nettoyer) le mot de passe. |
| [Protection](../../groupdocs.editor.options/wordprocessingsaveoptions/protection) { get; set; } | Permet de contrôler et d'appliquer les options de protection du document pour le document WordProcessing de tout format qui prend en charge la protection du document. Par défaut, la valeur est NULL – la protection du document ne sera pas utilisée. |

## Méthodes

| Nom | Description |
| --- | --- |
| [Clone](../../groupdocs.editor.options/wordprocessingsaveoptions/clone)() | Crée et renvoie une copie complète de cette instance de la classe WordProcessingSaveOptions |

### Remarques

WordProcessingSaveOptions est utilisé dans les situations où il existe une instance de la classe EditableDocument contenant le contenu d'un document modifié, et où il est nécessaire d'enregistrer ce contenu dans un nouveau document au format WordProcessing.

### Voir aussi

* interface [ISaveOptions](../isaveoptions)
* namespace [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.editor.dll -->
