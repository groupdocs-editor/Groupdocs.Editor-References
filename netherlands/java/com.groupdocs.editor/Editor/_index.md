---
title: "Editor"
second_title: "GroupDocs.Editor for Java API-referentie"
description: "Hoofdklasse die conversiemethoden omvat."
type: docs
weight: 11
url: /nl/java/com.groupdocs.editor/editor/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.resources.IAuxDisposable](../../com.groupdocs.editor.htmlcss.resources/iauxdisposable)
```
public final class Editor implements IAuxDisposable
```

Hoofdklaas, die conversiemethoden encapsuleert.
De Editor-klasse biedt methoden voor het laden, bewerken en opslaan van documenten in alle ondersteunde formaten. Het is wegwerpend, dus gebruik een 'using'-directive of maak de bronnen handmatig vrij via de 'Dispose()'-methode. Documentladen wordt uitgevoerd via constructors. Documentbewerking – via de methode 'Edit', en opslaan van het resulterende document na bewerking – via de methode 'Save'.
**Editor class should be considered as an entry point and the root object of the GroupDocs.Editor. All operations are performed using this class. Typical usage of the Editor class for performing a full document editing pipeline is the next:**

* Load a document into the Editor instance through its constructor.
* Optionally, detect a document type using a method.
* Open a document for editing by calling an method and obtaining an instance of class from it..
* Editing a document content on client-side using any WYSIWYG HTML-editor.
* Creating a new instance of from edited document content.
* Saving an edited document to some output format by calling a method.
* Disposing an instance of Editor class via 'using' operator or manually.

## Constructors

| Constructor | Beschrijving |
| --- | --- |
|  | [Editor(DocumentFormatBase format)](#Editor-com.groupdocs.editor.formats.abstraction.DocumentFormatBase-) | Initialiseert een nieuwe instantie van de [Editor](../../com.groupdocs.editor/editor)-klasse en maakt een nieuw leeg document aan op basis van het opgegeven formaat. |
|
|  | [Editor(InputStream document)](#Editor-java.io.InputStream-) | Initialiseert een nieuwe Editor‑instantie met het opgegeven invoerdocument (als een stream) |
|
|  | [Editor(InputStream document, ILoadOptions loadOptions)](#Editor-java.io.InputStream-com.groupdocs.editor.options.ILoadOptions-) | Initialiseert een nieuwe Editor‑instantie met het opgegeven invoerdocument (als een |
stream) met de laadopties en Editor‑instellingen
|
|  | [Editor(String filePath)](#Editor-java.lang.String-) | Initialiseert een nieuwe Editor‑instantie met het opgegeven invoerdocument (als een volledig bestandspad) |
|
|  | [Editor(String filePath, ILoadOptions loadOptions)](#Editor-java.lang.String-com.groupdocs.editor.options.ILoadOptions-) | Initialiseert een nieuwe Editor‑instantie met het opgegeven invoerdocument (als een volledig bestandspad) met de laadopties |
|
## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [edit(IEditOptions editOptions)](#edit-com.groupdocs.editor.options.IEditOptions-) | Opent een eerder geladen document voor bewerking met behulp van opgegeven formaat‑specifieke opties door een instantie van de ''‑klasse te genereren en terug te geven, die op zijn beurt methoden bevat voor het produceren van HTML‑markup en bijbehorende bronnen. |
|
|  | [edit()](#edit--) | Opent een eerder geladen document voor bewerking met standaardopties door |
een instantie van de 'EditableDocument'-klasse te genereren en terug te geven, die,
op zijn beurt methoden bevat voor het produceren van HTML‑markup en bijbehorende
bronnen.
|
|  | [save(EditableDocument inputDocument, OutputStream outputDocument, ISaveOptions saveOptions)](#save-com.groupdocs.editor.EditableDocument-java.io.OutputStream-com.groupdocs.editor.options.ISaveOptions-) | Converteert het opgegeven bewerkte document, weergegeven als een instantie van |
'EditableDocument', naar het resulterende document van het opgegeven formaat en
slaat de inhoud op naar de opgegeven stream
|
|  | [save(EditableDocument inputDocument, String filePath, ISaveOptions saveOptions)](#save-com.groupdocs.editor.EditableDocument-java.lang.String-com.groupdocs.editor.options.ISaveOptions-) | Converteert het opgegeven bewerkte document, weergegeven als een instantie van '', naar het resulterende document van het opgegeven formaat en slaat de inhoud op naar een bestand via het opgegeven bestandspad |
|
|  | [save(EditableDocument inputDocument, String filePath)](#save-com.groupdocs.editor.EditableDocument-java.lang.String-) | Converteert het opgegeven bewerkte document (weergegeven door een [EditableDocument](../../com.groupdocs.editor/editabledocument)) naar een output‑document waarvan het formaat wordt bepaald aan de hand van de bestandsnaamextensie, en slaat het op naar het opgegeven bestandspad. |
|
|  | [save(OutputStream outputDocument, WordProcessingSaveOptions saveOptions)](#save-java.io.OutputStream-com.groupdocs.editor.options.WordProcessingSaveOptions-) | Converteert het originele document na wijziging (bijvoorbeeld, |
FormFieldManager
(#getFormFieldManager.getFormFieldManager)),
naar het resulterende document van het opgegeven formaat en slaat de inhoud op naar de verstrekte stream.
|
|  | [save(OutputStream outputDocument)](#save-java.io.OutputStream-) | Sla de huidige documentinhoud op naar de opgegeven output‑stream. |
|
|  | [getDocumentInfo(String password)](#getDocumentInfo-java.lang.String-) | Geeft metadata terug over het document dat is geladen in deze 'Editor'-instantie |
|
|  | [dispose()](#dispose--) | Verwijdert deze instantie van Editor, zodat deze alle interne |
bronnen vrijgeeft en niet meer beschikbaar is voor verder gebruik
|
|  | [isDisposed()](#isDisposed--) | Geeft aan of deze Editor‑instantie al is verwijderd en niet kan worden |
nog gebruikt (true) of niet en is actief (false)
|
### Editor(DocumentFormatBase format) {#Editor-com.groupdocs.editor.formats.abstraction.DocumentFormatBase-}
```
public Editor(DocumentFormatBase format)
```


Initialiseert een nieuwe instantie van de [Editor](../../com.groupdocs.editor/editor)-klasse en maakt een nieuw leeg document aan op basis van het opgegeven formaat.

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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | format | [DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase) | vertegenwoordigt het bestandsformaat van het document dat zal worden aangemaakt. **Learn more** |

* More about file types supported by GroupDocs.Editor: [Document formats supported by GroupDocs.Editor](../https://docs.groupdocs.com/display/editornet/Supported+Document+Formats)
* More about GroupDocs.Editor for Java features: [Developer Guide](../https://docs.groupdocs.com/editor/java/developer-guide/)
|

### Editor(InputStream document) {#Editor-java.io.InputStream-}
```
public Editor(InputStream document)
```


Initialiseert een nieuwe Editor‑instantie met het opgegeven invoerdocument (als een stream)


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | document | java.io.InputStream | Delegate, die een stream met documentinhoud moet retourneren. Mag niet NULL zijn. **Learn more** |

* More about file types supported by GroupDocs.Editor: [Document formats supported by GroupDocs.Editor](../https://docs.groupdocs.com/display/editornet/Supported+Document+Formats)
* More about GroupDocs.Editor for Java features: [Developer Guide](../https://docs.groupdocs.com/editor/java/developer-guide/)
|

### Editor(InputStream document, ILoadOptions loadOptions) {#Editor-java.io.InputStream-com.groupdocs.editor.options.ILoadOptions-}
```
public Editor(InputStream document, ILoadOptions loadOptions)
```


Initialiseert een nieuwe Editor‑instantie met het opgegeven invoerdocument (als een
stream) met de laadopties en Editor‑instellingen


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | document | java.io.InputStream | Delegate, die een stream met documentinhoud moet retourneren. Mag niet NULL zijn. |
|
|  | loadOptions | [ILoadOptions](../../com.groupdocs.editor.options/iloadoptions) | Delegate, die documentlaadopties moet retourneren. Mag NULL zijn en kan null retourneren – in dat geval wordt het documenttype automatisch gedetecteerd en worden de standaardlaadopties voor dat type toegepast. |
|

### Editor(String filePath) {#Editor-java.lang.String-}
```
public Editor(String filePath)
```


Initialiseert een nieuwe Editor‑instantie met het opgegeven invoerdocument (als een volledig bestandspad)


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | filePath | java.lang.String | Volledig pad naar het bestand. Mag niet NULL zijn. Moet geldig zijn en het bestand moet bestaan. **Learn more** |

* More about file types supported by GroupDocs.Editor: [Document formats supported by GroupDocs.Editor](../https://docs.groupdocs.com/editor/java/supported-document-formats/)
* More about GroupDocs.Editor for Java features: [Developer Guide](../https://docs.groupdocs.com/editor/java/developer-guide/)
|

### Editor(String filePath, ILoadOptions loadOptions) {#Editor-java.lang.String-com.groupdocs.editor.options.ILoadOptions-}
```
public Editor(String filePath, ILoadOptions loadOptions)
```


Initialiseert een nieuwe Editor‑instantie met het opgegeven invoerdocument (als een volledig bestandspad) met de laadopties


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | filePath | java.lang.String | Volledig pad naar het bestand. Mag niet NULL zijn. Moet geldig zijn en het bestand moet bestaan. |
|
|  | loadOptions | [ILoadOptions](../../com.groupdocs.editor.options/iloadoptions) | Delegate, die documentlaadopties moet retourneren. Mag NULL zijn en kan null retourneren – in dat geval wordt het documenttype automatisch gedetecteerd en worden de standaardlaadopties voor dat type toegepast. **Learn more** |

* More about file types supported by GroupDocs.Editor: [Document formats supported by GroupDocs.Editor](../https://docs.groupdocs.com/editor/java/supported-document-formats/)
* More about GroupDocs.Editor for Java features: [Developer Guide](../https://docs.groupdocs.com/editor/java/developer-guide/)
* More about how to open and edit password-protected documents and document from different storages: [Load and edit documents using GroupDocs.Editor](../https://docs.groupdocs.com/editor/java/load-document/)
|

### edit(IEditOptions editOptions) {#edit-com.groupdocs.editor.options.IEditOptions-}
```
public final EditableDocument edit(IEditOptions editOptions)
```


Opent een eerder geladen document voor bewerking met behulp van opgegeven formaat‑specifieke opties door een instantie van de ''‑klasse te genereren en terug te geven, die op zijn beurt methoden bevat voor het produceren van HTML‑markup en bijbehorende bronnen.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | editOptions | [IEditOptions](../../com.groupdocs.editor.options/ieditoptions) | Formaat‑specifieke documentopties, die het conversieproces verfijnen. Mag niet NULL zijn. Mag niet conflicteren met eerder toegepaste laadopties. |


*** ** * ** ***

Wanneer het oorspronkelijke invoerdocument wordt geladen in de 'Editor'-instantie via de constructor, maakt deze methode het mogelijk het document te openen voor bewerking door het te converteren naar een tussenformaat, dat is ingekapseld in een instantie van de klasse 'EditableDocument'. 'EditableDocument', geretourneerd door deze methode, bevat alle benodigde methoden en eigenschappen voor het genereren van HTML-markup en bijbehorende bronnen (zoals afbeeldingen, lettertypen en stylesheets) in alle noodzakelijke configuraties voor het later doorgeven aan elke WYSIWYG HTML-editor. Deze overload verkrijgt bewerkingsopties die specifiek zijn voor familie‑formaten.

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


Opent een eerder geladen document voor bewerking met standaardopties door
een instantie van de 'EditableDocument'-klasse te genereren en terug te geven, die,
op zijn beurt methoden bevat voor het produceren van HTML‑markup en bijbehorende
bronnen.


**Returns:**
[EditableDocument](../../com.groupdocs.editor/editabledocument) - Instance of the 'EditableDocument' class, which encapsulates overall input document with all its resources in intermediate format. This method, if successfully finished, never returns NULL.


*** ** * ** ***

Wanneer het oorspronkelijke invoerdocument wordt geladen in de 'Editor'-instantie via de constructor, maakt deze methode het mogelijk het document te openen voor bewerking door het te converteren naar een tussenformaat, dat is ingekapseld in een instantie van de klasse 'EditableDocument'. 'EditableDocument', geretourneerd door deze methode, bevat alle benodigde methoden en eigenschappen voor het genereren van HTML-markup en bijbehorende bronnen (zoals afbeeldingen, lettertypen en stylesheets) in alle noodzakelijke configuraties voor het later doorgeven aan elke WYSIWYG HTML-editor. Deze overload past bewerkingsopties toe die standaard zijn voor het formaat waartoe het invoerdocument behoort.

<br />

**Learn more**

* More about editing documents using GroupDocs.Editor: [How to edit document using GroupDocs.Editor](../https://docs.groupdocs.com/editor/java/edit-document/)

### save(EditableDocument inputDocument, OutputStream outputDocument, ISaveOptions saveOptions) {#save-com.groupdocs.editor.EditableDocument-java.io.OutputStream-com.groupdocs.editor.options.ISaveOptions-}
```
public final void save(EditableDocument inputDocument, OutputStream outputDocument, ISaveOptions saveOptions)
```


Converteert het opgegeven bewerkte document, weergegeven als een instantie van
'EditableDocument', naar het resulterende document van het opgegeven formaat en
slaat de inhoud op naar de opgegeven stream


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | inputDocument | [EditableDocument](../../com.groupdocs.editor/editabledocument) | Versie van het invoerdocument, dat is bewerkt in een WYSIWYG HTML-editor en is opgeslagen als een instantie van de klasse 'EditableDocument', die moet worden geconverteerd naar een uitvoerdocument van een specifiek formaat. |
|
|  | outputDocument | java.io.OutputStream | Uitvoerstroom waarin de inhoud van het resulterende document wordt vastgelegd. Mag niet NULL zijn, mag niet worden verwijderd en moet schrijven ondersteunen. |
|
|  | saveOptions | [ISaveOptions](../../com.groupdocs.editor.options/isaveoptions) | Documentopslagopties die het formaat van het resulterende document definiëren, evenals algemene en formaat‑specifieke opslagopties. **Learn more** |

* More about saving document after edit using GroupDocs.Editor: [How to save edited document using GroupDocs.Editor](../https://docs.groupdocs.com/display/editornet/Save+document)
|

### save(EditableDocument inputDocument, String filePath, ISaveOptions saveOptions) {#save-com.groupdocs.editor.EditableDocument-java.lang.String-com.groupdocs.editor.options.ISaveOptions-}
```
public final void save(EditableDocument inputDocument, String filePath, ISaveOptions saveOptions)
```


Converteert het opgegeven bewerkte document, weergegeven als een instantie van '', naar het resulterende document van het opgegeven formaat en slaat de inhoud op naar een bestand via het opgegeven bestandspad


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | inputDocument | [EditableDocument](../../com.groupdocs.editor/editabledocument) | Versie van het invoerdocument, dat is bewerkt in een WYSIWYG HTML-editor en is opgeslagen als een instantie van de ''‑klasse, die moet worden geconverteerd naar een uitvoerdocument van een specifiek formaat. Mag niet null of verwijderd zijn. |
|
|  | filePath | java.lang.String | Pad naar het bestand waarin het uitvoerdocument wordt opgeslagen. Als er al een bestand met dezelfde naam bestaat, wordt het volledig overschreven. De tekenreeks met het pad mag niet null, leeg of alleen uit witruimtes bestaan. |
|
|  | saveOptions | [ISaveOptions](../../com.groupdocs.editor.options/isaveoptions) | Documentopslagopties die het formaat van het resulterende document definiëren, evenals algemene en formaat‑specifieke opslagopties. Mag niet null zijn. **Learn more** |

* More about saving document after edit using GroupDocs.Editor: [How to save edited document using GroupDocs.Editor](../https://docs.groupdocs.com/display/editornet/Save+document)
|

### save(EditableDocument inputDocument, String filePath) {#save-com.groupdocs.editor.EditableDocument-java.lang.String-}
```
public final void save(EditableDocument inputDocument, String filePath)
```


Converteert het opgegeven bewerkte document (weergegeven door een [EditableDocument](../../com.groupdocs.editor/editabledocument)) naar een output‑document waarvan het formaat wordt bepaald aan de hand van de bestandsnaamextensie, en slaat het op naar het opgegeven bestandspad.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | inputDocument | [EditableDocument](../../com.groupdocs.editor/editabledocument) | Versie van het invoerdocument dat is bewerkt in een WYSIWYG HTML-editor en is opgeslagen als een [EditableDocument](../../com.groupdocs.editor/editabledocument)-instantie. Mag niet null of verwijderd zijn. |
|
|  | filePath | java.lang.String | Pad naar het bestand waarin het uitvoerdocument wordt opgeslagen. Als er een bestand met dezelfde naam bestaat, wordt het volledig overschreven. De pad‑string mag niet null, leeg of alleen uit spaties bestaan. Omdat de standaard opslaan‑opties en uitvoerformaat worden bepaald aan de hand van deze bestandsnaam, moet het een geldige extensie hebben. |
|

### save(OutputStream outputDocument, WordProcessingSaveOptions saveOptions) {#save-java.io.OutputStream-com.groupdocs.editor.options.WordProcessingSaveOptions-}
```
public final OutputStream save(OutputStream outputDocument, WordProcessingSaveOptions saveOptions)
```


Converteert het originele document na wijziging (bijvoorbeeld,
FormFieldManager
(#getFormFieldManager.getFormFieldManager)),
naar het resulterende document van het opgegeven formaat en slaat de inhoud op naar de verstrekte stream.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | outputDocument | java.io.OutputStream | De stream waarnaar het uitvoerdocument wordt opgeslagen. Deze stream moet schrijfbaar zijn en zich aan het begin van de documentinhoud bevinden. Mag niet null zijn. |
|
|  | saveOptions | [WordProcessingSaveOptions](../../com.groupdocs.editor.options/wordprocessingsaveoptions) | Documentopslagopties die het formaat van het resulterende document definiëren, evenals algemene en formaat‑specifieke opslagopties. Mag niet null zijn. |

<br />

*** ** * ** ***

Als de  outputDocument  of  saveOptions  null is, wordt een NullPointerException gegooid. Als het te bewaren document ontbreekt, wordt een NullPointerException gegooid.

<br />

<br />

*** ** * ** ***

 **Learn more:** 

* 

<br />

|

**Returns:**
java.io.OutputStream - De stream die de opgeslagen documentinhoud bevat.

### save(OutputStream outputDocument) {#save-java.io.OutputStream-}
```
public final OutputStream save(OutputStream outputDocument)
```


Sla de huidige documentinhoud op naar de opgegeven output‑stream.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | outputDocument | java.io.OutputStream | De stream waarnaar de documentinhoud wordt opgeslagen. Dit mag niet null zijn. |

<br />

*** ** * ** ***

Deze methode kopieert de inhoud van de interne documentrepresentatie naar de opgegeven output‑stream. De oorspronkelijke positie van de stream wordt behouden na de opslagbewerking.

<br />

|

**Returns:**
java.io.OutputStream - De stream met de opgeslagen documentinhoud.

### getDocumentInfo(String password) {#getDocumentInfo-java.lang.String-}
```
public final IDocumentInfo getDocumentInfo(String password)
```


Geeft metadata terug over het document dat is geladen in deze 'Editor'-instantie


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | password | java.lang.String | Gebruiker kan een wachtwoord opgeven voor een document, als dit document versleuteld is met het wachtwoord. Kan NULL of een lege string zijn, wat gelijk staat aan het afwezige wachtwoord. Voor die documentformaten die geen wachtwoordbeveiligingsfunctie hebben, wordt dit argument genegeerd. Als het document versleuteld is, en het wachtwoord niet is opgegeven in deze parameter, maar het eerder is opgegeven in de laadopties bij het maken van deze instantie, wordt het gebruikt. **Learn more** |

* Learn more about obtaining document specific properties in code: [How to get document info using GroupDocs.Editor](../https://docs.groupdocs.com/editor/java/extracting-document-metainfo/)
|

**Returns:**
[IDocumentInfo](../../com.groupdocs.editor.metadata/idocumentinfo)
### dispose() {#dispose--}
```
public final void dispose()
```


Verwijdert deze instantie van Editor, zodat deze alle interne
bronnen vrijgeeft en niet meer beschikbaar is voor verder gebruik


### isDisposed() {#isDisposed--}
```
public final boolean isDisposed()
```


Geeft aan of deze Editor‑instantie al is verwijderd en niet kan worden
nog gebruikt (true) of niet en is actief (false)


**Returns:**
boolean
