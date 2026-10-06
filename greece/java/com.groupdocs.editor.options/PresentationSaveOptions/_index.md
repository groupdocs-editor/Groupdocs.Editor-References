---
title: "PresentationSaveOptions"
second_title: "Αναφορά API του GroupDocs.Editor για Java"
description: "Επιτρέπει τον καθορισμό προσαρμοσμένων επιλογών για τη δημιουργία και αποθήκευση εγγράφων Presentation συμβατών με PowerPoint"
type: docs
weight: 34
url: /el/java/com.groupdocs.editor.options/presentationsaveoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.ISaveOptions](../../com.groupdocs.editor.options/isaveoptions)
```
public final class PresentationSaveOptions implements ISaveOptions
```

Επιτρέπει τον καθορισμό προσαρμοσμένων επιλογών για τη δημιουργία και αποθήκευση του Presentation
(συμβατά με PowerPoint) έγγραφα

## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
|  | [PresentationSaveOptions()](#PresentationSaveOptions--) | Αυτός ο κατασκευαστής χωρίς παραμέτρους δημιουργεί μια νέα παρουσία του PresentationSaveOptions με μορφή εξόδου PPTX (μπορεί να τροποποιηθεί στη συνέχεια μέσω |
OutputFormat
(ιδιότητα (#getOutputFormat.getOutputFormat/#setOutputFormat(PresentationFormats).setOutputFormat(PresentationFormats)))
|
|  | [PresentationSaveOptions(PresentationFormats outputFormat)](#PresentationSaveOptions-com.groupdocs.editor.formats.PresentationFormats-) | Δημιουργεί μια νέα παρουσία του PresentationSaveOptions με καθορισμένο |
υποχρεωτική μορφή εξόδου Presentation, ενώ όλες οι άλλες παράμετροι είναι
προεπιλογή
|
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [getPassword()](#getPassword--) | Επιτρέπει τον καθορισμό, την τροποποίηση και την απόκτηση του κωδικού πρόσβασης, ο οποίος θα χρησιμοποιηθεί για |
κωδικοποίηση του τελικού εγγράφου Presentation.
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | Επιτρέπει τον καθορισμό, την τροποποίηση και την ανάκτηση του κωδικού, ο οποίος θα χρησιμοποιηθεί για την κωδικοποίηση του τελικού εγγράφου Presentation. |
|
|  | [getSlideNumber()](#getSlideNumber--) | Επιτρέπει την εισαγωγή επεξεργασμένης διαφάνειας σε υπάρχουσα παρουσίαση αντί για τη δημιουργία νέας παρουσίασης με μία διαφάνεια (προεπιλεγμένη συμπεριφορά). |
|
|  | [setSlideNumber(int value)](#setSlideNumber-int-) | Επιτρέπει την εισαγωγή επεξεργασμένης διαφάνειας σε υπάρχουσα παρουσίαση αντί για τη δημιουργία νέας παρουσίασης με μία διαφάνεια (προεπιλεγμένη συμπεριφορά). |
|
|  | [getInsertAsNewSlide()](#getInsertAsNewSlide--) | Δυαδική σημαία, η οποία καθορίζει αν η επεξεργασμένη διαφάνεια πρέπει να αντικαταστήσει την υπάρχουσα διαφάνεια στην αρχική παρουσίαση στη θέση που καθορίζεται από το |
SlideNumber
(ιδιότητα (#getSlideNumber.getSlideNumber/#setSlideNumber(int).setSlideNumber(int)), ή πρέπει να ενσωματωθεί μεταξύ της υπάρχουσας διαφάνειας και της προηγούμενης, χωρίς αντικατάσταση του περιεχομένου της.)
|
|  | [setInsertAsNewSlide(boolean value)](#setInsertAsNewSlide-boolean-) | Δυαδική σημαία, η οποία καθορίζει αν η επεξεργασμένη διαφάνεια πρέπει να αντικαταστήσει την υπάρχουσα διαφάνεια στην αρχική παρουσίαση στη θέση που καθορίζεται από το |
SlideNumber
(ιδιότητα (#getSlideNumber.getSlideNumber/#setSlideNumber(int).setSlideNumber(int)), ή πρέπει να ενσωματωθεί μεταξύ της υπάρχουσας διαφάνειας και της προηγούμενης, χωρίς αντικατάσταση του περιεχομένου της.)
|
|  | [getOutputFormat()](#getOutputFormat--) | Επιτρέπει τον καθορισμό μορφής Presentation, η οποία θα χρησιμοποιηθεί για την αποθήκευση του εγγράφου |
|
|  | [setOutputFormat(PresentationFormats value)](#setOutputFormat-com.groupdocs.editor.formats.PresentationFormats-) | Επιτρέπει τον καθορισμό μορφής Presentation, η οποία θα χρησιμοποιηθεί για την αποθήκευση του εγγράφου |
|
|  | [getSlideNumbersToDelete()](#getSlideNumbersToDelete--) | Επιτρέπει τον καθορισμό ενός πίνακα με αριθμούς διαφανειών που ξεκινούν από το 1 και πρέπει να διαγραφούν από την παρουσίαση κατά την αποθήκευση, σε περίπτωση που η επεξεργασμένη διαφάνεια εισαχθεί σε υπάρχουσα παρουσίαση. |
|
|  | [setSlideNumbersToDelete(int[] value)](#setSlideNumbersToDelete-int---) | Επιτρέπει τον καθορισμό ενός πίνακα με αριθμούς διαφανειών που ξεκινούν από το 1 και πρέπει να διαγραφούν από την παρουσίαση κατά την αποθήκευση, σε περίπτωση που η επεξεργασμένη διαφάνεια εισαχθεί σε υπάρχουσα παρουσίαση. |
|
### PresentationSaveOptions() {#PresentationSaveOptions--}
```
public PresentationSaveOptions()
```


Αυτός ο κατασκευαστής χωρίς παραμέτρους δημιουργεί μια νέα παρουσία του PresentationSaveOptions με μορφή εξόδου PPTX (μπορεί να τροποποιηθεί στη συνέχεια μέσω
OutputFormat
(ιδιότητα (#getOutputFormat.getOutputFormat/#setOutputFormat(PresentationFormats).setOutputFormat(PresentationFormats)))


### PresentationSaveOptions(PresentationFormats outputFormat) {#PresentationSaveOptions-com.groupdocs.editor.formats.PresentationFormats-}
```
public PresentationSaveOptions(PresentationFormats outputFormat)
```


Δημιουργεί μια νέα παρουσία του PresentationSaveOptions με καθορισμένο
υποχρεωτική μορφή εξόδου Presentation, ενώ όλες οι άλλες παράμετροι είναι
προεπιλογή


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | outputFormat | [PresentationFormats](../../com.groupdocs.editor.formats/presentationformats) | Υποχρεωτική μορφή εξόδου, στην οποία πρέπει να αποθηκευτεί το έγγραφο Presentation |
|

### getPassword() {#getPassword--}
```
public final String getPassword()
```


Επιτρέπει τον καθορισμό, την τροποποίηση και την απόκτηση του κωδικού πρόσβασης, ο οποίος θα χρησιμοποιηθεί για
κωδικοποίηση του τελικού εγγράφου Presentation. Από προεπιλογή είναι NULL -
δεν θα οριστεί κωδικός. Ορίστε σε NULL ή κενή συμβολοσειρά για να το αφαιρέσετε
ο κωδικός πρόσβασης, εάν είχε οριστεί προηγουμένως.


**Returns:**
java.lang.String -
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Επιτρέπει τον καθορισμό, την τροποποίηση και την ανάκτηση του κωδικού, ο οποίος θα χρησιμοποιηθεί για την κωδικοποίηση του τελικού εγγράφου Presentation.
Από προεπιλογή είναι NULL - ο κωδικός πρόσβασης δεν θα οριστεί. Ορίστε σε NULL ή κενή συμβολοσειρά για να αφαιρέσετε τον κωδικό πρόσβασης, εάν είχε οριστεί προηγουμένως.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### getSlideNumber() {#getSlideNumber--}
```
public final int getSlideNumber()
```


Επιτρέπει την εισαγωγή επεξεργασμένης διαφάνειας σε υπάρχουσα παρουσίαση αντί για τη δημιουργία νέας παρουσίασης με μία διαφάνεια (προεπιλεγμένη συμπεριφορά).
Ο αριθμός διαφάνειας είναι ένας αριθμός που ξεκινά από 1 για μια διαφάνεια στην παρουσίαση, που έχει φορτωθεί στην κλάση Editor. Εάν είναι 0 (προεπιλεγμένη τιμή), η νέα παρουσίαση θα δημιουργηθεί με μία μόνο επεξεργασμένη διαφάνεια. Εάν είναι μεγαλύτερος ή μικρότερος από το μηδέν, και υπάρχει έγκυρη παρουσίαση, φορτωμένη στην κλάση Editor, η επεξεργασμένη διαφάνεια, αποθηκευμένη μέσα στην είσοδο του αντικειμένου EditableDocument, θα εισαχθεί σε αυτήν την παρουσίαση.

<br />

*** ** * ** ***

> ```
> Given presentation has 5 slides:
>  SlideNumber  = 0; \u2014 ignore given presentation, create a new presentation and put edited slide into it.
>  SlideNumber  = 1; \u2014 replace the first slide with edited
>  SlideNumber  = 2; \u2014 replace the second slide with edited
>  SlideNumber  = 5; \u2014 replace the last (5th) slide with edited
>  SlideNumber  = 6; \u2014 replace the last (5th) slide with edited, because 6 is greater then 5 and thus is adjusted
>  SlideNumber = -1; \u2014 replace the last (5th) slide with edited, because "-1" means "last existing"
>  SlideNumber = -2; \u2014 replace the 4th slide with edited
>  SlideNumber = -3; \u2014 replace the 3rd slide with edited
>  SlideNumber = -4; \u2014 replace the 2nd slide with edited
>  SlideNumber = -5; \u2014 replace the first slide with edited
>  SlideNumber = -6; \u2014 replace the first slide with edited, because "-6" is greater then 5 and thus is adjusted
>  
> ```

<br />

<br />

*** ** * ** ***

 *SlideNumber*  integer property, if it is not in default state (reserved value '0'), represents a slide number, so it starts from 1, not from zero, and its max value is the amount of all existing slides in a presentation. However, if specified value is greater then amount of all slides, GroupDocs.Editor will adjust it to mark the last slide. Negative values are also allowed and count slides from end. For example, "-1" implies last slide in a presentation, "-2" \\u2014 last but one, etc. Like with positive values, when negative slide number exceeds the total count of slides in the given presentation, it will be adjusted to the first slide. The  InsertAsNewSlide (#getInsertAsNewSlide.getInsertAsNewSlide/#setInsertAsNewSlide(boolean).setInsertAsNewSlide(boolean)) boolean property is tightly coupled with this one.

<br />



**Returns:**
int
### setSlideNumber(int value) {#setSlideNumber-int-}
```
public final void setSlideNumber(int value)
```


Επιτρέπει την εισαγωγή επεξεργασμένης διαφάνειας σε υπάρχουσα παρουσίαση αντί για τη δημιουργία νέας παρουσίασης με μία διαφάνεια (προεπιλεγμένη συμπεριφορά).
Ο αριθμός διαφάνειας είναι ένας αριθμός που ξεκινά από 1 για μια διαφάνεια στην παρουσίαση, που έχει φορτωθεί στην κλάση Editor. Εάν είναι 0 (προεπιλεγμένη τιμή), η νέα παρουσίαση θα δημιουργηθεί με μία μόνο επεξεργασμένη διαφάνεια. Εάν είναι μεγαλύτερος ή μικρότερος από το μηδέν, και υπάρχει έγκυρη παρουσίαση, φορτωμένη στην κλάση Editor, η επεξεργασμένη διαφάνεια, αποθηκευμένη μέσα στην είσοδο του αντικειμένου EditableDocument, θα εισαχθεί σε αυτήν την παρουσίαση.

<br />

*** ** * ** ***

> ```
> Given presentation has 5 slides:
>  SlideNumber  = 0; \u2014 ignore given presentation, create a new presentation and put edited slide into it.
>  SlideNumber  = 1; \u2014 replace the first slide with edited
>  SlideNumber  = 2; \u2014 replace the second slide with edited
>  SlideNumber  = 5; \u2014 replace the last (5th) slide with edited
>  SlideNumber  = 6; \u2014 replace the last (5th) slide with edited, because 6 is greater then 5 and thus is adjusted
>  SlideNumber = -1; \u2014 replace the last (5th) slide with edited, because "-1" means "last existing"
>  SlideNumber = -2; \u2014 replace the 4th slide with edited
>  SlideNumber = -3; \u2014 replace the 3rd slide with edited
>  SlideNumber = -4; \u2014 replace the 2nd slide with edited
>  SlideNumber = -5; \u2014 replace the first slide with edited
>  SlideNumber = -6; \u2014 replace the first slide with edited, because "-6" is greater then 5 and thus is adjusted
>  
> ```

<br />

<br />

*** ** * ** ***

 *SlideNumber*  integer property, if it is not in default state (reserved value '0'), represents a slide number, so it starts from 1, not from zero, and its max value is the amount of all existing slides in a presentation. However, if specified value is greater then amount of all slides, GroupDocs.Editor will adjust it to mark the last slide. Negative values are also allowed and count slides from end. For example, "-1" implies last slide in a presentation, "-2" \\u2014 last but one, etc. Like with positive values, when negative slide number exceeds the total count of slides in the given presentation, it will be adjusted to the first slide. The  InsertAsNewSlide (#getInsertAsNewSlide.getInsertAsNewSlide/#setInsertAsNewSlide(boolean).setInsertAsNewSlide(boolean)) boolean property is tightly coupled with this one.

<br />



**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### getInsertAsNewSlide() {#getInsertAsNewSlide--}
```
public final boolean getInsertAsNewSlide()
```


Δυαδική σημαία, η οποία καθορίζει αν η επεξεργασμένη διαφάνεια πρέπει να αντικαταστήσει την υπάρχουσα διαφάνεια στην αρχική παρουσίαση στη θέση που καθορίζεται από το
SlideNumber
(ιδιότητα (#getSlideNumber.getSlideNumber/#setSlideNumber(int).setSlideNumber(int)), ή πρέπει να ενσωματωθεί μεταξύ της υπάρχουσας διαφάνειας και της προηγούμενης, χωρίς αντικατάσταση του περιεχομένου της.)
Από προεπιλογή είναι false \\u2014 η υπάρχουσα διαφάνεια θα αντικατασταθεί. Αυτή η ιδιότητα αγνοείται, εάν η τιμή του
SlideNumber
(#getSlideNumber.getSlideNumber/#setSlideNumber(int).setSlideNumber(int)) η ιδιότητα είναι ορισμένη σε '0'.

<br />

*** ** * ** ***

Από προεπιλογή η διαφάνεια αντικαθίσταται. Αυτό σημαίνει ότι εάν η δεδομένη παρουσίαση έχει 5 διαφάνειες, και το SlideNumber (#getSlideNumber.getSlideNumber/#setSlideNumber(int).setSlideNumber(int))=4, τότε η 4η διαφάνεια θα αντικατασταθεί με τη νέα επεξεργασμένη διαφάνεια, ενώ ο συνολικός αριθμός διαφάνειων στην παρουσίαση (5) θα παραμείνει αμετάβλητος. Ωστόσο, εάν η τιμή αυτής της ιδιότητας οριστεί σε *true*, η νέα επεξεργασμένη διαφάνεια θα ενσωματωθεί ως 4η διαφάνεια, και όλες οι επόμενες διαφάνειες θα μετακινηθούν στο τέλος: η "old" 4η διαφάνεια γίνεται 5η, και η 5η γίνεται 6η, και ο συνολικός αριθμός διαφάνειων στην παρουσίαση θα αυξηθεί κατά ένα και θα γίνει 6.

<br />



**Returns:**
boolean
### setInsertAsNewSlide(boolean value) {#setInsertAsNewSlide-boolean-}
```
public final void setInsertAsNewSlide(boolean value)
```


Δυαδική σημαία, η οποία καθορίζει αν η επεξεργασμένη διαφάνεια πρέπει να αντικαταστήσει την υπάρχουσα διαφάνεια στην αρχική παρουσίαση στη θέση που καθορίζεται από το
SlideNumber
(ιδιότητα (#getSlideNumber.getSlideNumber/#setSlideNumber(int).setSlideNumber(int)), ή πρέπει να ενσωματωθεί μεταξύ της υπάρχουσας διαφάνειας και της προηγούμενης, χωρίς αντικατάσταση του περιεχομένου της.)
Από προεπιλογή είναι false \\u2014 η υπάρχουσα διαφάνεια θα αντικατασταθεί. Αυτή η ιδιότητα αγνοείται, εάν η τιμή του
SlideNumber
(#getSlideNumber.getSlideNumber/#setSlideNumber(int).setSlideNumber(int)) η ιδιότητα είναι ορισμένη σε '0'.

<br />

*** ** * ** ***

Από προεπιλογή η διαφάνεια αντικαθίσταται. Αυτό σημαίνει ότι εάν η δεδομένη παρουσίαση έχει 5 διαφάνειες, και το SlideNumber (#getSlideNumber.getSlideNumber/#setSlideNumber(int).setSlideNumber(int))=4, τότε η 4η διαφάνεια θα αντικατασταθεί με τη νέα επεξεργασμένη διαφάνεια, ενώ ο συνολικός αριθμός διαφάνειων στην παρουσίαση (5) θα παραμείνει αμετάβλητος. Ωστόσο, εάν η τιμή αυτής της ιδιότητας οριστεί σε *true*, η νέα επεξεργασμένη διαφάνεια θα ενσωματωθεί ως 4η διαφάνεια, και όλες οι επόμενες διαφάνειες θα μετακινηθούν στο τέλος: η "old" 4η διαφάνεια γίνεται 5η, και η 5η γίνεται 6η, και ο συνολικός αριθμός διαφάνειων στην παρουσίαση θα αυξηθεί κατά ένα και θα γίνει 6.

<br />



**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |

### getOutputFormat() {#getOutputFormat--}
```
public final PresentationFormats getOutputFormat()
```


Επιτρέπει τον καθορισμό μορφής Presentation, η οποία θα χρησιμοποιηθεί για την αποθήκευση του εγγράφου

<br />

*** ** * ** ***

Η μορφή εξόδου συνήθως ορίζεται στον κατασκευαστή αυτής της κλάσης, επειδή είναι υποχρεωτική. Αυτή η ιδιότητα επιτρέπει την απόκτηση ή τροποποίηση της μορφής εξόδου αργότερα, όταν το στιγμιότυπο της κλάσης [PresentationSaveOptions](../../com.groupdocs.editor.options/presentationsaveoptions) έχει ήδη δημιουργηθεί.

<br />



**Returns:**
[PresentationFormats](../../com.groupdocs.editor.formats/presentationformats)
### setOutputFormat(PresentationFormats value) {#setOutputFormat-com.groupdocs.editor.formats.PresentationFormats-}
```
public final void setOutputFormat(PresentationFormats value)
```


Επιτρέπει τον καθορισμό μορφής Presentation, η οποία θα χρησιμοποιηθεί για την αποθήκευση του εγγράφου

<br />

*** ** * ** ***

Η μορφή εξόδου συνήθως ορίζεται στον κατασκευαστή αυτής της κλάσης, επειδή είναι υποχρεωτική. Αυτή η ιδιότητα επιτρέπει την απόκτηση ή τροποποίηση της μορφής εξόδου αργότερα, όταν το στιγμιότυπο της κλάσης [PresentationSaveOptions](../../com.groupdocs.editor.options/presentationsaveoptions) έχει ήδη δημιουργηθεί.

<br />



**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [PresentationFormats](../../com.groupdocs.editor.formats/presentationformats) |  |

### getSlideNumbersToDelete() {#getSlideNumbersToDelete--}
```
public final int[] getSlideNumbersToDelete()
```


Επιτρέπει τον καθορισμό ενός πίνακα με αριθμούς διαφάνειων που ξεκινούν από 1 και πρέπει να διαγραφούν από την παρουσίαση κατά την αποθήκευσή της, στην περίπτωση που η επεξεργασμένη διαφάνεια εισαχθεί σε υπάρχουσα παρουσίαση. Όταν η επεξεργασμένη διαφάνεια αποθηκευτεί όχι ως νέα παρουσίαση μίας διαφάνειας (προεπιλεγμένη συμπεριφορά), αλλά αντίθετα αποθηκευτεί σε υπάρχουσα παρουσίαση (χρησιμοποιώντας #getSlideNumber().getSlideNumber() / #setSlideNumber(int).setSlideNumber(int)), είναι επίσης δυνατό να διαγραφούν ορισμένες συγκεκριμένες διαφάνειες από αυτήν την παρουσίαση καθορίζοντας τους αριθμούς τους σε αυτόν τον πίνακα. Από προεπιλογή αυτός ο πίνακας είναι  null  \\u2014 δεν θα διαγραφούν διαφάνειες. Ωστόσο, όταν αυτός ο πίνακας δεν είναι null και δεν είναι κενός, και περιέχει τουλάχιστον έναν έγκυρο αριθμό διαφάνειας, μετά τη δημιουργία του εγγράφου Presentation εξόδου με το περιεχόμενο της επεξεργασμένης διαφάνειας, οι διαφάνειες με τους καθορισμένους αριθμούς θα διαγραφούν από την παρουσίαση ακριβώς πριν από τη γραφή του περιεχομένου της σε ροή εξόδου ή αρχείο. Οι αριθμοί διαφάνειας σε αυτόν τον πίνακα είναι 1‑based, όχι 0‑based. Οι μη έγκυροι αριθμοί (μικρότεροι από 1 ή μεγαλύτεροι από το συνολικό αριθμό διαφάνειων) θα αγνοηθούν.


**Returns:**
int[] - Πίνακας αριθμών διαφάνειας που ξεκινούν από 1 για διαγραφή, ή  null  εάν δεν πρέπει να διαγραφεί τίποτα.

### setSlideNumbersToDelete(int[] value) {#setSlideNumbersToDelete-int---}
```
public final void setSlideNumbersToDelete(int[] value)
```


Επιτρέπει τον καθορισμό ενός πίνακα με αριθμούς διαφάνειας που ξεκινούν από 1 και πρέπει να διαγραφούν από την παρουσίαση κατά την αποθήκευσή της, στην περίπτωση που η επεξεργασμένη διαφάνεια εισαχθεί σε υπάρχουσα παρουσίαση. Οι αριθμοί διαφάνειας σε αυτόν τον πίνακα είναι 1‑based. Οι μη έγκυροι αριθμοί θα αγνοηθούν.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | τιμή | int[] | Πίνακας αριθμών διαφάνειας που ξεκινούν από 1 για διαγραφή (μπορεί να είναι  null  ή κενός). |
|

