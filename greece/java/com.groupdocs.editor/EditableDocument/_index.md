---
title: "EditableDocument"
second_title: "Αναφορά API του GroupDocs.Editor για Java"
description: "Ενδιάμεσο έγγραφο που περιέχει το περιεχόμενο πριν και μετά την επεξεργασία"
type: docs
weight: 10
url: /el/java/com.groupdocs.editor/editabledocument/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.resources.IAuxDisposable](../../com.groupdocs.editor.htmlcss.resources/iauxdisposable)
```
public final class EditableDocument implements IAuxDisposable
```

Ενδιάμεσο έγγραφο, που περιέχει περιεχόμενο πριν και μετά την επεξεργασία


*** ** * ** ***

Μία παρουσία της κλάσης EditableDocument μπορεί να παραχθεί από τη μέθοδο Editor.edit() ή να δημιουργηθεί από τον χρήστη χρησιμοποιώντας στατικές συναρτήσεις. EditableDocument αποθηκεύει εσωτερικά το έγγραφο σε δικό του κλειστό μορφότυπο, ο οποίος είναι συμβατός (μετατρέψιμος) με όλες τις μορφές εισαγωγής και εξαγωγής που υποστηρίζει το GroupDocs.Editor. Για να γίνει το έγγραφο επεξεργάσιμο σε οποιονδήποτε επεξεργαστή WYSIWYG στην πλευρά του πελάτη (όπως CKEditor ή TinyMCE), EditableDocument παρέχει μεθόδους για τη δημιουργία HTML markup και την παραγωγή πόρων που μπορούν να γίνουν αποδεκτοί από τον χρήστη.

<br />


## Πεδία

| Πεδίο | Περιγραφή |
| --- | --- |
| [Disposed](#Disposed) |  |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [getImages()](#getImages--) | Επιτρέπει την απόκτηση εξωτερικών πόρων εικόνας (raster εικόνες), που χρησιμοποιούνται |
από αυτό το έγγραφο HTML
|
|  | [getFonts()](#getFonts--) | Επιτρέπει την απόκτηση εξωτερικών πόρων γραμματοσειρών, που χρησιμοποιούνται από αυτό το HTML |
έγγραφο
|
|  | [getCss()](#getCss--) | Επιστρέφει μια λίστα πόρων CSS |
|
|  | [getAudio()](#getAudio--) | Επιστρέφει μια λίστα πόρων ήχου |
|
|  | [getAllResources()](#getAllResources--) | Επιστρέφει μια λίστα όλων των υπαρχόντων πόρων: όλα τα φύλλα στυλ, εικόνες από |
HTML και όλα τα φύλλα στυλ, γραμματοσειρές
|
|  | [getContent(OutputStream storage, Charset encoding)](#getContent-java.io.OutputStream-java.nio.charset.Charset-) | Επιστρέφει το συνολικό περιεχόμενο του εγγράφου HTML ως ροή byte γράφοντας αυτό το περιεχόμενο σε καθορισμένη ροή με καθορισμένη κωδικοποίηση κειμένου |
|
|  | [getBodyContent()](#getBodyContent--) | Επιστρέφει το σώμα του εγγράφου HTML (το περιεχόμενο μεταξύ του ανοίγματος και του κλεισίματος |
ετικέτες BODY χωρίς αυτές τις ετικέτες) ως συμβολοσειρά.
|
|  | [getBodyContent(String externalImagesTemplate)](#getBodyContent-java.lang.String-) | Επιστρέφει το σώμα του εγγράφου HTML (το περιεχόμενο μεταξύ του ανοίγματος και του κλεισίματος |
ετικέτες BODY χωρίς αυτές τις ετικέτες) ως συμβολοσειρά, όπου οι σύνδεσμοι προς το εξωτερικό
πόρους περιέχουν το καθορισμένο πρόθεμα.
|
|  | [getContent()](#getContent--) | Επιστρέφει το συνολικό περιεχόμενο του εγγράφου HTML ως συμβολοσειρά. |
|
|  | [getContentString(String externalImagesTemplate, String externalCssTemplate)](#getContentString-java.lang.String-java.lang.String-) | Επιστρέφει το συνολικό περιεχόμενο του εγγράφου HTML ως συμβολοσειρά, όπου οι σύνδεσμοι προς |
τους εξωτερικούς πόρους περιέχουν το καθορισμένο πρόθεμα.
|
|  | [getCssContent()](#getCssContent--) | Επιστρέφει το περιεχόμενο όλων των εξωτερικών φύλλων στυλ ως λίστα συμβολοσειρών, όπου |
μια συμβολοσειρά αντιπροσωπεύει ένα φύλλο στυλ.
|
|  | [getCssContent(String externalImagesPrefix, String externalFontsPrefix)](#getCssContent-java.lang.String-java.lang.String-) | Επιστρέφει το περιεχόμενο όλων των εξωτερικών φύλλων στυλ ως λίστα συμβολοσειρών, όπου |
μια συμβολοσειρά αντιπροσωπεύει ένα φύλλο στυλ.
|
|  | [getEmbeddedHtml()](#getEmbeddedHtml--) | Επιστρέφει όλο το περιεχόμενο αυτού του εγγράφου HTML με όλους τους σχετικούς πόρους σε ένα |
σχήμα μιας μοναδικής συμβολοσειράς, όπου όλοι οι πόροι είναι ενσωματωμένοι μέσα στο HTML
σήμανση σε μορφή κωδικοποιημένη base64.
|
|  | [save(String htmlFilePath)](#save-java.lang.String-) | Αποθηκεύει αυτό το έγγραφο HTML στο αρχείο στην καθορισμένη διαδρομή, όπου η σήμανση HTML |
θα αποθηκευτεί, και στον συνοδευτικό φάκελο με τους πόρους.
|
|  | [save(String htmlFilePath, String resourcesFolderPath)](#save-java.lang.String-java.lang.String-) | Αποθηκεύει αυτό το έγγραφο HTML στο αρχείο στην καθορισμένη διαδρομή, όπου η σήμανση HTML |
θα αποθηκευτεί, και στον συνοδευτικό φάκελο με τους πόρους, ο οποίος είναι
τοποθετημένος στην καθορισμένη διαδρομή.
|
| [save(Writer htmlMarkup, HtmlSaveOptions saveOptions)](#save-java.io.Writer-com.groupdocs.editor.options.HtmlSaveOptions-) |  |
|  | [fromMarkup(String newHtmlContent, List<IHtmlResource> resources)](#fromMarkup-java.lang.String-java.util.List-com.groupdocs.editor.htmlcss.resources.IHtmlResource--) | Στατική εργοστασιακή μέθοδος, η οποία δημιουργεί μια παρουσία του EditableDocument από |
την καθορισμένη σήμανση HTML και ένα σύνολο αντίστοιχων συνδεδεμένων πόρων
|
|  | [fromMarkupAndResourceFolder(String newHtmlContent, String resourceFolderPath)](#fromMarkupAndResourceFolder-java.lang.String-java.lang.String-) | Στατική εργοστασιακή μέθοδος, η οποία δημιουργεί ένα στιγμιότυπο του EditableDocument από καθορισμένη σήμανση HTML και από πόρους, που βρίσκονται στο φάκελο που έχει οριστεί με το πλήρες μονοπάτι |
|
|  | [fromFile(String htmlFilePath, String resourceFolderPath)](#fromFile-java.lang.String-java.lang.String-) | Στατική εργοστασιακή μέθοδος, η οποία δημιουργεί ένα στιγμιότυπο του EditableDocument από ένα HTML |
αρχείο, το οποίο καθορίζεται από διαδρομή προς το ίδιο το αρχείο \*.html και έναν φάκελο
με συνδεδεμένους πόρους
|
|  | [dispose()](#dispose--) | Αποδεσμεύει αυτό το στιγμιότυπο του Editable document, αποδεσμεύοντας το περιεχόμενό του και |
καθιστώντας τις μεθόδους και τις ιδιότητές του μη λειτουργικές
|
|  | [isDisposed()](#isDisposed--) | Καθορίζει εάν αυτό το Editable document έχει ήδη αποδεσμευτεί (true) ή |
όχι (false)
|
### Disposed {#Disposed}
```
public final Event<EventHandler> Disposed
```


### getImages() {#getImages--}
```
public final List<IImageResource> getImages()
```


Επιτρέπει την απόκτηση εξωτερικών πόρων εικόνας (raster εικόνες), που χρησιμοποιούνται
από αυτό το έγγραφο HTML


**Returns:**
java.util.List<com.groupdocs.editor.htmlcss.resources.images.IImageResource>
### getFonts() {#getFonts--}
```
public final List<FontResourceBase> getFonts()
```


Επιτρέπει την απόκτηση εξωτερικών πόρων γραμματοσειρών, που χρησιμοποιούνται από αυτό το HTML
έγγραφο


**Returns:**
java.util.List<com.groupdocs.editor.htmlcss.resources.fonts.FontResourceBase>
### getCss() {#getCss--}
```
public final List<CssText> getCss()
```


Επιστρέφει μια λίστα πόρων CSS


**Returns:**
java.util.List<com.groupdocs.editor.htmlcss.resources.textual.CssText>
### getAudio() {#getAudio--}
```
public final List<Mp3Audio> getAudio()
```


Επιστρέφει μια λίστα πόρων ήχου


**Returns:**
java.util.List<com.groupdocs.editor.htmlcss.resources.audio.Mp3Audio>
### getAllResources() {#getAllResources--}
```
public final List<IHtmlResource> getAllResources()
```


Επιστρέφει μια λίστα όλων των υπαρχόντων πόρων: όλα τα φύλλα στυλ, εικόνες από
HTML και όλα τα φύλλα στυλ, γραμματοσειρές


*** ** * ** ***

Αυτή η ιδιότητα επιστρέφει ένα συνενωμένο αποτέλεσμα των ιδιοτήτων 'Images', 'Fonts' και 'Css'

<br />



**Returns:**
java.util.List<com.groupdocs.editor.htmlcss.resources.IHtmlResource>
### getContent(OutputStream storage, Charset encoding) {#getContent-java.io.OutputStream-java.nio.charset.Charset-}
```
public OutputStream getContent(OutputStream storage, Charset encoding)
```


Επιστρέφει το συνολικό περιεχόμενο του εγγράφου HTML ως ροή byte γράφοντας αυτό το περιεχόμενο σε καθορισμένη ροή με καθορισμένη κωδικοποίηση κειμένου


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | αποθήκευση | java.io.OutputStream | Μη μηδενική ροή byte, η οποία υποστηρίζει εγγραφή |
|
|  | κωδικοποίηση | java.nio.charset.Charset | Μη μηδενική κωδικοποίηση κειμένου, η οποία πρέπει να εφαρμοστεί κατά την εγγραφή του κειμενικού περιεχομένου στην καθορισμένη αποθήκευση |


TStream
: Οποιαδήποτε υλοποίηση του java.io.InputStream
|

**Returns:**
java.io.OutputStream - Παράδειγμα της καθορισμένης αποθήκευσης

### getBodyContent() {#getBodyContent--}
```
public final String getBodyContent()
```


Επιστρέφει το σώμα του εγγράφου HTML (το περιεχόμενο μεταξύ του ανοίγματος και του κλεισίματος
ετικέτες BODY χωρίς αυτές τις ετικέτες) ως συμβολοσειρά.


**Returns:**
java.lang.String - Συμβολοσειρά, η οποία περιέχει το σώμα του εγγράφου HTML


*** ** * ** ***

Οι επεξεργαστές WYSIWYG λειτουργούν με το σώμα του εγγράφου και δεν μπορούν να επεξεργαστούν σωστά τις μεταπληροφορίες του από το μπλοκ HEAD. Αυτή η μέθοδος έχει σχεδιαστεί για τέτοιες περιπτώσεις. Αυτή η υπερφόρτωση δεν επιτρέπει την προσαρμογή των URI για εξωτερικά αιτήματα πόρων.

<br />


### getBodyContent(String externalImagesTemplate) {#getBodyContent-java.lang.String-}
```
public final String getBodyContent(String externalImagesTemplate)
```


Επιστρέφει το σώμα του εγγράφου HTML (το περιεχόμενο μεταξύ του ανοίγματος και του κλεισίματος
ετικέτες BODY χωρίς αυτές τις ετικέτες) ως συμβολοσειρά, όπου οι σύνδεσμοι προς το εξωτερικό
πόρους περιέχουν το καθορισμένο πρόθεμα.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | externalImagesTemplate | java.lang.String | Μέσω αυτής της παραμέτρου μπορεί να καθοριστεί ένα πρόθεμα, το οποίο θα προσαρτηθεί στους συνδέσμους προς όλες τις εξωτερικές εικόνες στα στοιχεία IMG, που θα εμφανιστούν στην τελική συμβολοσειρά HTML. Εάν είναι NULL ή κενό, τα προθέματα δεν θα προστεθούν. |


*** ** * ** ***

Οι επεξεργαστές WYSIWYG λειτουργούν με το σώμα του εγγράφου και δεν μπορούν να επεξεργαστούν σωστά τις μεταπληροφορίες του από το μπλοκ HEAD. Αυτή η μέθοδος έχει σχεδιαστεί για τέτοιες περιπτώσεις. Αυτή η υπερφόρτωση επιτρέπει την προσαρμογή των URI για εξωτερικά αιτήματα πόρων.

<br />

|

**Returns:**
java.lang.String - String, η οποία περιέχει το σώμα του εγγράφου HTML με συνδέσμους, προσαρμοσμένο στις εξωτερικές εικόνες

### getContent() {#getContent--}
```
public String getContent()
```


Επιστρέφει το συνολικό περιεχόμενο του εγγράφου HTML ως συμβολοσειρά.


**Returns:**
java.lang.String - String, η οποία περιέχει το περιεχόμενο του εγγράφου HTML

### getContentString(String externalImagesTemplate, String externalCssTemplate) {#getContentString-java.lang.String-java.lang.String-}
```
public String getContentString(String externalImagesTemplate, String externalCssTemplate)
```


Επιστρέφει το συνολικό περιεχόμενο του εγγράφου HTML ως συμβολοσειρά, όπου οι σύνδεσμοι προς
τους εξωτερικούς πόρους περιέχουν το καθορισμένο πρόθεμα.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | externalImagesTemplate | java.lang.String | Μέσω αυτής της παραμέτρου μπορεί να καθοριστεί ένα πρόθεμα, το οποίο θα προσαρτηθεί στους συνδέσμους προς όλες τις εξωτερικές εικόνες στα στοιχεία IMG, που θα εμφανιστούν στην τελική συμβολοσειρά HTML. Εάν είναι NULL ή κενό, τα προθέματα δεν θα προστεθούν. |
|
|  | externalCssTemplate | java.lang.String | Μέσω αυτής της παραμέτρου μπορεί να καθοριστεί ένα πρόθεμα, το οποίο θα προσαρτηθεί στους συνδέσμους προς όλα τα εξωτερικά φύλλα στυλ στα στοιχεία LINK, τα οποία θα εμφανιστούν στην τελική συμβολοσειρά HTML. Εάν είναι NULL ή κενό, τα προθέματα δεν θα προστεθούν. |
|

**Returns:**
java.lang.String - String, η οποία περιέχει το περιεχόμενο του εγγράφου HTML με συνδέσμους, προσαρμοσμένο στους εξωτερικούς πόρους

### getCssContent() {#getCssContent--}
```
public final List<String> getCssContent()
```


Επιστρέφει το περιεχόμενο όλων των εξωτερικών φύλλων στυλ ως λίστα συμβολοσειρών, όπου
ένα string αντιπροσωπεύει ένα φύλλο στυλ. Επιστρέφει κενή λίστα, εάν δεν υπάρχει
CSS για αυτό το έγγραφο.


**Returns:**
java.util.List<java.lang.String> - Μια λίστα από strings, όπου κάθε string περιέχει το περιεχόμενο ενός εγγράφου CSS

### getCssContent(String externalImagesPrefix, String externalFontsPrefix) {#getCssContent-java.lang.String-java.lang.String-}
```
public final List<String> getCssContent(String externalImagesPrefix, String externalFontsPrefix)
```


Επιστρέφει το περιεχόμενο όλων των εξωτερικών φύλλων στυλ ως λίστα συμβολοσειρών, όπου
ένα string αντιπροσωπεύει ένα φύλλο στυλ. Το καθορισμένο πρόθεμα θα εφαρμοστεί σε
κάθε σύνδεσμο προς τον εξωτερικό πόρο σε κάθε παραγόμενο φύλλο στυλ.
Επιστρέφει κενή λίστα, εάν δεν υπάρχει CSS για αυτό το έγγραφο.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | externalImagesPrefix | java.lang.String | Μέσω αυτής της παραμέτρου μπορεί να καθοριστεί ένα πρόθεμα, το οποίο θα προσαρτηθεί στους συνδέσμους προς όλες τις εξωτερικές εικόνες, που θα εμφανιστούν στις δηλώσεις CSS στις παραγόμενες συμβολοσειρές CSS. Εάν είναι NULL ή κενό, τα προθέματα δεν θα προστεθούν. |
|
|  | externalFontsPrefix | java.lang.String | Μέσω αυτής της παραμέτρου μπορεί να καθοριστεί ένα πρόθεμα, το οποίο θα προσαρτηθεί στους συνδέσμους προς όλες τις εξωτερικές γραμματοσειρές στο |
|

**Returns:**
java.util.List<java.lang.String> - Μια λίστα από strings, όπου κάθε string περιέχει το περιεχόμενο ενός εγγράφου CSS

### getEmbeddedHtml() {#getEmbeddedHtml--}
```
public final String getEmbeddedHtml()
```


Επιστρέφει όλο το περιεχόμενο αυτού του εγγράφου HTML με όλους τους σχετικούς πόρους σε ένα
σχήμα μιας μοναδικής συμβολοσειράς, όπου όλοι οι πόροι είναι ενσωματωμένοι μέσα στο HTML
σήμανση σε μορφή κωδικοποιημένη base64.


**Returns:**
java.lang.String - String, η οποία δεν είναι NULL ή κενή σε καμία περίπτωση

### save(String htmlFilePath) {#save-java.lang.String-}
```
public final void save(String htmlFilePath)
```


Αποθηκεύει αυτό το έγγραφο HTML στο αρχείο στην καθορισμένη διαδρομή, όπου η σήμανση HTML
θα αποθηκευτεί, και στον συνοδευτικό φάκελο με τους πόρους.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | htmlFilePath | java.lang.String | Πλήρης διαδρομή προς το αρχείο, όπου θα αποθηκευτεί το σήμα HTML. Το αρχείο θα δημιουργηθεί ή θα αντικατασταθεί, εάν υπάρχει. Ο συνοδευτικός φάκελος πόρων θα δημιουργηθεί στον ίδιο φάκελο όπου υπάρχει το αρχείο HTML. |
|

### save(String htmlFilePath, String resourcesFolderPath) {#save-java.lang.String-java.lang.String-}
```
public final void save(String htmlFilePath, String resourcesFolderPath)
```


Αποθηκεύει αυτό το έγγραφο HTML στο αρχείο στην καθορισμένη διαδρομή, όπου η σήμανση HTML
θα αποθηκευτεί, και στον συνοδευτικό φάκελο με τους πόρους, ο οποίος είναι
τοποθετημένος στην καθορισμένη διαδρομή.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | htmlFilePath | java.lang.String | Πλήρης διαδρομή προς το αρχείο, όπου θα αποθηκευτεί το σήμα HTML. Δεν μπορεί να είναι NULL ή κενό. Το αρχείο θα δημιουργηθεί ή θα αντικατασταθεί, εάν υπάρχει. |
|
|  | resourcesFolderPath | java.lang.String | Πλήρης διαδρομή προς το συνοδευτικό φάκελο, όπου θα αποθηκευτούν όλοι οι σχετικοί πόροι. Εάν είναι NULL ή κενό, ο φάκελος θα δημιουργηθεί αυτόματα στον ίδιο κατάλογο όπου βρίσκεται το αρχείο \\*.html. Εάν καθοριστεί και δεν υπάρχει, θα δημιουργηθεί. |
|

### save(Writer htmlMarkup, HtmlSaveOptions saveOptions) {#save-java.io.Writer-com.groupdocs.editor.options.HtmlSaveOptions-}
```
public void save(Writer htmlMarkup, HtmlSaveOptions saveOptions)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| htmlMarkup | java.io.Writer |  |
| saveOptions | [HtmlSaveOptions](../../com.groupdocs.editor.options/htmlsaveoptions) |  |

### fromMarkup(String newHtmlContent, List<IHtmlResource> resources) {#fromMarkup-java.lang.String-java.util.List-com.groupdocs.editor.htmlcss.resources.IHtmlResource--}
```
public static EditableDocument fromMarkup(String newHtmlContent, List<IHtmlResource> resources)
```


Στατική εργοστασιακή μέθοδος, η οποία δημιουργεί μια παρουσία του EditableDocument από
την καθορισμένη σήμανση HTML και ένα σύνολο αντίστοιχων συνδεδεμένων πόρων


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | newHtmlContent | java.lang.String | String, που περιέχει ακατέργαστο σήμα HTML, το οποίο πρέπει να αναλυθεί. Δεν μπορεί να είναι NULL, κενό ή μη έγκυρο. |
|
|  | πόροι | java.util.List<com.groupdocs.editor.htmlcss.resources.IHtmlResource> | Συλλογή όλων των πόρων (εικόνες, φύλλα στυλ, γραμματοσειρές), που χρησιμοποιούνται στο έγγραφο HTML, που καθορίζεται στην παράμετρο newHtmlContent. Μπορεί να λείπει (NULL ή κενή συλλογή). |
|

**Returns:**
[EditableDocument](../../com.groupdocs.editor/editabledocument) - New non-null instance of EditableDocument

### fromMarkupAndResourceFolder(String newHtmlContent, String resourceFolderPath) {#fromMarkupAndResourceFolder-java.lang.String-java.lang.String-}
```
public static EditableDocument fromMarkupAndResourceFolder(String newHtmlContent, String resourceFolderPath)
```


Στατική εργοστασιακή μέθοδος, η οποία δημιουργεί ένα στιγμιότυπο του EditableDocument από καθορισμένη σήμανση HTML και από πόρους, που βρίσκονται στο φάκελο που έχει οριστεί με το πλήρες μονοπάτι


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | newHtmlContent | java.lang.String | String, που περιέχει ακατέργαστο σήμα HTML, το οποίο πρέπει να αναλυθεί. Δεν μπορεί να είναι NULL, κενό ή μη έγκυρο. |
|
|  | resourceFolderPath | java.lang.String | Υποχρεωτική διαδρομή προς το φάκελο με τους πόρους. Όλα τα φύλλα στυλ που βρίσκονται σε αυτόν το φάκελο θα χρησιμοποιηθούν. Δεν μπορεί να είναι NULL ή κενή συμβολοσειρά, και αυτός ο φάκελος πρέπει να υπάρχει. |

<br />

*** ** * ** ***

Αυτό το στατικό εργοστάσιο είναι χρήσιμο όταν το περιεχόμενο του εγγράφου HTML παρουσιάζεται ως συμβολοσειρά, αλλά όλοι οι πόροι βρίσκονται σε κάποιο φάκελο, και συχνά οι σύνδεσμοι προς αυτούς τους πόρους στο σήμα HTML είναι άκυροι και λείπουν. Κατά την κλήση αυτής της μεθόδου, σαρώει τον καθορισμένο φάκελο και αυτόματα εφαρμόζει όλα τα ευρέθηκαν φύλλα στυλ στο έγγραφο. Αυτή η μέθοδος είναι πολύ χρήσιμη όταν λαμβάνεται περιεχόμενο από διαφορετικούς επεξεργαστές HTML, οι οποίοι συνήθως αποκόπτουν τα μεταδεδομένα του εγγράφου κ.λπ.

<br />

|

**Returns:**
[EditableDocument](../../com.groupdocs.editor/editabledocument) - New non-null instance of EditableDocument

### fromFile(String htmlFilePath, String resourceFolderPath) {#fromFile-java.lang.String-java.lang.String-}
```
public static EditableDocument fromFile(String htmlFilePath, String resourceFolderPath)
```


Στατική εργοστασιακή μέθοδος, η οποία δημιουργεί ένα στιγμιότυπο του EditableDocument από ένα HTML
αρχείο, το οποίο καθορίζεται από διαδρομή προς το ίδιο το αρχείο \*.html και έναν φάκελο
με συνδεδεμένους πόρους


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | htmlFilePath | java.lang.String | String, που περιέχει πλήρη διαδρομή προς το αρχείο HTML. Δεν μπορεί να είναι null, πρέπει να είναι έγκυρη διαδρομή αρχείου, και το ίδιο το αρχείο πρέπει να υπάρχει. |
|
|  | resourceFolderPath | java.lang.String | Προαιρετική διαδρομή προς το φάκελο με τους πόρους HTML. Εάν είναι NULL, άκυρη ή τέτοιος φάκελος δεν υπάρχει, ο Editor θα προσπαθήσει να βρει αυτόν τον φάκελο μόνος του, αναλύοντας το σήμα HTML |
|

**Returns:**
[EditableDocument](../../com.groupdocs.editor/editabledocument) - New non-null instance of EditableDocument

### dispose() {#dispose--}
```
public final void dispose()
```


Αποδεσμεύει αυτό το στιγμιότυπο του Editable document, αποδεσμεύοντας το περιεχόμενό του και
καθιστώντας τις μεθόδους και τις ιδιότητές του μη λειτουργικές


### isDisposed() {#isDisposed--}
```
public final boolean isDisposed()
```


Καθορίζει εάν αυτό το Editable document έχει ήδη αποδεσμευτεί (true) ή
όχι (false)


**Returns:**
boolean
