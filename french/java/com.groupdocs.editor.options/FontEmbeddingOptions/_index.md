---
title: "FontEmbeddingOptions"
second_title: "Référence API de GroupDocs.Editor pour Java"
description: "Les options d'intégration de polices contrôlent quelles ressources de police doivent être intégrées dans le document WordProcessing de sortie"
type: docs
weight: 17
url: /fr/java/com.groupdocs.editor.options/fontembeddingoptions/
---
**Inheritance:**
java.lang.Object
```
public final class FontEmbeddingOptions
```

Les options d'intégration de polices contrôlent quelles ressources de police doivent être intégrées dans
le document WordProcessing de sortie


*** ** * ** ***

Les options d'intégration de polices sont appliquées lors de l'enregistrement du document (de l'EditableDocument intermédiaire vers le format WordProcessing de sortie), cet enum est inclus en tant que propriété dans WordProcessingSaveOptions, d'où il doit être utilisé

<br />


## Champs

| Champ | Description |
| --- | --- |
|  | [NotEmbed](#NotEmbed) | N'intégrez aucune ressource de police ni depuis EditableDocument ni depuis le |
système.
|
|  | [EmbedAll](#EmbedAll) | Analysez le contenu du document à partir de l'EditableDocument d'entrée, trouvez toutes les polices utilisées |
et intégrez-les dans le document WordProcessing de sortie.
|
|  | [EmbedWithoutSystem](#EmbedWithoutSystem) | Exactement à [EmbedAll](../../com.groupdocs.editor.options/fontembeddingoptions#EmbedAll), mais exclure ces polices, |
qui sont traitées par le système d'exploitation comme des polices système
|
## Méthodes

| Méthode | Description |
| --- | --- |
| [getFontEmbeddingOptions()](#getFontEmbeddingOptions--) |  |
### NotEmbed {#NotEmbed}
```
public static final int NotEmbed
```


N'intégrez aucune ressource de police ni depuis EditableDocument ni depuis le
système. Valeur par défaut.


### EmbedAll {#EmbedAll}
```
public static final int EmbedAll
```


Analysez le contenu du document à partir de l'EditableDocument d'entrée, trouvez toutes les polices utilisées
et les incorporer dans le document WordProcessing de sortie. En premier lieu
GroupDocs.Editor récupère les polices à partir des ressources de police contenues dans EditableDocument.
Si elles sont insuffisantes ou manquantes, alors GroupDocs.Editor récupère les polices
à partir du système d'exploitation.


*** ** * ** ***

Tout d'abord, GroupDocs.Editor analyse le contenu d'EditableDocument et crée une liste de toutes les polices utilisées. Ensuite, ces polices sont recherchées dans les ressources de police d'EditableDocument. Si EditableDocument contient des ressources de police qui ne sont pas utilisées dans le contenu du document, ces ressources sont ignorées. S'il existe des polices utilisées dans le contenu du document qui n'ont pas de ressources de police correspondantes dans EditableDocument, alors GroupDocs.Editor tente de les trouver dans le système d'exploitation. Cette option ressemble à l'option "Incorporer les polices dans le fichier" avec toutes les sous‑options désactivées dans Microsoft Word 2007 et versions ultérieures

<br />



### EmbedWithoutSystem {#EmbedWithoutSystem}
```
public static final int EmbedWithoutSystem
```


Exactement à [EmbedAll](../../com.groupdocs.editor.options/fontembeddingoptions#EmbedAll), mais exclure ces polices,
qui sont traitées par le système d'exploitation comme des polices système


*** ** * ** ***

MS Windows possède un concept de polices système, qui sont les polices les plus basiques et utilisées par Windows lui‑même. Lors de l'utilisation de cette option, GroupDocs.Editor se comporte comme dans le cas [EmbedAll](../../com.groupdocs.editor.options/fontembeddingoptions#EmbedAll), mais examine finalement l'ensemble des polices obtenues et exclut celles qui sont traitées par le système d'exploitation comme des polices système. Cette option ressemble aux options "Incorporer les polices dans le fichier" + "Ne pas incorporer les polices système courantes" dans Microsoft Word 2007 et versions ultérieures

<br />



### getFontEmbeddingOptions() {#getFontEmbeddingOptions--}
```
public static int[] getFontEmbeddingOptions()
```




**Returns:**
int[]
