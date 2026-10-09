---
title: "Editor"
second_title: "Référence d'API GroupDocs.Editor pour Node.js via Java"
description: "Classe principale qui encapsule les méthodes de conversion."
type: docs
weight: 11
url: /fr/nodejs-java/com.groupdocs.editor/editor/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.resources.IAuxDisposable](../../com.groupdocs.editor.htmlcss.resources/iauxdisposable)
```
public final class Editor implements IAuxDisposable
```

Classe principale, qui encapsule les méthodes de conversion.
La classe Editor fournit des méthodes pour charger, modifier et enregistrer des documents de tous les formats pris en charge. Elle est jetable, donc utilisez une directive 'using' ou libérez ses ressources manuellement via l'appel de la méthode 'Dispose()'. Le chargement des documents est effectué via les constructeurs. La modification des documents – via la méthode 'Edit' – et l'enregistrement du document résultant après modification – via la méthode 'Save'.
**Editor class should be considered as an entry point and the root object of the GroupDocs.Editor. All operations are performed using this class. Typical usage of the Editor class for performing a full document editing pipeline is the next:**

* Load a document into the Editor instance through its constructor.
* Optionally, detect a document type using a method.
* Open a document for editing by calling an method and obtaining an instance of class from it..
* Editing a document content on client-side using any WYSIWYG HTML-editor.
* Creating a new instance of from edited document content.
* Saving an edited document to some output format by calling a method.
* Disposing an instance of Editor class via 'using' operator or manually.

## Constructeurs

| Constructeur | Description |
| --- | --- |
|  | [Editor(DocumentFormatBase format)](#Editor-com.groupdocs.editor.formats.abstraction.DocumentFormatBase-) | Initialise une nouvelle instance de la classe [Editor](../../com.groupdocs.editor/editor) et crée un nouveau document vide basé sur le format spécifié. |
|
|  | [Editor(InputStream document)](#Editor-java.io.InputStream-) | Initialise une nouvelle instance d'Editor avec le document d'entrée spécifié (en tant que flux) |
|
|  | [Editor(InputStream document, ILoadOptions loadOptions)](#Editor-java.io.InputStream-com.groupdocs.editor.options.ILoadOptions-) | Initialise une nouvelle instance d'Editor avec le document d'entrée spécifié (en tant que |
stream) avec ses options de chargement et les paramètres de l'Editor
|
|  | [Editor(String filePath)](#Editor-java.lang.String-) | Initialise une nouvelle instance d'Editor avec le document d'entrée spécifié (en tant que chemin de fichier complet) |
|
|  | [Editor(String filePath, ILoadOptions loadOptions)](#Editor-java.lang.String-com.groupdocs.editor.options.ILoadOptions-) | Initialise une nouvelle instance d'Editor avec le document d'entrée spécifié (en tant que chemin de fichier complet) avec ses options de chargement |
|
## Méthodes

| Méthode | Description |
| --- | --- |
|  | [edit(IEditOptions editOptions)](#edit-com.groupdocs.editor.options.IEditOptions-) | Ouvre un document préalablement chargé pour l'édition en utilisant les options spécifiques au format en générant et en retournant une instance de la classe '' qui, à son tour, contient des méthodes pour produire du balisage HTML et les ressources associées. |
|
|  | [edit()](#edit--) | Ouvre un document préalablement chargé pour l'édition en utilisant les options par défaut par |
en générant et en retournant une instance de la classe 'EditableDocument', qui,
à son tour, contient des méthodes pour produire du balisage HTML et les
ressources.
|
|  | [save(EditableDocument inputDocument, OutputStream outputDocument, ISaveOptions saveOptions)](#save-com.groupdocs.editor.EditableDocument-java.io.OutputStream-com.groupdocs.editor.options.ISaveOptions-) | Convertit le document édité spécifié, représenté comme instance de |
'EditableDocument', vers le document résultant du format spécifié et
enregistre son contenu dans le flux spécifié
|
|  | [save(EditableDocument inputDocument, String filePath, ISaveOptions saveOptions)](#save-com.groupdocs.editor.EditableDocument-java.lang.String-com.groupdocs.editor.options.ISaveOptions-) | Convertit le document édité spécifié, représenté comme instance de '', vers le document résultant du format spécifié et enregistre son contenu dans un fichier selon le chemin de fichier spécifié |
|
|  | [save(EditableDocument inputDocument, String filePath)](#save-com.groupdocs.editor.EditableDocument-java.lang.String-) | Convertit le document édité spécifié (représenté par un [EditableDocument](../../com.groupdocs.editor/editabledocument)) en un document de sortie dont le format est déterminé à partir de l'extension du nom de fichier, et l'enregistre au chemin de fichier spécifié. |
|
|  | [save(OutputStream outputDocument, WordProcessingSaveOptions saveOptions)](#save-java.io.OutputStream-com.groupdocs.editor.options.WordProcessingSaveOptions-) | Convertit le document original après modification (par exemple, |
FormFieldManager
(#getFormFieldManager.getFormFieldManager)),
vers le document résultant du format spécifié et enregistre son contenu dans le flux fourni.
|
|  | [save(OutputStream outputDocument)](#save-java.io.OutputStream-) | Enregistrez le contenu du document actuel dans le flux de sortie spécifié. |
|
|  | [getDocumentInfo(String password)](#getDocumentInfo-java.lang.String-) | Renvoie les métadonnées du document qui a été chargé dans cette instance d'Editor |
|
|  | [dispose()](#dispose--) | Libère cette instance d'Editor, afin qu'elle libère toutes les |
ressources et devienne indisponible pour toute utilisation ultérieure
|
|  | [isDisposed()](#isDisposed--) | Indique si cette instance d'Editor a déjà été libérée et ne peut pas être |
utilisée davantage (true) ou non et est active (false)
|
### Editor(DocumentFormatBase format) {#Editor-com.groupdocs.editor.formats.abstraction.DocumentFormatBase-}
```
public Editor(DocumentFormatBase format)
```


Initialise une nouvelle instance de la classe [Editor](../../com.groupdocs.editor/editor) et crée un nouveau document vide basé sur le format spécifié.

<br />

*** ** * ** ***

> ```
>   IDocumentFormat format = WordProcessingFormats.Docx;
>  Editor editor = new Editor(format);
>  {
>      // Use the editor instance to edit and save documents
>  }
>  
>  
> ```

<br />



**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | format | [DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase) | représente le format de fichier du document qui sera créé. **Learn more** |

* More about file types supported by GroupDocs.Editor: [Document formats supported by GroupDocs.Editor](../https://docs.groupdocs.com/display/editornet/Supported+Document+Formats)
* More about GroupDocs.Editor for Java features: [Developer Guide](../https://docs.groupdocs.com/editor/java/developer-guide/)
|

### Editor(InputStream document) {#Editor-java.io.InputStream-}
```
public Editor(InputStream document)
```


Initialise une nouvelle instance d'Editor avec le document d'entrée spécifié (en tant que flux)


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | document | java.io.InputStream | Délégué, qui doit retourner un flux contenant le contenu du document. Ne doit pas être NULL. **Learn more** |

* More about file types supported by GroupDocs.Editor: [Document formats supported by GroupDocs.Editor](../https://docs.groupdocs.com/display/editornet/Supported+Document+Formats)
* More about GroupDocs.Editor for Java features: [Developer Guide](../https://docs.groupdocs.com/editor/java/developer-guide/)
|

### Editor(InputStream document, ILoadOptions loadOptions) {#Editor-java.io.InputStream-com.groupdocs.editor.options.ILoadOptions-}
```
public Editor(InputStream document, ILoadOptions loadOptions)
```


Initialise une nouvelle instance d'Editor avec le document d'entrée spécifié (en tant que
stream) avec ses options de chargement et les paramètres de l'Editor


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | document | java.io.InputStream | Délégué, qui doit retourner un flux contenant le contenu du document. Ne doit pas être NULL. |
|
|  | loadOptions | [ILoadOptions](../../com.groupdocs.editor.options/iloadoptions) | Délégué, qui doit renvoyer des options de chargement de document. Peut être NULL et peut renvoyer null - dans ce cas le type de document sera détecté automatiquement et les options de chargement par défaut pour ce type seront appliquées. |
|

### Editor(String filePath) {#Editor-java.lang.String-}
```
public Editor(String filePath)
```


Initialise une nouvelle instance d'Editor avec le document d'entrée spécifié (en tant que chemin de fichier complet)


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | filePath | java.lang.String | Chemin complet du fichier. Ne doit pas être NULL. Doit être valide et le fichier doit exister. **En savoir plus** |

* More about file types supported by GroupDocs.Editor: [Document formats supported by GroupDocs.Editor](../https://docs.groupdocs.com/editor/java/supported-document-formats/)
* More about GroupDocs.Editor for Java features: [Developer Guide](../https://docs.groupdocs.com/editor/java/developer-guide/)
|

### Editor(String filePath, ILoadOptions loadOptions) {#Editor-java.lang.String-com.groupdocs.editor.options.ILoadOptions-}
```
public Editor(String filePath, ILoadOptions loadOptions)
```


Initialise une nouvelle instance d'Editor avec le document d'entrée spécifié (en tant que chemin de fichier complet) avec ses options de chargement


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | filePath | java.lang.String | Chemin complet du fichier. Ne doit pas être NULL. Doit être valide et le fichier doit exister. |
|
|  | loadOptions | [ILoadOptions](../../com.groupdocs.editor.options/iloadoptions) | Délégué, qui doit renvoyer des options de chargement de document. Peut être NULL et peut renvoyer null - dans ce cas le type de document sera détecté automatiquement et les options de chargement par défaut pour ce type seront appliquées. **En savoir plus** |

* More about file types supported by GroupDocs.Editor: [Document formats supported by GroupDocs.Editor](../https://docs.groupdocs.com/editor/java/supported-document-formats/)
* More about GroupDocs.Editor for Java features: [Developer Guide](../https://docs.groupdocs.com/editor/java/developer-guide/)
* More about how to open and edit password-protected documents and document from different storages: [Load and edit documents using GroupDocs.Editor](../https://docs.groupdocs.com/editor/java/load-document/)
|

### edit(IEditOptions editOptions) {#edit-com.groupdocs.editor.options.IEditOptions-}
```
public final EditableDocument edit(IEditOptions editOptions)
```


Ouvre un document préalablement chargé pour l'édition en utilisant les options spécifiques au format en générant et en retournant une instance de la classe '' qui, à son tour, contient des méthodes pour produire du balisage HTML et les ressources associées.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | editOptions | [IEditOptions](../../com.groupdocs.editor.options/ieditoptions) | Options de document spécifiques au format, qui permettent d’ajuster le processus de conversion. Ne doit pas être NULL. Ne doit pas entrer en conflit avec les options de chargement déjà appliquées. |


*** ** * ** ***

Lorsque le document original d’entrée est chargé dans l’instance 'Editor' via le constructeur, cette méthode permet d’ouvrir le document pour le modifier en le convertissant en format intermédiaire, encapsulé dans une instance de la classe 'EditableDocument'. 'EditableDocument', renvoyé par cette méthode, contient toutes les méthodes et propriétés nécessaires pour produire le balisage HTML et les ressources correspondantes (comme les images, les polices et les feuilles de style) dans toutes les configurations requises pour les transmettre ensuite à n’importe quel éditeur HTML WYSIWYG. Cette surcharge obtient les options d’édition, spécifiques aux formats de la famille.

*** ** * ** ***


**Learn more**

* More about editing documents using GroupDocs.Editor: [How to edit document using GroupDocs.Editor](../https://docs.groupdocs.com/display/editornet/Edit+document)
|

**Returns:**
[EditableDocument](../../com.groupdocs.editor/editabledocument)
### edit() {#edit--}
```
public final EditableDocument edit()
```


Ouvre un document préalablement chargé pour l'édition en utilisant les options par défaut par
en générant et en retournant une instance de la classe 'EditableDocument', qui,
à son tour, contient des méthodes pour produire du balisage HTML et les
ressources.


**Returns:**
[EditableDocument](../../com.groupdocs.editor/editabledocument) - Instance of the 'EditableDocument' class, which encapsulates overall input document with all its resources in intermediate format. This method, if successfully finished, never returns NULL.


*** ** * ** ***

Lorsque le document original d’entrée est chargé dans l’instance 'Editor' via le constructeur, cette méthode permet d’ouvrir le document pour le modifier en le convertissant en format intermédiaire, encapsulé dans une instance de la classe 'EditableDocument'. 'EditableDocument', renvoyé par cette méthode, contient toutes les méthodes et propriétés nécessaires pour produire le balisage HTML et les ressources correspondantes (comme les images, les polices et les feuilles de style) dans toutes les configurations requises pour les transmettre ensuite à n’importe quel éditeur HTML WYSIWYG. Cette surcharge applique les options d’édition, qui sont les valeurs par défaut pour le format auquel appartient le document d’entrée.

<br />

**Learn more**

* More about editing documents using GroupDocs.Editor: [How to edit document using GroupDocs.Editor](../https://docs.groupdocs.com/editor/java/edit-document/)

### save(EditableDocument inputDocument, OutputStream outputDocument, ISaveOptions saveOptions) {#save-com.groupdocs.editor.EditableDocument-java.io.OutputStream-com.groupdocs.editor.options.ISaveOptions-}
```
public final void save(EditableDocument inputDocument, OutputStream outputDocument, ISaveOptions saveOptions)
```


Convertit le document édité spécifié, représenté comme instance de
'EditableDocument', vers le document résultant du format spécifié et
enregistre son contenu dans le flux spécifié


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | inputDocument | [EditableDocument](../../com.groupdocs.editor/editabledocument) | Version du document d’entrée, qui a été modifié dans un éditeur HTML WYSIWYG et est stockée comme instance de la classe 'EditableDocument', qui doit être convertie en document de sortie d’un format spécifique |
|
|  | outputDocument | java.io.OutputStream | Flux de sortie, dans lequel le contenu du document résultant sera enregistré. Ne doit pas être NULL, disposé, et doit prendre en charge l’écriture. |
|
|  | saveOptions | [ISaveOptions](../../com.groupdocs.editor.options/isaveoptions) | Options d’enregistrement du document, qui définissent le format du document résultant, ainsi que les options d’enregistrement générales et spécifiques au format. **En savoir plus** |

* More about saving document after edit using GroupDocs.Editor: [How to save edited document using GroupDocs.Editor](../https://docs.groupdocs.com/display/editornet/Save+document)
|

### save(EditableDocument inputDocument, String filePath, ISaveOptions saveOptions) {#save-com.groupdocs.editor.EditableDocument-java.lang.String-com.groupdocs.editor.options.ISaveOptions-}
```
public final void save(EditableDocument inputDocument, String filePath, ISaveOptions saveOptions)
```


Convertit le document édité spécifié, représenté comme instance de '', vers le document résultant du format spécifié et enregistre son contenu dans un fichier selon le chemin de fichier spécifié


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | inputDocument | [EditableDocument](../../com.groupdocs.editor/editabledocument) | Version du document d’entrée, qui a été modifié dans un éditeur HTML WYSIWYG et est stockée comme instance de la classe '' , qui doit être convertie en document de sortie d’un format spécifique. Ne doit pas être null ou disposé. |
|
|  | filePath | java.lang.String | Chemin du fichier dans lequel le document de sortie sera enregistré. Si un fichier du même nom existe, il sera entièrement réécrit. La chaîne de chemin ne doit pas être null, vide ou ne contenir que des espaces. |
|
|  | saveOptions | [ISaveOptions](../../com.groupdocs.editor.options/isaveoptions) | Options d’enregistrement du document, qui définissent le format du document résultant, ainsi que les options d’enregistrement générales et spécifiques au format. Ne doit pas être null. **En savoir plus** |

* More about saving document after edit using GroupDocs.Editor: [How to save edited document using GroupDocs.Editor](../https://docs.groupdocs.com/display/editornet/Save+document)
|

### save(EditableDocument inputDocument, String filePath) {#save-com.groupdocs.editor.EditableDocument-java.lang.String-}
```
public final void save(EditableDocument inputDocument, String filePath)
```


Convertit le document édité spécifié (représenté par un [EditableDocument](../../com.groupdocs.editor/editabledocument)) en un document de sortie dont le format est déterminé à partir de l'extension du nom de fichier, et l'enregistre au chemin de fichier spécifié.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | inputDocument | [EditableDocument](../../com.groupdocs.editor/editabledocument) | Version du document d’entrée qui a été modifié dans un éditeur HTML WYSIWYG et est stockée comme instance de [EditableDocument](../../com.groupdocs.editor/editabledocument). Ne doit pas être  null  ou disposé. |
|
|  | filePath | java.lang.String | Chemin du fichier où le document de sortie sera enregistré. Si un fichier du même nom existe, il sera entièrement écrasé. La chaîne de chemin ne doit pas être  null , vide, ou ne contenir que des espaces. Étant donné que les options d’enregistrement par défaut et le format de sortie sont déterminés à partir de ce nom de fichier, il doit avoir une extension valide. |
|

### save(OutputStream outputDocument, WordProcessingSaveOptions saveOptions) {#save-java.io.OutputStream-com.groupdocs.editor.options.WordProcessingSaveOptions-}
```
public final OutputStream save(OutputStream outputDocument, WordProcessingSaveOptions saveOptions)
```


Convertit le document original après modification (par exemple,
FormFieldManager
(#getFormFieldManager.getFormFieldManager)),
vers le document résultant du format spécifié et enregistre son contenu dans le flux fourni.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | outputDocument | java.io.OutputStream | Le flux dans lequel le document de sortie sera enregistré. Ce flux doit être accessible en écriture et positionné au début du contenu du document. Ne doit pas être null. |
|
|  | saveOptions | [WordProcessingSaveOptions](../../com.groupdocs.editor.options/wordprocessingsaveoptions) | Options d’enregistrement du document qui définissent le format du document résultant, ainsi que les options d’enregistrement générales et spécifiques au format. Ne doit pas être null. |

<br />

*** ** * ** ***

Si le  outputDocument  ou le  saveOptions  est nul, une NullPointerException sera levée. Si le document à enregistrer est manquant, une NullPointerException sera levée.

<br />

<br />

*** ** * ** ***

 **Learn more:** 

* 

<br />

|

**Returns:**
java.io.OutputStream - Le flux contenant le contenu du document enregistré.

### save(OutputStream outputDocument) {#save-java.io.OutputStream-}
```
public final OutputStream save(OutputStream outputDocument)
```


Enregistrez le contenu du document actuel dans le flux de sortie spécifié.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | outputDocument | java.io.OutputStream | Le flux dans lequel le contenu du document sera enregistré. Il ne peut pas être nul. |

<br />

*** ** * ** ***

Cette méthode copie le contenu de la représentation interne du document vers le flux de sortie fourni. La position d'origine du flux est conservée après l'opération d'enregistrement.

<br />

|

**Returns:**
java.io.OutputStream - Le flux contenant le contenu du document enregistré.

### getDocumentInfo(String password) {#getDocumentInfo-java.lang.String-}
```
public final IDocumentInfo getDocumentInfo(String password)
```


Renvoie les métadonnées du document qui a été chargé dans cette instance d'Editor


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | mot de passe | java.lang.String | L'utilisateur peut spécifier un mot de passe pour un document, si ce document est chiffré avec le mot de passe. Peut être NULL ou une chaîne vide, ce qui équivaut à l'absence de mot de passe. Pour les formats de document qui ne disposent pas de fonctionnalité de protection par mot de passe, cet argument sera ignoré. Si le document est chiffré et que le mot de passe n'est pas spécifié dans ce paramètre, mais qu'il a été spécifié auparavant dans les options de chargement lors de la création de cette instance, il sera utilisé. **Learn more** |

* Learn more about obtaining document specific properties in code: [How to get document info using GroupDocs.Editor](../https://docs.groupdocs.com/editor/java/extracting-document-metainfo/)
|

**Returns:**
[IDocumentInfo](../../com.groupdocs.editor.metadata/idocumentinfo)
### dispose() {#dispose--}
```
public final void dispose()
```


Libère cette instance d'Editor, afin qu'elle libère toutes les
ressources et devienne indisponible pour toute utilisation ultérieure


### isDisposed() {#isDisposed--}
```
public final boolean isDisposed()
```


Indique si cette instance d'Editor a déjà été libérée et ne peut pas être
utilisée davantage (true) ou non et est active (false)


**Returns:**
booléen
