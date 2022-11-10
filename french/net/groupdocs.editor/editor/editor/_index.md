---
title: Editor
second_title: Référence de l'API GroupDocs.Editor pour .NET
description: Initialise la nouvelle instance de léditeur avec le document dentrée spécifié sous forme de flux
type: docs
weight: 10
url: /fr/net/groupdocs.editor/editor/editor/
---
## Editor(Func&lt;Stream&gt;) {#constructor}

Initialise la nouvelle instance de l'éditeur avec le document d'entrée spécifié (sous forme de flux)

```csharp
public Editor(Func<Stream> document)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| document | Func`1 | Délégué, qui devrait renvoyer un flux avec le contenu du document. Ne doit pas être NULL. |

### Remarques

**Apprendre encore plus**

* En savoir plus sur les types de fichiers pris en charge par GroupDocs.Editor : [Formats de documents pris en charge par GroupDocs.Editor](https://docs.groupdocs.com/display/editornet/Supported+Document+Formats)
* En savoir plus sur les fonctionnalités de GroupDocs.Editor pour .NET : [Guide du développeur](https://docs.groupdocs.com/display/editornet/Developer+Guide)

### Voir également

* class [Editor](../../editor)
* espace de noms [GroupDocs.Editor](../../editor)
* Assemblée [GroupDocs.Editor](../../../)

---

## Editor(Func&lt;Stream&gt;, Func&lt;ILoadOptions&gt;) {#constructor_1}

Initialise la nouvelle instance de l'éditeur avec le document d'entrée spécifié (sous forme de flux) avec ses options de chargement

```csharp
public Editor(Func<Stream> document, Func<ILoadOptions> loadOptions)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| document | Func`1 | Délégué, qui devrait renvoyer un flux avec le contenu du document. Ne doit pas être NULL. |
| loadOptions | Func`1 | Délégué, qui devrait renvoyer des options de chargement de document. Peut être NULL et peut retourner null - dans ce cas le type de document sera détecté automatiquement et les options de chargement par défaut pour ce type seront appliquées. |

### Remarques

**Apprendre encore plus**

* En savoir plus sur les types de fichiers pris en charge par GroupDocs.Editor : [Formats de documents pris en charge par GroupDocs.Editor](https://docs.groupdocs.com/display/editornet/Supported+Document+Formats)
* En savoir plus sur les fonctionnalités de GroupDocs.Editor pour .NET : [Guide du développeur](https://docs.groupdocs.com/display/editornet/Developer+Guide)
* En savoir plus sur l'ouverture et la modification de documents protégés par mot de passe et de documents provenant de différents stockages : [Charger et modifier des documents à l'aide de GroupDocs.Editor](https://docs.groupdocs.com/display/editornet/Load+document)

### Voir également

* interface [ILoadOptions](../../../groupdocs.editor.options/iloadoptions)
* class [Editor](../../editor)
* espace de noms [GroupDocs.Editor](../../editor)
* Assemblée [GroupDocs.Editor](../../../)

---

## Editor(string) {#constructor_2}

Initialise la nouvelle instance de l'éditeur avec le document d'entrée spécifié (en tant que chemin de fichier complet)

```csharp
public Editor(string filePath)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| filePath | String | Chemin d'accès complet au fichier. Ne doit pas être NULL. Doit être valide et le fichier doit exister. |

### Remarques

**Apprendre encore plus**

* En savoir plus sur les types de fichiers pris en charge par GroupDocs.Editor : [Formats de documents pris en charge par GroupDocs.Editor](https://docs.groupdocs.com/display/editornet/Supported+Document+Formats)
* En savoir plus sur les fonctionnalités de GroupDocs.Editor pour .NET : [Guide du développeur](https://docs.groupdocs.com/display/editornet/Developer+Guide)

### Voir également

* class [Editor](../../editor)
* espace de noms [GroupDocs.Editor](../../editor)
* Assemblée [GroupDocs.Editor](../../../)

---

## Editor(string, Func&lt;ILoadOptions&gt;) {#constructor_3}

Initialise la nouvelle instance de l'éditeur avec le document d'entrée spécifié (en tant que chemin de fichier complet) avec ses options de chargement

```csharp
public Editor(string filePath, Func<ILoadOptions> loadOptions)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| filePath | String | Chemin d'accès complet au fichier. Ne doit pas être NULL. Doit être valide et le fichier doit exister. |
| loadOptions | Func`1 | Délégué, qui devrait renvoyer des options de chargement de document. Peut être NULL et peut retourner null - dans ce cas le type de document sera détecté automatiquement et les options de chargement par défaut pour ce type seront appliquées. |

### Remarques

**Apprendre encore plus**

* En savoir plus sur les types de fichiers pris en charge par GroupDocs.Editor : [Formats de documents pris en charge par GroupDocs.Editor](https://docs.groupdocs.com/display/editornet/Supported+Document+Formats)
* En savoir plus sur les fonctionnalités de GroupDocs.Editor pour .NET : [Guide du développeur](https://docs.groupdocs.com/display/editornet/Developer+Guide)
* En savoir plus sur l'ouverture et la modification de documents protégés par mot de passe et de documents provenant de différents stockages : [Charger et modifier des documents à l'aide de GroupDocs.Editor](https://docs.groupdocs.com/display/editornet/Load+document)

### Voir également

* interface [ILoadOptions](../../../groupdocs.editor.options/iloadoptions)
* class [Editor](../../editor)
* espace de noms [GroupDocs.Editor](../../editor)
* Assemblée [GroupDocs.Editor](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->
