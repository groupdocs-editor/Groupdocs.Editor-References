---
title: "Mp3Audio"
second_title: "Αναφορά API του GroupDocs.Editor για Java"
description: "Αντιπροσωπεύει έναν πόρο ήχου οποιασδήποτε μορφής."
type: docs
weight: 11
url: /el/java/com.groupdocs.editor.htmlcss.resources.audio/mp3audio/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.resources.IHtmlResource](../../com.groupdocs.editor.htmlcss.resources/ihtmlresource)
```
public final class Mp3Audio implements IHtmlResource
```

Αντιπροσωπεύει έναν πόρο ήχου οποιασδήποτε μορφής.

## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
|  | [Mp3Audio(String name, System.IO.Stream binaryContent, boolean leaveOpen)](#Mp3Audio-java.lang.String-com.aspose.ms.System.IO.Stream-boolean-) | Δημιουργεί νέα κλάση Mp3Audio από περιεχόμενο MP3, που αναπαρίσταται ως ροή byte, και με το καθορισμένο όνομα |
|
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [isValid(System.IO.Stream binaryContent)](#isValid-com.aspose.ms.System.IO.Stream-) | Ελέγχει εάν η καθορισμένη ροή είναι έγκυρο περιεχόμενο MP3 |
|
|  | [getName()](#getName--) | Επιστρέφει το όνομα αυτού του περιεχομένου MP3. |
|
|  | [getFilenameWithExtension()](#getFilenameWithExtension--) | Επιστρέφει το σωστό όνομα αρχείου αυτού του περιεχομένου MP3, το οποίο αποτελείται από όνομα και επέκταση. |
|
|  | [getType()](#getType--) | Επιστρέφει ένα AudioFormat.Mp3 (επίσης ικανοποιεί το IHtmlResource.getFormat() μέσω συνεπαγόμενης επιστροφής) |
|
|  | [getByteContent()](#getByteContent--) | Επιστρέφει το περιεχόμενο αυτής της γραμματοσειράς ως ροή byte |
|
|  | [getByteContentInternal()](#getByteContentInternal--) | Επιστρέφει το περιεχόμενο αυτού του MP3 πόρου ήχου ως ροή byte με την αρχική θέση |
|
|  | [getTextContent()](#getTextContent--) | Επιστρέφει το περιεχόμενο αυτού του MP3 πόρου ως συμβολοσειρά κωδικοποιημένη σε base64. |
|
|  | [save(String fullPathToFile)](#save-java.lang.String-) | Αποθηκεύει αυτόν τον MP3 πόρο στο καθορισμένο αρχείο |
|
|  | [equals(IHtmlResource other)](#equals-com.groupdocs.editor.htmlcss.resources.IHtmlResource-) | Ελέγχει αυτήν την παρουσία με τον καθορισμένο πόρο HTML για ισότητα αναφοράς |
|
|  | [equals(Mp3Audio other)](#equals-com.groupdocs.editor.htmlcss.resources.audio.Mp3Audio-) | Ελέγχει αυτήν την παρουσία με τον καθορισμένο πόρο γραμματοσειράς για ισότητα αναφοράς |
|
|  | [dispose()](#dispose--) | Αποδεσμεύει αυτόν τον πόρο MP3, αποδεσμεύοντας το περιεχόμενό του και καθιστώντας τις περισσότερες μεθόδους και ιδιότητες μη λειτουργικές |
|
|  | [isDisposed()](#isDisposed--) | Καθορίζει εάν το περιεχόμενο MP3 είναι αποδεσμευμένο ή όχι |
|
| [addDisposedListener(EventHandler value)](#addDisposedListener-com.groupdocs.editor.handler.EventHandler-) |  |
| [removeDisposedListener(EventHandler value)](#removeDisposedListener-com.groupdocs.editor.handler.EventHandler-) |  |
### Mp3Audio(String name, System.IO.Stream binaryContent, boolean leaveOpen) {#Mp3Audio-java.lang.String-com.aspose.ms.System.IO.Stream-boolean-}
```
public Mp3Audio(String name, System.IO.Stream binaryContent, boolean leaveOpen)
```


Δημιουργεί νέα κλάση Mp3Audio από περιεχόμενο MP3, που αναπαρίσταται ως ροή byte, και με το καθορισμένο όνομα


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | όνομα | java.lang.String | Όνομα του περιεχομένου MP3. Δεν μπορεί να είναι null, κενό ή λευκοί χαρακτήρες. |
|
|  | binaryContent | com.aspose.ms.System.IO.Stream | Περιεχόμενο ως ροή byte. Η ανάγνωση ξεκινά από την αρχική θέση. Δεν μπορεί να είναι null. Πρέπει να είναι αναγνώσιμη και αναζητήσιμη. Εάν αυτή η παρουσία αποδεσμευτεί, αυτή η ροή θα αποδεσμευθεί επίσης. |
|
|  | leaveOpen | boolean | Καθορίζει εάν θα αποδεσμευτεί ή όχι η καθορισμένη ροή όταν η παρουσία Mp3Audio αποδεσμευτεί |
|

### isValid(System.IO.Stream binaryContent) {#isValid-com.aspose.ms.System.IO.Stream-}
```
public static boolean isValid(System.IO.Stream binaryContent)
```


Ελέγχει εάν η καθορισμένη ροή είναι έγκυρο περιεχόμενο MP3


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | binaryContent | com.aspose.ms.System.IO.Stream | Ροή byte, η οποία προφανώς περιέχει περιεχόμενο MP3 |
|

**Returns:**
boolean - True εάν η καθορισμένη ροή περιέχει έγκυρο περιεχόμενο MP3, false διαφορετικά

### getName() {#getName--}
```
public String getName()
```


Επιστρέφει το όνομα αυτού του περιεχομένου MP3. Συνήθως δεν περιέχει την επέκταση του ονόματος αρχείου και θεωρητικά μπορεί να διαφέρει από το όνομα αρχείου.


**Returns:**
java.lang.String
### getFilenameWithExtension() {#getFilenameWithExtension--}
```
public String getFilenameWithExtension()
```


Επιστρέφει το σωστό όνομα αρχείου αυτού του περιεχομένου MP3, το οποίο αποτελείται από το όνομα και την επέκταση. Θεωρητικά μπορεί να διαφέρει από το όνομα.


**Returns:**
java.lang.String
### getType() {#getType--}
```
public AudioType getType()
```


Επιστρέφει ένα AudioFormat.Mp3 (επίσης ικανοποιεί το IHtmlResource.getFormat() μέσω συνεπαγόμενης επιστροφής)


**Returns:**
[AudioType](../../com.groupdocs.editor.htmlcss.resources.audio/audiotype)
### getByteContent() {#getByteContent--}
```
public InputStream getByteContent()
```


Επιστρέφει το περιεχόμενο αυτής της γραμματοσειράς ως ροή byte


**Returns:**
java.io.InputStream
### getByteContentInternal() {#getByteContentInternal--}
```
public System.IO.Stream getByteContentInternal()
```


Επιστρέφει το περιεχόμενο αυτού του MP3 πόρου ήχου ως ροή byte με την αρχική θέση


**Returns:**
com.aspose.ms.System.IO.Stream
### getTextContent() {#getTextContent--}
```
public String getTextContent()
```


Επιστρέφει το περιεχόμενο αυτού του πόρου MP3 ως συμβολοσειρά κωδικοποιημένη σε base64. Αυτή η τιμή αποθηκεύεται στην κρυφή μνήμη μετά την πρώτη κλήση.


**Returns:**
java.lang.String
### save(String fullPathToFile) {#save-java.lang.String-}
```
public void save(String fullPathToFile)
```


Αποθηκεύει αυτόν τον MP3 πόρο στο καθορισμένο αρχείο


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | fullPathToFile | java.lang.String | Πλήρης διαδρομή προς το αρχείο, το οποίο θα δημιουργηθεί ή ξαναγραφεί |
|

### equals(IHtmlResource other) {#equals-com.groupdocs.editor.htmlcss.resources.IHtmlResource-}
```
public boolean equals(IHtmlResource other)
```


Ελέγχει αυτήν την παρουσία με τον καθορισμένο πόρο HTML για ισότητα αναφοράς


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | other | [IHtmlResource](../../com.groupdocs.editor.htmlcss.resources/ihtmlresource) | Άλλος κληρονόμος της διεπαφής IHtmlResource |
|

**Returns:**
boolean - Αληθές εάν είναι ίσες, ψευδές εάν δεν είναι ίσες

### equals(Mp3Audio other) {#equals-com.groupdocs.editor.htmlcss.resources.audio.Mp3Audio-}
```
public boolean equals(Mp3Audio other)
```


Ελέγχει αυτήν την παρουσία με τον καθορισμένο πόρο γραμματοσειράς για ισότητα αναφοράς


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | other | [Mp3Audio](../../com.groupdocs.editor.htmlcss.resources.audio/mp3audio) | Άλλη παρουσία της κλάσης Mp3Audio |
|

**Returns:**
boolean - Αληθές εάν είναι ίσες, ψευδές εάν δεν είναι ίσες

### dispose() {#dispose--}
```
public void dispose()
```


Αποδεσμεύει αυτόν τον πόρο MP3, αποδεσμεύοντας το περιεχόμενό του και καθιστώντας τις περισσότερες μεθόδους και ιδιότητες μη λειτουργικές


### isDisposed() {#isDisposed--}
```
public boolean isDisposed()
```


Καθορίζει εάν το περιεχόμενο MP3 είναι αποδεσμευμένο ή όχι


**Returns:**
boolean
### addDisposedListener(EventHandler value) {#addDisposedListener-com.groupdocs.editor.handler.EventHandler-}
```
public void addDisposedListener(EventHandler value)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [EventHandler](../../com.groupdocs.editor.handler/eventhandler) |  |

### removeDisposedListener(EventHandler value) {#removeDisposedListener-com.groupdocs.editor.handler.EventHandler-}
```
public void removeDisposedListener(EventHandler value)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [EventHandler](../../com.groupdocs.editor.handler/eventhandler) |  |

