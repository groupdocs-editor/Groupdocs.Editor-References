---
title: WordProcessingSaveOptions
second_title: Référence de l'API GroupDocs.Editor pour .NET
description: Permet de spécifier des options personnalisées pour générer et enregistrer des documents compatibles avec WordProcessing après leur modification
type: docs
weight: 1240
url: /fr/net/groupdocs.editor.options/wordprocessingsaveoptions/
---
## WordProcessingSaveOptions class

Permet de spécifier des options personnalisées pour générer et enregistrer des documents compatibles avec WordProcessing après leur modification

```csharp
public sealed class WordProcessingSaveOptions : ICloneable, ISaveOptions
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [WordProcessingSaveOptions](wordprocessingsaveoptions)(WordProcessingFormats) | Crée une nouvelle instance de WordProcessingSaveOptions avec le format de sortie WordProcessing obligatoire spécifié, tandis que tous les autres paramètres sont default |

## Propriétés

| Nom | La description |
| --- | --- |
| [EnablePagination](../../groupdocs.editor.options/wordprocessingsaveoptions/enablepagination) { get; set; } | Permet d'activer ou de désactiver la pagination qui sera utilisée pour enregistrer le document WordProcessing. Si le document original a été ouvert et modifié en mode pagination, cette option doit également être activée. Par défaut est désactivé. |
| [FontEmbedding](../../groupdocs.editor.options/wordprocessingsaveoptions/fontembedding) { get; set; } | Responsable de l'intégration des ressources de police dans le document WordProcessing de sortie. Par défaut, n'intègre aucune police (NotEmbed). |
| [Locale](../../groupdocs.editor.options/wordprocessingsaveoptions/locale) { get; set; } | Permet de définir des paramètres régionaux par défaut (langue) pour le document WordProcessing, qui seront appliqués lors de sa création. Lorsque n'est pas spécifié (valeur par défaut), MS Word (ou un autre programme) détectera (ou choisira) le document local selon à ses propres paramètres ou à d'autres facteurs. |
| [LocaleBi](../../groupdocs.editor.options/wordprocessingsaveoptions/localebi) { get; set; } | Permet de définir des paramètres régionaux de remplacement (langue) pour le document WordProcessing pour le texte RTL (de droite à gauche), qui sera appliqué lors de sa création. Lorsque n'est pas spécifié (valeur par défaut), MS Word (ou autre programme) détectera (ou choisira) le document RTL locale en fonction de ses propres paramètres ou d'autres facteurs. |
| [LocaleFarEast](../../groupdocs.editor.options/wordprocessingsaveoptions/localefareast) { get; set; } | Permet de remplacer les paramètres régionaux (langue) du document WordProcessing pour le texte est-asiatique, qui seront appliqués lors de sa création. Lorsque n'est pas spécifié (valeur par défaut), MS Word (ou un autre programme) détectera (ou choisira ) le document East-Asia locale selon ses propres paramètres ou d'autres facteurs. |
| [OptimizeMemoryUsage](../../groupdocs.editor.options/wordprocessingsaveoptions/optimizememoryusage) { get; set; } | Active les mécanismes d'optimisation de la mémoire lors de la génération de documents à partir de HTML, ce qui dégrade les performances en raison de la diminution de l'utilisation de la mémoire. La définition de cette option sur true peut réduire considérablement la consommation de mémoire lors de la génération de documents volumineux au prix d'un gain de temps plus lent. La valeur par défaut est false (l'optimisation de la mémoire est désactivée pour de meilleures performances). |
| [OutputFormat](../../groupdocs.editor.options/wordprocessingsaveoptions/outputformat) { get; set; } | Permet de spécifier un format WordProcessing, qui sera utilisé pour enregistrer le document |
| [Password](../../groupdocs.editor.options/wordprocessingsaveoptions/password) { get; set; } | Permet de spécifier, modifier, obtenir ou supprimer un mot de passe, qui sera utilisé pour encoder le document WordProcessing généré. Spécifiez NULL ou une chaîne vide pour supprimer (nettoyer) le mot de passe. |
| [Protection](../../groupdocs.editor.options/wordprocessingsaveoptions/protection) { get; set; } | Permet de contrôler et d'appliquer les options de protection de document pour le document WordProcessing de n'importe quel format, qui prend en charge la protection de document. Par défaut est NULL - la protection de document ne sera pas utilisée. |

## Méthodes

| Nom | La description |
| --- | --- |
| [Clone](../../groupdocs.editor.options/wordprocessingsaveoptions/clone)() | Crée et renvoie une copie complète de cette instance de WordProcessingSaveOptions class |

### Remarques

WordProcessingSaveOptions est appliqué dans les situations où il existe une instance de la classe EditableDocument, qui contient un contenu de document modifié, et il est nécessaire d'enregistrer ce contenu dans le nouveau document au format WordProcessing.

### Voir également

* interface [ISaveOptions](../isaveoptions)
* espace de noms [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* Assemblée [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->
