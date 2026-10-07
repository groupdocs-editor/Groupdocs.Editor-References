---
title: "Editor"
second_title: "GroupDocs.Editor för Java API-referens"
description: "Huvudklass som kapslar in konverteringsmetoder."
type: docs
weight: 11
url: /sv/java/com.groupdocs.editor/editor/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.resources.IAuxDisposable](../../com.groupdocs.editor.htmlcss.resources/iauxdisposable)
```
public final class Editor implements IAuxDisposable
```

Huvudklass som kapslar in konverteringsmetoder.
Editor-klass tillhandahåller metoder för att läsa in, redigera och spara dokument i alla stödda format. Den är avyttringbar, så använd en 'using'-direktiv eller frigör dess resurser manuellt via 'Dispose()'-metodanrop. Dokumentladdning utförs via konstruktorer. Dokumentredigering – via metoden 'Edit', och sparande tillbaka till det resulterande dokumentet efter redigering – via metoden 'Save'.
**Editor class should be considered as an entry point and the root object of the GroupDocs.Editor. All operations are performed using this class. Typical usage of the Editor class for performing a full document editing pipeline is the next:**

* Load a document into the Editor instance through its constructor.
* Optionally, detect a document type using a method.
* Open a document for editing by calling an method and obtaining an instance of class from it..
* Editing a document content on client-side using any WYSIWYG HTML-editor.
* Creating a new instance of from edited document content.
* Saving an edited document to some output format by calling a method.
* Disposing an instance of Editor class via 'using' operator or manually.

## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
|  | [Editor(DocumentFormatBase format)](#Editor-com.groupdocs.editor.formats.abstraction.DocumentFormatBase-) | Initierar en ny instans av klassen [Editor](../../com.groupdocs.editor/editor) och skapar ett nytt tomt dokument baserat på det angivna formatet. |
|
|  | [Editor(InputStream document)](#Editor-java.io.InputStream-) | Initierar en ny Editor-instans med angivet inmatningsdokument (som en ström) |
|
|  | [Editor(InputStream document, ILoadOptions loadOptions)](#Editor-java.io.InputStream-com.groupdocs.editor.options.ILoadOptions-) | Initierar en ny Editor-instans med angivet inmatningsdokument (som en |
ström) med dess laddningsalternativ och Editor-inställningar
|
|  | [Editor(String filePath)](#Editor-java.lang.String-) | Initierar en ny Editor-instans med angivet inmatningsdokument (som en fullständig filsökväg) |
|
|  | [Editor(String filePath, ILoadOptions loadOptions)](#Editor-java.lang.String-com.groupdocs.editor.options.ILoadOptions-) | Initierar en ny Editor-instans med angivet inmatningsdokument (som en fullständig filsökväg) med dess laddningsalternativ |
|
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [edit(IEditOptions editOptions)](#edit-com.groupdocs.editor.options.IEditOptions-) | Öppnar ett tidigare inläst dokument för redigering med angivna format‑specifika alternativ genom att generera och returnera en instans av ''-klassen, som i sin tur innehåller metoder för att producera HTML‑markup och tillhörande resurser. |
|
|  | [edit()](#edit--) | Öppnar ett tidigare inläst dokument för redigering med standardalternativ genom att |
generera och returnera en instans av klassen 'EditableDocument', som,
i sin tur innehåller metoder för att producera HTML‑markup och tillhörande
resurser.
|
|  | [save(EditableDocument inputDocument, OutputStream outputDocument, ISaveOptions saveOptions)](#save-com.groupdocs.editor.EditableDocument-java.io.OutputStream-com.groupdocs.editor.options.ISaveOptions-) | Konverterar angivet redigerat dokument, representerat som en instans av |
'EditableDocument', till det resulterande dokumentet i angivet format och
sparar dess innehåll till angiven ström
|
|  | [save(EditableDocument inputDocument, String filePath, ISaveOptions saveOptions)](#save-com.groupdocs.editor.EditableDocument-java.lang.String-com.groupdocs.editor.options.ISaveOptions-) | Konverterar angivet redigerat dokument, representerat som en instans av '', till det resulterande dokumentet i angivet format och sparar dess innehåll till en fil via den angivna filsökvägen |
|
|  | [save(EditableDocument inputDocument, String filePath)](#save-com.groupdocs.editor.EditableDocument-java.lang.String-) | Konverterar det angivna redigerade dokumentet (representerat av en [EditableDocument](../../com.groupdocs.editor/editabledocument)) till ett utdata­dokument vars format bestäms av filnamnstillägget och sparar det till den angivna filsökvägen. |
|
|  | [save(OutputStream outputDocument, WordProcessingSaveOptions saveOptions)](#save-java.io.OutputStream-com.groupdocs.editor.options.WordProcessingSaveOptions-) | Konverterar originaldokumentet efter modifiering (till exempel, |
FormFieldManager
(#getFormFieldManager.getFormFieldManager)),
till det resulterande dokumentet i det angivna formatet och sparar dess innehåll till den angivna strömmen.
|
|  | [save(OutputStream outputDocument)](#save-java.io.OutputStream-) | Spara det aktuella dokumentets innehåll till den angivna utdata‑strömmen. |
|
|  | [getDocumentInfo(String password)](#getDocumentInfo-java.lang.String-) | Returnerar metadata om dokumentet som laddades till denna 'Editor'-instans |
|
|  | [dispose()](#dispose--) | Avslutar denna instans av Editor, så att den frigör all intern |
resurser och blir otillgängliga för vidare användning
|
|  | [isDisposed()](#isDisposed--) | Indikerar om den här Editor-instansen redan har avlägsnats och inte kan vara |
användas längre (true) eller inte och är aktiv (false)
|
### Editor(DocumentFormatBase format) {#Editor-com.groupdocs.editor.formats.abstraction.DocumentFormatBase-}
```
public Editor(DocumentFormatBase format)
```


Initierar en ny instans av klassen [Editor](../../com.groupdocs.editor/editor) och skapar ett nytt tomt dokument baserat på det angivna formatet.

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
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | format | [DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase) | representerar filformatet för dokumentet som kommer att skapas. **Learn more** |

* More about file types supported by GroupDocs.Editor: [Document formats supported by GroupDocs.Editor](../https://docs.groupdocs.com/display/editornet/Supported+Document+Formats)
* More about GroupDocs.Editor for Java features: [Developer Guide](../https://docs.groupdocs.com/editor/java/developer-guide/)
|

### Editor(InputStream document) {#Editor-java.io.InputStream-}
```
public Editor(InputStream document)
```


Initierar en ny Editor-instans med angivet inmatningsdokument (som en ström)


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | dokument | java.io.InputStream | Delegat som ska returnera en ström med dokumentinnehåll. Får inte vara NULL. **Learn more** |

* More about file types supported by GroupDocs.Editor: [Document formats supported by GroupDocs.Editor](../https://docs.groupdocs.com/display/editornet/Supported+Document+Formats)
* More about GroupDocs.Editor for Java features: [Developer Guide](../https://docs.groupdocs.com/editor/java/developer-guide/)
|

### Editor(InputStream document, ILoadOptions loadOptions) {#Editor-java.io.InputStream-com.groupdocs.editor.options.ILoadOptions-}
```
public Editor(InputStream document, ILoadOptions loadOptions)
```


Initierar en ny Editor-instans med angivet inmatningsdokument (som en
ström) med dess laddningsalternativ och Editor-inställningar


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | dokument | java.io.InputStream | Delegat som ska returnera en ström med dokumentinnehåll. Får inte vara NULL. |
|
|  | loadOptions | [ILoadOptions](../../com.groupdocs.editor.options/iloadoptions) | Delegat som ska returnera dokumentets laddningsalternativ. Kan vara NULL och kan returnera null – i så fall kommer dokumenttypen att upptäckas automatiskt och standardladdningsalternativ för den typen kommer att tillämpas. |
|

### Editor(String filePath) {#Editor-java.lang.String-}
```
public Editor(String filePath)
```


Initierar en ny Editor-instans med angivet inmatningsdokument (som en fullständig filsökväg)


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | filePath | java.lang.String | Fullständig sökväg till filen. Får inte vara NULL. Ska vara giltig och filen ska finnas. **Learn more** |

* More about file types supported by GroupDocs.Editor: [Document formats supported by GroupDocs.Editor](../https://docs.groupdocs.com/editor/java/supported-document-formats/)
* More about GroupDocs.Editor for Java features: [Developer Guide](../https://docs.groupdocs.com/editor/java/developer-guide/)
|

### Editor(String filePath, ILoadOptions loadOptions) {#Editor-java.lang.String-com.groupdocs.editor.options.ILoadOptions-}
```
public Editor(String filePath, ILoadOptions loadOptions)
```


Initierar en ny Editor-instans med angivet inmatningsdokument (som en fullständig filsökväg) med dess laddningsalternativ


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | filePath | java.lang.String | Fullständig sökväg till filen. Får inte vara NULL. Ska vara giltig och filen ska finnas. |
|
|  | loadOptions | [ILoadOptions](../../com.groupdocs.editor.options/iloadoptions) | Delegat som ska returnera dokumentets laddningsalternativ. Kan vara NULL och kan returnera null – i så fall kommer dokumenttypen att upptäckas automatiskt och standardladdningsalternativ för den typen kommer att tillämpas. **Learn more** |

* More about file types supported by GroupDocs.Editor: [Document formats supported by GroupDocs.Editor](../https://docs.groupdocs.com/editor/java/supported-document-formats/)
* More about GroupDocs.Editor for Java features: [Developer Guide](../https://docs.groupdocs.com/editor/java/developer-guide/)
* More about how to open and edit password-protected documents and document from different storages: [Load and edit documents using GroupDocs.Editor](../https://docs.groupdocs.com/editor/java/load-document/)
|

### edit(IEditOptions editOptions) {#edit-com.groupdocs.editor.options.IEditOptions-}
```
public final EditableDocument edit(IEditOptions editOptions)
```


Öppnar ett tidigare inläst dokument för redigering med angivna format‑specifika alternativ genom att generera och returnera en instans av ''-klassen, som i sin tur innehåller metoder för att producera HTML‑markup och tillhörande resurser.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | editOptions | [IEditOptions](../../com.groupdocs.editor.options/ieditoptions) | Format‑specifika dokumentalternativ, som möjliggör finjustering av konverteringsprocessen. Får inte vara NULL. Får inte stå i konflikt med tidigare tillämpade laddningsalternativ. |


*** ** * ** ***

När det ursprungliga dokumentet laddas till 'Editor'-instansen via konstruktorn, möjliggör den här metoden att öppna dokumentet för redigering genom att konvertera det till ett mellanformat som kapslas in i en instans av klassen 'EditableDocument'. 'EditableDocument', som returneras från den här metoden, innehåller alla nödvändiga metoder och egenskaper för att producera HTML‑markup och motsvarande resurser (såsom bilder, teckensnitt och stilmallar) i alla nödvändiga konfigurationer för att därefter kunna överföra dem till någon WYSIWYG‑HTML‑editor. Detta överlagring hämtar redigeringsalternativ som är specifika för familjeformat.

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


Öppnar ett tidigare inläst dokument för redigering med standardalternativ genom att
generera och returnera en instans av klassen 'EditableDocument', som,
i sin tur innehåller metoder för att producera HTML‑markup och tillhörande
resurser.


**Returns:**
[EditableDocument](../../com.groupdocs.editor/editabledocument) - Instance of the 'EditableDocument' class, which encapsulates overall input document with all its resources in intermediate format. This method, if successfully finished, never returns NULL.


*** ** * ** ***

När det ursprungliga dokumentet laddas till 'Editor'-instansen via konstruktorn, möjliggör den här metoden att öppna dokumentet för redigering genom att konvertera det till ett mellanformat som kapslas in i en instans av klassen 'EditableDocument'. 'EditableDocument', som returneras från den här metoden, innehåller alla nödvändiga metoder och egenskaper för att producera HTML‑markup och motsvarande resurser (såsom bilder, teckensnitt och stilmallar) i alla nödvändiga konfigurationer för att därefter kunna överföra dem till någon WYSIWYG‑HTML‑editor. Denna överlagring tillämpar redigeringsalternativ som är standard för det format som det inmatade dokumentet tillhör.

<br />

**Learn more**

* More about editing documents using GroupDocs.Editor: [How to edit document using GroupDocs.Editor](../https://docs.groupdocs.com/editor/java/edit-document/)

### save(EditableDocument inputDocument, OutputStream outputDocument, ISaveOptions saveOptions) {#save-com.groupdocs.editor.EditableDocument-java.io.OutputStream-com.groupdocs.editor.options.ISaveOptions-}
```
public final void save(EditableDocument inputDocument, OutputStream outputDocument, ISaveOptions saveOptions)
```


Konverterar angivet redigerat dokument, representerat som en instans av
'EditableDocument', till det resulterande dokumentet i angivet format och
sparar dess innehåll till angiven ström


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | inputDocument | [EditableDocument](../../com.groupdocs.editor/editabledocument) | Version av inmatningsdokumentet som redigerades i en WYSIWYG‑HTML‑editor och lagras som en instans av klassen 'EditableDocument', som ska konverteras till ett utdata‑dokument av ett specifikt format |
|
|  | outputDocument | java.io.OutputStream | Utdatastream, i vilken innehållet i det resulterande dokumentet kommer att registreras. Får inte vara NULL, avlägsnad, och bör stödja skrivning. |
|
|  | saveOptions | [ISaveOptions](../../com.groupdocs.editor.options/isaveoptions) | Dokumentets sparalternativ, som definierar formatet för det resulterande dokumentet, samt allmänna och format‑specifika sparalternativ. **Learn more** |

* More about saving document after edit using GroupDocs.Editor: [How to save edited document using GroupDocs.Editor](../https://docs.groupdocs.com/display/editornet/Save+document)
|

### save(EditableDocument inputDocument, String filePath, ISaveOptions saveOptions) {#save-com.groupdocs.editor.EditableDocument-java.lang.String-com.groupdocs.editor.options.ISaveOptions-}
```
public final void save(EditableDocument inputDocument, String filePath, ISaveOptions saveOptions)
```


Konverterar angivet redigerat dokument, representerat som en instans av '', till det resulterande dokumentet i angivet format och sparar dess innehåll till en fil via den angivna filsökvägen


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | inputDocument | [EditableDocument](../../com.groupdocs.editor/editabledocument) | Version av inmatningsdokumentet som redigerades i en WYSIWYG‑HTML‑editor och lagras som en instans av ''‑klassen, som ska konverteras till ett utdata‑dokument av ett specifikt format. Får inte vara null eller avlägsnad. |
|
|  | filePath | java.lang.String | Sökväg till filen där det resulterande dokumentet kommer att sparas. Om en fil med samma namn finns, kommer den att skrivas över helt. Strängen med sökväg får inte vara null, tom eller bara bestå av blanksteg. |
|
|  | saveOptions | [ISaveOptions](../../com.groupdocs.editor.options/isaveoptions) | Alternativ för dokumentlagring som definierar formatet på det resulterande dokumentet samt allmänna och format‑specifika lagringsalternativ. Får inte vara null. **Läs mer** |

* More about saving document after edit using GroupDocs.Editor: [How to save edited document using GroupDocs.Editor](../https://docs.groupdocs.com/display/editornet/Save+document)
|

### save(EditableDocument inputDocument, String filePath) {#save-com.groupdocs.editor.EditableDocument-java.lang.String-}
```
public final void save(EditableDocument inputDocument, String filePath)
```


Konverterar det angivna redigerade dokumentet (representerat av en [EditableDocument](../../com.groupdocs.editor/editabledocument)) till ett utdata­dokument vars format bestäms av filnamnstillägget och sparar det till den angivna filsökvägen.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | inputDocument | [EditableDocument](../../com.groupdocs.editor/editabledocument) | Version av inmatningsdokumentet som redigerades i en WYSIWYG HTML‑editor och lagras som en [EditableDocument](../../com.groupdocs.editor/editabledocument)-instans. Får inte vara null eller disponerad. |
|
|  | filePath | java.lang.String | Sökväg till filen där det resulterande dokumentet ska sparas. Om en fil med samma namn finns, kommer den att skrivas över helt. Sökvägssträngen får inte vara null, tom eller bara bestå av blanksteg. Eftersom standardalternativen för sparande och utdataformatet bestäms av detta filnamn, måste det ha en giltig filändelse. |
|

### save(OutputStream outputDocument, WordProcessingSaveOptions saveOptions) {#save-java.io.OutputStream-com.groupdocs.editor.options.WordProcessingSaveOptions-}
```
public final OutputStream save(OutputStream outputDocument, WordProcessingSaveOptions saveOptions)
```


Konverterar originaldokumentet efter modifiering (till exempel,
FormFieldManager
(#getFormFieldManager.getFormFieldManager)),
till det resulterande dokumentet i det angivna formatet och sparar dess innehåll till den angivna strömmen.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | outputDocument | java.io.OutputStream | Strömmen som det resulterande dokumentet ska sparas till. Denna ström bör vara skrivbar och placerad i början av dokumentets innehåll. Får inte vara null. |
|
|  | saveOptions | [WordProcessingSaveOptions](../../com.groupdocs.editor.options/wordprocessingsaveoptions) | Alternativ för dokumentlagring som definierar formatet på det resulterande dokumentet samt allmänna och format‑specifika lagringsalternativ. Får inte vara null. |

<br />

*** ** * ** ***

Om  outputDocument  eller  saveOptions  är null kastas ett NullPointerException. Om dokumentet som ska sparas saknas kastas ett NullPointerException.

<br />

<br />

*** ** * ** ***

 **Learn more:** 

* 

<br />

|

**Returns:**
java.io.OutputStream - Strömmen som innehåller det sparade dokumentets innehåll.

### save(OutputStream outputDocument) {#save-java.io.OutputStream-}
```
public final OutputStream save(OutputStream outputDocument)
```


Spara det aktuella dokumentets innehåll till den angivna utdata‑strömmen.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | outputDocument | java.io.OutputStream | Strömmen som dokumentinnehållet ska sparas till. Detta får inte vara null. |

<br />

*** ** * ** ***

Denna metod kopierar innehållet från den interna dokumentrepresentationen till den angivna utströmmen. Strömmens ursprungliga position bevaras efter sparoperationen.

<br />

|

**Returns:**
java.io.OutputStream - Strömmen med det sparade dokumentets innehåll.

### getDocumentInfo(String password) {#getDocumentInfo-java.lang.String-}
```
public final IDocumentInfo getDocumentInfo(String password)
```


Returnerar metadata om dokumentet som laddades till denna 'Editor'-instans


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | lösenord | java.lang.String | Användaren kan ange ett lösenord för ett dokument om dokumentet är krypterat med lösenordet. Kan vara NULL eller en tom sträng, vilket motsvarar avsaknad av lösenord. För de dokumentformat som inte har stöd för lösenordsskydd kommer detta argument att ignoreras. Om dokumentet är krypterat och lösenordet inte anges i denna parameter, men det angavs tidigare i laddningsalternativen när denna instans skapades, kommer det att användas. **Läs mer** |

* Learn more about obtaining document specific properties in code: [How to get document info using GroupDocs.Editor](../https://docs.groupdocs.com/editor/java/extracting-document-metainfo/)
|

**Returns:**
[IDocumentInfo](../../com.groupdocs.editor.metadata/idocumentinfo)
### dispose() {#dispose--}
```
public final void dispose()
```


Avslutar denna instans av Editor, så att den frigör all intern
resurser och blir otillgängliga för vidare användning


### isDisposed() {#isDisposed--}
```
public final boolean isDisposed()
```


Indikerar om den här Editor-instansen redan har avlägsnats och inte kan vara
användas längre (true) eller inte och är aktiv (false)


**Returns:**
boolean
