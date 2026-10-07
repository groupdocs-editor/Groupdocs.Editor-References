---
title: "IDocumentInfo"
second_title: "Référence API GroupDocs.Editor pour .NET"
description: "Interface commune à tous les enveloppes de métadonnées de fichiers"
type: docs
weight: 740
url: /fr/net/groupdocs.editor.metadata/idocumentinfo/
---
## IDocumentInfo interface

Interface commune à tous les enveloppes de métadonnées de fichiers

```csharp
public interface IDocumentInfo
```

## Propriétés

| Nom | Description |
| --- | --- |
| [Format](../../groupdocs.editor.metadata/idocumentinfo/format) { get; } | Dans le type implémentant, il faut renvoyer un format de document sous forme d'une valeur unique d'un type qui représente une famille de formats et hérite de l'interface IDocumentFormat |
| [IsEncrypted](../../groupdocs.editor.metadata/idocumentinfo/isencrypted) { get; } | Indique si le fichier spécifique est chiffré et nécessite un mot de passe pour l'ouverture. Pour les types de documents qui ne peuvent pas être chiffrés (comme tous les documents texte), cela doit toujours renvoyer 'false'. |
| [PageCount](../../groupdocs.editor.metadata/idocumentinfo/pagecount) { get; } | Dans le type implémentant, il faut renvoyer le nombre (nombre) de pages ou d'autres entités similaires dépendant du format (onglets, diapositives, etc.). Pour les familles de types qui n'ont rien de similaire (comme les documents texte simples ou XML), il faut renvoyer 1. |
| [Size](../../groupdocs.editor.metadata/idocumentinfo/size) { get; } | Taille du document en octets |

### Voir aussi

* namespace [GroupDocs.Editor.Metadata](../../groupdocs.editor.metadata)
* assembly [GroupDocs.Editor](../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.editor.dll -->
