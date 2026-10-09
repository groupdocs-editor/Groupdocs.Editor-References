---
title: "Editor"
second_title: "GroupDocs.Editor για Node.js μέσω Java API Reference"
description: "Κύρια κλάση που περιλαμβάνει μεθόδους μετατροπής."
type: docs
weight: 11
url: /el/nodejs-java/com.groupdocs.editor/editor/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.resources.IAuxDisposable](../../com.groupdocs.editor.htmlcss.resources/iauxdisposable)
```
public final class Editor implements IAuxDisposable
```

Κύρια κλάση, η οποία ενσωματώνει μεθόδους μετατροπής.
Η κλάση Editor παρέχει μεθόδους για τη φόρτωση, την επεξεργασία και την αποθήκευση εγγράφων όλων των υποστηριζόμενων μορφών. Είναι διαχειρίσιμη, επομένως χρησιμοποιήστε την οδηγία 'using' ή απελευθερώστε τους πόρους της χειροκίνητα μέσω της κλήσης μεθόδου 'Dispose()'. Η φόρτωση εγγράφων πραγματοποιείται μέσω κατασκευαστών. Η επεξεργασία εγγράφων - μέσω της μεθόδου 'Edit', και η αποθήκευση πίσω στο τελικό έγγραφο μετά την επεξεργασία - μέσω της μεθόδου 'Save'.
**Editor class should be considered as an entry point and the root object of the GroupDocs.Editor. All operations are performed using this class. Typical usage of the Editor class for performing a full document editing pipeline is the next:**

* Load a document into the Editor instance through its constructor.
* Optionally, detect a document type using a method.
* Open a document for editing by calling an method and obtaining an instance of class from it..
* Editing a document content on client-side using any WYSIWYG HTML-editor.
* Creating a new instance of from edited document content.
* Saving an edited document to some output format by calling a method.
* Disposing an instance of Editor class via 'using' operator or manually.

## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
|  | [Editor(DocumentFormatBase format)](#Editor-com.groupdocs.editor.formats.abstraction.DocumentFormatBase-) | Αρχικοποιεί μια νέα παρουσία της κλάσης [Editor](../../com.groupdocs.editor/editor) και δημιουργεί ένα νέο κενό έγγραφο βάσει της καθορισμένης μορφής. |
|
|  | [Editor(InputStream document)](#Editor-java.io.InputStream-) | Αρχικοποιεί νέα παρουσία του Editor με το καθορισμένο έγγραφο εισόδου (ως ροή) |
|
|  | [Editor(InputStream document, ILoadOptions loadOptions)](#Editor-java.io.InputStream-com.groupdocs.editor.options.ILoadOptions-) | Αρχικοποιεί νέα παρουσία του Editor με το καθορισμένο έγγραφο εισόδου (ως ένα |
stream) με τις επιλογές φόρτωσης και τις ρυθμίσεις του Editor
|
|  | [Editor(String filePath)](#Editor-java.lang.String-) | Αρχικοποιεί νέο αντικείμενο Editor με το καθορισμένο έγγραφο εισόδου (ως πλήρης διαδρομή αρχείου) |
|
|  | [Editor(String filePath, ILoadOptions loadOptions)](#Editor-java.lang.String-com.groupdocs.editor.options.ILoadOptions-) | Αρχικοποιεί νέο αντικείμενο Editor με το καθορισμένο έγγραφο εισόδου (ως πλήρης διαδρομή αρχείου) με τις επιλογές φόρτωσής του |
|
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [edit(IEditOptions editOptions)](#edit-com.groupdocs.editor.options.IEditOptions-) | Ανοίγει ένα προηγουμένως φορτωμένο έγγραφο για επεξεργασία χρησιμοποιώντας τις καθορισμένες επιλογές ειδικές για μορφή, δημιουργώντας και επιστρέφοντας ένα αντικείμενο της κλάσης '' , το οποίο, με τη σειρά του, περιέχει μεθόδους για τη δημιουργία σήμανσης HTML και σχετικών πόρων. |
|
|  | [edit()](#edit--) | Ανοίγει ένα προηγουμένως φορτωμένο έγγραφο για επεξεργασία χρησιμοποιώντας τις προεπιλεγμένες επιλογές με |
δημιουργώντας και επιστρέφοντας ένα αντικείμενο της κλάσης 'EditableDocument', το οποίο,
με τη σειρά του, περιέχει μεθόδους για τη δημιουργία σήμανσης HTML και σχετικών
πόρων.
|
|  | [save(EditableDocument inputDocument, OutputStream outputDocument, ISaveOptions saveOptions)](#save-com.groupdocs.editor.EditableDocument-java.io.OutputStream-com.groupdocs.editor.options.ISaveOptions-) | Μετατρέπει το καθορισμένο επεξεργασμένο έγγραφο, που αντιπροσωπεύεται ως αντικείμενο της |
'EditableDocument', στο τελικό έγγραφο της καθορισμένης μορφής και
αποθηκεύει το περιεχόμενό του σε καθορισμένο stream
|
|  | [save(EditableDocument inputDocument, String filePath, ISaveOptions saveOptions)](#save-com.groupdocs.editor.EditableDocument-java.lang.String-com.groupdocs.editor.options.ISaveOptions-) | Μετατρέπει το καθορισμένο επεξεργασμένο έγγραφο, που αντιπροσωπεύεται ως αντικείμενο της '', στο τελικό έγγραφο της καθορισμένης μορφής και αποθηκεύει το περιεχόμενό του σε αρχείο με την καθορισμένη διαδρομή αρχείου |
|
|  | [save(EditableDocument inputDocument, String filePath)](#save-com.groupdocs.editor.EditableDocument-java.lang.String-) | Μετατρέπει το καθορισμένο επεξεργασμένο έγγραφο (που αντιπροσωπεύεται από ένα [EditableDocument](../../com.groupdocs.editor/editabledocument)) σε ένα έγγραφο εξόδου του οποίου η μορφή καθορίζεται από την επέκταση του ονόματος αρχείου, και το αποθηκεύει στην καθορισμένη διαδρομή αρχείου. |
|
|  | [save(OutputStream outputDocument, WordProcessingSaveOptions saveOptions)](#save-java.io.OutputStream-com.groupdocs.editor.options.WordProcessingSaveOptions-) | Μετατρέπει το αρχικό έγγραφο μετά την τροποποίηση (για παράδειγμα, |
FormFieldManager
(#getFormFieldManager.getFormFieldManager)),
στο τελικό έγγραφο της καθορισμένης μορφής και αποθηκεύει το περιεχόμενό του στο παρεχόμενο stream.
|
|  | [save(OutputStream outputDocument)](#save-java.io.OutputStream-) | Αποθηκεύστε το τρέχον περιεχόμενο του εγγράφου στο καθορισμένο stream εξόδου. |
|
|  | [getDocumentInfo(String password)](#getDocumentInfo-java.lang.String-) | Επιστρέφει μεταδεδομένα σχετικά με το έγγραφο, που φορτώθηκε σε αυτό το αντικείμενο 'Editor' |
|
|  | [dispose()](#dispose--) | Αποδεσμεύει αυτό το αντικείμενο Editor, ώστε να απελευθερώσει όλους τους εσωτερικούς |
πόρους και να γίνει μη διαθέσιμο για περαιτέρω χρήση
|
|  | [isDisposed()](#isDisposed--) | Δείχνει εάν αυτό το αντικείμενο Editor έχει ήδη αποδεσμευτεί και δεν μπορεί να |
χρησιμοποιηθεί ξανά (true) ή όχι και είναι ενεργό (false)
|
### Editor(DocumentFormatBase format) {#Editor-com.groupdocs.editor.formats.abstraction.DocumentFormatBase-}
```
public Editor(DocumentFormatBase format)
```


Αρχικοποιεί μια νέα παρουσία της κλάσης [Editor](../../com.groupdocs.editor/editor) και δημιουργεί ένα νέο κενό έγγραφο βάσει της καθορισμένης μορφής.

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
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | format | [DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase) | αντιπροσωπεύει τη μορφή αρχείου του εγγράφου που θα δημιουργηθεί. **Μάθετε περισσότερα** |

* More about file types supported by GroupDocs.Editor: [Document formats supported by GroupDocs.Editor](../https://docs.groupdocs.com/display/editornet/Supported+Document+Formats)
* More about GroupDocs.Editor for Java features: [Developer Guide](../https://docs.groupdocs.com/editor/java/developer-guide/)
|

### Editor(InputStream document) {#Editor-java.io.InputStream-}
```
public Editor(InputStream document)
```


Αρχικοποιεί νέα παρουσία του Editor με το καθορισμένο έγγραφο εισόδου (ως ροή)


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | εγγράφου | java.io.InputStream | Αντιπρόσωπος, που πρέπει να επιστρέφει ένα stream με το περιεχόμενο του εγγράφου. Δεν πρέπει να είναι NULL. **Μάθετε περισσότερα** |

* More about file types supported by GroupDocs.Editor: [Document formats supported by GroupDocs.Editor](../https://docs.groupdocs.com/display/editornet/Supported+Document+Formats)
* More about GroupDocs.Editor for Java features: [Developer Guide](../https://docs.groupdocs.com/editor/java/developer-guide/)
|

### Editor(InputStream document, ILoadOptions loadOptions) {#Editor-java.io.InputStream-com.groupdocs.editor.options.ILoadOptions-}
```
public Editor(InputStream document, ILoadOptions loadOptions)
```


Αρχικοποιεί νέα παρουσία του Editor με το καθορισμένο έγγραφο εισόδου (ως ένα
stream) με τις επιλογές φόρτωσης και τις ρυθμίσεις του Editor


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | εγγράφου | java.io.InputStream | Αντιπρόσωπος, που πρέπει να επιστρέφει ένα stream με το περιεχόμενο του εγγράφου. Δεν πρέπει να είναι NULL. |
|
|  | loadOptions | [ILoadOptions](../../com.groupdocs.editor.options/iloadoptions) | Delegate, που πρέπει να επιστρέφει επιλογές φόρτωσης εγγράφου. Μπορεί να είναι NULL και να επιστρέφει null - σε αυτήν την περίπτωση ο τύπος του εγγράφου θα ανιχνευθεί αυτόματα και θα εφαρμοστούν οι προεπιλεγμένες επιλογές φόρτωσης για αυτόν τον τύπο. |
|

### Editor(String filePath) {#Editor-java.lang.String-}
```
public Editor(String filePath)
```


Αρχικοποιεί νέο αντικείμενο Editor με το καθορισμένο έγγραφο εισόδου (ως πλήρης διαδρομή αρχείου)


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | filePath | java.lang.String | Πλήρης διαδρομή προς το αρχείο. Δεν πρέπει να είναι NULL. Πρέπει να είναι έγκυρη και το αρχείο πρέπει να υπάρχει. **Learn more** |

* More about file types supported by GroupDocs.Editor: [Document formats supported by GroupDocs.Editor](../https://docs.groupdocs.com/editor/java/supported-document-formats/)
* More about GroupDocs.Editor for Java features: [Developer Guide](../https://docs.groupdocs.com/editor/java/developer-guide/)
|

### Editor(String filePath, ILoadOptions loadOptions) {#Editor-java.lang.String-com.groupdocs.editor.options.ILoadOptions-}
```
public Editor(String filePath, ILoadOptions loadOptions)
```


Αρχικοποιεί νέο αντικείμενο Editor με το καθορισμένο έγγραφο εισόδου (ως πλήρης διαδρομή αρχείου) με τις επιλογές φόρτωσής του


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | filePath | java.lang.String | Πλήρης διαδρομή προς το αρχείο. Δεν πρέπει να είναι NULL. Πρέπει να είναι έγκυρη και το αρχείο πρέπει να υπάρχει. |
|
|  | loadOptions | [ILoadOptions](../../com.groupdocs.editor.options/iloadoptions) | Delegate, που πρέπει να επιστρέφει επιλογές φόρτωσης εγγράφου. Μπορεί να είναι NULL και να επιστρέφει null - σε αυτήν την περίπτωση ο τύπος του εγγράφου θα ανιχνευθεί αυτόματα και θα εφαρμοστούν οι προεπιλεγμένες επιλογές φόρτωσης για αυτόν τον τύπο. **Learn more** |

* More about file types supported by GroupDocs.Editor: [Document formats supported by GroupDocs.Editor](../https://docs.groupdocs.com/editor/java/supported-document-formats/)
* More about GroupDocs.Editor for Java features: [Developer Guide](../https://docs.groupdocs.com/editor/java/developer-guide/)
* More about how to open and edit password-protected documents and document from different storages: [Load and edit documents using GroupDocs.Editor](../https://docs.groupdocs.com/editor/java/load-document/)
|

### edit(IEditOptions editOptions) {#edit-com.groupdocs.editor.options.IEditOptions-}
```
public final EditableDocument edit(IEditOptions editOptions)
```


Ανοίγει ένα προηγουμένως φορτωμένο έγγραφο για επεξεργασία χρησιμοποιώντας τις καθορισμένες επιλογές ειδικές για μορφή, δημιουργώντας και επιστρέφοντας ένα αντικείμενο της κλάσης '' , το οποίο, με τη σειρά του, περιέχει μεθόδους για τη δημιουργία σήμανσης HTML και σχετικών πόρων.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | editOptions | [IEditOptions](../../com.groupdocs.editor.options/ieditoptions) | Επιλογές εγγράφου ειδικές για μορφή, που επιτρέπουν τη βελτιστοποίηση της διαδικασίας μετατροπής. Δεν πρέπει να είναι NULL. Δεν πρέπει να συγκρούονται με τις προηγουμένως εφαρμοσμένες επιλογές φόρτωσης. |


*** ** * ** ***

Όταν το αρχικό έγγραφο εισόδου φορτώνεται στην παρουσία 'Editor' μέσω του κατασκευαστή, αυτή η μέθοδος επιτρέπει το άνοιγμα του εγγράφου για επεξεργασία μετατρέποντάς το σε ενδιάμεση μορφή, η οποία ενσωματώνεται σε μια παρουσία της κλάσης 'EditableDocument'. Η 'EditableDocument', που επιστρέφεται από αυτή τη μέθοδο, περιέχει όλες τις απαραίτητες μεθόδους και ιδιότητες για την παραγωγή HTML markup και των αντίστοιχων πόρων (όπως εικόνες, γραμματοσειρές και φύλλα στυλ) σε όλες τις απαραίτητες διαμορφώσεις για την επακόλουθη μεταφορά τους σε οποιονδήποτε WYSIWYG HTML-editor. Αυτή η υπερφόρτωση λαμβάνει επιλογές επεξεργασίας, οι οποίες είναι συγκεκριμένες για τις οικογενειακές μορφές.

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


Ανοίγει ένα προηγουμένως φορτωμένο έγγραφο για επεξεργασία χρησιμοποιώντας τις προεπιλεγμένες επιλογές με
δημιουργώντας και επιστρέφοντας ένα αντικείμενο της κλάσης 'EditableDocument', το οποίο,
με τη σειρά του, περιέχει μεθόδους για τη δημιουργία σήμανσης HTML και σχετικών
πόρων.


**Returns:**
[EditableDocument](../../com.groupdocs.editor/editabledocument) - Instance of the 'EditableDocument' class, which encapsulates overall input document with all its resources in intermediate format. This method, if successfully finished, never returns NULL.


*** ** * ** ***

Όταν το αρχικό έγγραφο εισόδου φορτώνεται στην παρουσία 'Editor' μέσω του κατασκευαστή, αυτή η μέθοδος επιτρέπει το άνοιγμα του εγγράφου για επεξεργασία μετατρέποντάς το σε ενδιάμεση μορφή, η οποία ενσωματώνεται σε μια παρουσία της κλάσης 'EditableDocument'. Η 'EditableDocument', που επιστρέφεται από αυτή τη μέθοδο, περιέχει όλες τις απαραίτητες μεθόδους και ιδιότητες για την παραγωγή HTML markup και των αντίστοιχων πόρων (όπως εικόνες, γραμματοσειρές και φύλλα στυλ) σε όλες τις απαραίτητες διαμορφώσεις για την επακόλουθη μεταφορά τους σε οποιονδήποτε WYSIWYG HTML-editor. Αυτή η υπερφόρτωση εφαρμόζει επιλογές επεξεργασίας, οι οποίες είναι προεπιλεγμένες για τη μορφή στην οποία ανήκει το έγγραφο εισόδου.

<br />

**Learn more**

* More about editing documents using GroupDocs.Editor: [How to edit document using GroupDocs.Editor](../https://docs.groupdocs.com/editor/java/edit-document/)

### save(EditableDocument inputDocument, OutputStream outputDocument, ISaveOptions saveOptions) {#save-com.groupdocs.editor.EditableDocument-java.io.OutputStream-com.groupdocs.editor.options.ISaveOptions-}
```
public final void save(EditableDocument inputDocument, OutputStream outputDocument, ISaveOptions saveOptions)
```


Μετατρέπει το καθορισμένο επεξεργασμένο έγγραφο, που αντιπροσωπεύεται ως αντικείμενο της
'EditableDocument', στο τελικό έγγραφο της καθορισμένης μορφής και
αποθηκεύει το περιεχόμενό του σε καθορισμένο stream


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | inputDocument | [EditableDocument](../../com.groupdocs.editor/editabledocument) | Έκδοση του εγγράφου εισόδου, που επεξεργάστηκε σε WYSIWYG HTML-editor και αποθηκεύτηκε ως παρουσία της κλάσης 'EditableDocument', η οποία πρέπει να μετατραπεί σε έγγραφο εξόδου κάποιου συγκεκριμένου τύπου. |
|
|  | outputDocument | java.io.OutputStream | Ροή εξόδου, στην οποία θα καταγραφεί το περιεχόμενο του τελικού εγγράφου. Δεν πρέπει να είναι NULL, να έχει διαγραφεί, και πρέπει να υποστηρίζει εγγραφή. |
|
|  | saveOptions | [ISaveOptions](../../com.groupdocs.editor.options/isaveoptions) | Επιλογές αποθήκευσης εγγράφου, που καθορίζουν τη μορφή του τελικού εγγράφου, καθώς και γενικές και ειδικές για μορφή επιλογές αποθήκευσης. **Learn more** |

* More about saving document after edit using GroupDocs.Editor: [How to save edited document using GroupDocs.Editor](../https://docs.groupdocs.com/display/editornet/Save+document)
|

### save(EditableDocument inputDocument, String filePath, ISaveOptions saveOptions) {#save-com.groupdocs.editor.EditableDocument-java.lang.String-com.groupdocs.editor.options.ISaveOptions-}
```
public final void save(EditableDocument inputDocument, String filePath, ISaveOptions saveOptions)
```


Μετατρέπει το καθορισμένο επεξεργασμένο έγγραφο, που αντιπροσωπεύεται ως αντικείμενο της '', στο τελικό έγγραφο της καθορισμένης μορφής και αποθηκεύει το περιεχόμενό του σε αρχείο με την καθορισμένη διαδρομή αρχείου


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | inputDocument | [EditableDocument](../../com.groupdocs.editor/editabledocument) | Έκδοση του εγγράφου εισόδου, που επεξεργάστηκε σε WYSIWYG HTML-editor και αποθηκεύτηκε ως παρουσία της κλάσης '' , η οποία πρέπει να μετατραπεί σε έγγραφο εξόδου κάποιου συγκεκριμένου τύπου. Δεν πρέπει να είναι null ή διαγραμμένο. |
|
|  | filePath | java.lang.String | Διαδρομή προς το αρχείο, στο οποίο θα αποθηκευτεί το έγγραφο εξόδου. Εάν υπάρχει αρχείο με το ίδιο όνομα, θα ξαναγραφτεί πλήρως. Η συμβολοσειρά διαδρομής δεν πρέπει να είναι null, κενή ή να περιέχει μόνο κενά. |
|
|  | saveOptions | [ISaveOptions](../../com.groupdocs.editor.options/isaveoptions) | Επιλογές αποθήκευσης εγγράφου, που καθορίζουν τη μορφή του τελικού εγγράφου, καθώς και γενικές και ειδικές για μορφή επιλογές αποθήκευσης. Δεν πρέπει να είναι null. **Learn more** |

* More about saving document after edit using GroupDocs.Editor: [How to save edited document using GroupDocs.Editor](../https://docs.groupdocs.com/display/editornet/Save+document)
|

### save(EditableDocument inputDocument, String filePath) {#save-com.groupdocs.editor.EditableDocument-java.lang.String-}
```
public final void save(EditableDocument inputDocument, String filePath)
```


Μετατρέπει το καθορισμένο επεξεργασμένο έγγραφο (που αντιπροσωπεύεται από ένα [EditableDocument](../../com.groupdocs.editor/editabledocument)) σε ένα έγγραφο εξόδου του οποίου η μορφή καθορίζεται από την επέκταση του ονόματος αρχείου, και το αποθηκεύει στην καθορισμένη διαδρομή αρχείου.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | inputDocument | [EditableDocument](../../com.groupdocs.editor/editabledocument) | Έκδοση του εγγράφου εισόδου που επεξεργάστηκε σε WYSIWYG HTML editor και αποθηκεύτηκε ως παρουσία του [EditableDocument](../../com.groupdocs.editor/editabledocument). Δεν πρέπει να είναι  null  ή διαγραμμένο. |
|
|  | filePath | java.lang.String | Διαδρομή προς το αρχείο όπου θα αποθηκευτεί το έγγραφο εξόδου. Εάν υπάρχει αρχείο με το ίδιο όνομα, θα αντικατασταθεί πλήρως. Η συμβολοσειρά διαδρομής δεν πρέπει να είναι  null , κενή ή να περιέχει μόνο κενά. Επειδή οι προεπιλεγμένες επιλογές αποθήκευσης και η μορφή εξόδου καθορίζονται από αυτό το όνομα αρχείου, πρέπει να έχει έγκυρη επέκταση. |
|

### save(OutputStream outputDocument, WordProcessingSaveOptions saveOptions) {#save-java.io.OutputStream-com.groupdocs.editor.options.WordProcessingSaveOptions-}
```
public final OutputStream save(OutputStream outputDocument, WordProcessingSaveOptions saveOptions)
```


Μετατρέπει το αρχικό έγγραφο μετά την τροποποίηση (για παράδειγμα,
FormFieldManager
(#getFormFieldManager.getFormFieldManager)),
στο τελικό έγγραφο της καθορισμένης μορφής και αποθηκεύει το περιεχόμενό του στο παρεχόμενο stream.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | outputDocument | java.io.OutputStream | Η ροή στην οποία θα αποθηκευτεί το έγγραφο εξόδου. Αυτή η ροή πρέπει να είναι εγγράψιμη και τοποθετημένη στην αρχή του περιεχομένου του εγγράφου. Δεν πρέπει να είναι null. |
|
|  | saveOptions | [WordProcessingSaveOptions](../../com.groupdocs.editor.options/wordprocessingsaveoptions) | Επιλογές αποθήκευσης εγγράφου που καθορίζουν τη μορφή του τελικού εγγράφου, καθώς και γενικές και ειδικές για μορφή επιλογές αποθήκευσης. Δεν πρέπει να είναι null. |

<br />

*** ** * ** ***

Αν το  outputDocument  ή το  saveOptions  είναι null, θα εξαχθεί μια NullPointerException. Εάν λείπει το έγγραφο προς αποθήκευση, θα εξαχθεί μια NullPointerException.

<br />

<br />

*** ** * ** ***

 **Learn more:** 

* 

<br />

|

**Returns:**
java.io.OutputStream - Η ροή που περιέχει το αποθηκευμένο περιεχόμενο του εγγράφου.

### save(OutputStream outputDocument) {#save-java.io.OutputStream-}
```
public final OutputStream save(OutputStream outputDocument)
```


Αποθηκεύστε το τρέχον περιεχόμενο του εγγράφου στο καθορισμένο stream εξόδου.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | outputDocument | java.io.OutputStream | Η ροή στην οποία θα αποθηκευτεί το περιεχόμενο του εγγράφου. Αυτό δεν μπορεί να είναι null. |

<br />

*** ** * ** ***

Αυτή η μέθοδος αντιγράφει το περιεχόμενο από την εσωτερική αναπαράσταση του εγγράφου στη δοθείσα ροή εξόδου. Η αρχική θέση της ροής διατηρείται μετά την αποθήκευση.

<br />

|

**Returns:**
java.io.OutputStream - Η ροή με το αποθηκευμένο περιεχόμενο του εγγράφου.

### getDocumentInfo(String password) {#getDocumentInfo-java.lang.String-}
```
public final IDocumentInfo getDocumentInfo(String password)
```


Επιστρέφει μεταδεδομένα σχετικά με το έγγραφο, που φορτώθηκε σε αυτό το αντικείμενο 'Editor'


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | κωδικός πρόσβασης | java.lang.String | Ο χρήστης μπορεί να καθορίσει έναν κωδικό πρόσβασης για ένα έγγραφο, εάν αυτό το έγγραφο είναι κρυπτογραφημένο με τον κωδικό. Μπορεί να είναι NULL ή κενή συμβολοσειρά, που ισοδυναμεί με την απουσία κωδικού. Για εκείνες τις μορφές εγγράφων που δεν διαθέτουν δυνατότητα προστασίας με κωδικό, αυτό το όρισμα θα αγνοηθεί. Εάν το έγγραφο είναι κρυπτογραφημένο και ο κωδικός δεν έχει καθοριστεί σε αυτήν την παράμετρο, αλλά είχε καθοριστεί προηγουμένως στις επιλογές φόρτωσης κατά τη δημιουργία αυτού του αντικειμένου, θα χρησιμοποιηθεί. **Learn more** |

* Learn more about obtaining document specific properties in code: [How to get document info using GroupDocs.Editor](../https://docs.groupdocs.com/editor/java/extracting-document-metainfo/)
|

**Returns:**
[IDocumentInfo](../../com.groupdocs.editor.metadata/idocumentinfo)
### dispose() {#dispose--}
```
public final void dispose()
```


Αποδεσμεύει αυτό το αντικείμενο Editor, ώστε να απελευθερώσει όλους τους εσωτερικούς
πόρους και να γίνει μη διαθέσιμο για περαιτέρω χρήση


### isDisposed() {#isDisposed--}
```
public final boolean isDisposed()
```


Δείχνει εάν αυτό το αντικείμενο Editor έχει ήδη αποδεσμευτεί και δεν μπορεί να
χρησιμοποιηθεί ξανά (true) ή όχι και είναι ενεργό (false)


**Returns:**
boolean
