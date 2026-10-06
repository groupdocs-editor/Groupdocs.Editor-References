---
title: "FontEmbeddingOptions"
second_title: "Αναφορά API του GroupDocs.Editor για Java"
description: "Οι επιλογές ενσωμάτωσης γραμματοσειρών ελέγχουν ποιοι πόροι γραμματοσειρών πρέπει να ενσωματωθούν στο έγγραφο WordProcessing εξόδου"
type: docs
weight: 17
url: /el/java/com.groupdocs.editor.options/fontembeddingoptions/
---
**Inheritance:**
java.lang.Object
```
public final class FontEmbeddingOptions
```

Οι επιλογές ενσωμάτωσης γραμματοσειρών ελέγχουν ποιοι πόροι γραμματοσειρών πρέπει να ενσωματωθούν σε
το έγγραφο WordProcessing εξόδου


*** ** * ** ***

Οι επιλογές ενσωμάτωσης γραμματοσειρών εφαρμόζονται κατά την αποθήκευση του εγγράφου (από το ενδιάμεσο EditableDocument σε μορφή WordProcessing εξόδου), αυτό το enum περιλαμβάνεται ως ιδιότητα στα WordProcessingSaveOptions, από όπου πρέπει να χρησιμοποιηθεί

<br />


## Πεδία

| Πεδίο | Περιγραφή |
| --- | --- |
|  | [NotEmbed](#NotEmbed) | Μην ενσωματώσετε κανέναν πόρο γραμματοσειράς ούτε από το EditableDocument ούτε από το |
σύστημα.
|
|  | [EmbedAll](#EmbedAll) | Αναλύστε το περιεχόμενο του εγγράφου από το εισαγόμενο EditableDocument, βρείτε όλες τις χρησιμοποιημένες γραμματοσειρές |
και ενσωματώστε τις στο έγγραφο WordProcessing εξόδου.
|
|  | [EmbedWithoutSystem](#EmbedWithoutSystem) | Ακριβώς όπως το [EmbedAll](../../com.groupdocs.editor.options/fontembeddingoptions#EmbedAll), αλλά εξαιρεί αυτές τις γραμματοσειρές, |
που θεωρούνται από το OS ως γραμματοσειρές συστήματος
|
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getFontEmbeddingOptions()](#getFontEmbeddingOptions--) |  |
### NotEmbed {#NotEmbed}
```
public static final int NotEmbed
```


Μην ενσωματώσετε κανέναν πόρο γραμματοσειράς ούτε από το EditableDocument ούτε από το
σύστημα. Προεπιλεγμένη τιμή.


### EmbedAll {#EmbedAll}
```
public static final int EmbedAll
```


Αναλύστε το περιεχόμενο του εγγράφου από το εισαγόμενο EditableDocument, βρείτε όλες τις χρησιμοποιημένες γραμματοσειρές
και ενσωματώνει τα σε έξοδο έγγραφο WordProcessing. Κατ' αρχήν
Το GroupDocs.Editor λαμβάνει τις γραμματοσειρές από τους πόρους γραμματοσειρών εντός του EditableDocument.
Εάν είναι ανεπαρκείς ή λείπουν, τότε το GroupDocs.Editor λαμβάνει τις γραμματοσειρές
από το OS.


*** ** * ** ***

Κατ' αρχάς το GroupDocs.Editor αναλύει το περιεχόμενο του EditableDocument και δημιουργεί μια λίστα με όλες τις χρησιμοποιημένες γραμματοσειρές. Στη συνέχεια αυτές οι γραμματοσειρές αναζητούνται στους πόρους γραμματοσειρών του EditableDocument. Εάν το EditableDocument περιέχει κάποιους πόρους γραμματοσειρών που δεν συμμετέχουν στο περιεχόμενο του εγγράφου, αυτοί οι πόροι αγνοούνται. Εάν υπάρχουν γραμματοσειρές που χρησιμοποιούνται στο περιεχόμενο του εγγράφου και δεν έχουν αντίστοιχους πόρους γραμματοσειρών στο EditableDocument, τότε το GroupDocs.Editor προσπαθεί να τις βρει στο OS. Αυτή η επιλογή μοιάζει με την επιλογή "Embed fonts in the file" με όλες τις υποεπιλογές απενεργοποιημένες στο Microsoft Word 2007 και νεότερα

<br />



### EmbedWithoutSystem {#EmbedWithoutSystem}
```
public static final int EmbedWithoutSystem
```


Ακριβώς όπως το [EmbedAll](../../com.groupdocs.editor.options/fontembeddingoptions#EmbedAll), αλλά εξαιρεί αυτές τις γραμματοσειρές,
που θεωρούνται από το OS ως γραμματοσειρές συστήματος


*** ** * ** ***

Το MS Windows έχει μια έννοια των γραμματοσειρών συστήματος, οι οποίες είναι οι πιο βασικές και χρησιμοποιούμενες γραμματοσειρές από το ίδιο το Windows. Όταν χρησιμοποιείται αυτή η επιλογή, το GroupDocs.Editor λειτουργεί όπως στην περίπτωση του [EmbedAll](../../com.groupdocs.editor.options/fontembeddingoptions#EmbedAll), αλλά τελικά εξετάζει ένα σύνολο των αποκτηθέντων γραμματοσειρών και εξαιρεί εκείνες που θεωρούνται από το OS ως γραμματοσειρές συστήματος. Αυτή η επιλογή μοιάζει με τις επιλογές "Embed fonts in the file" + "Do not embed common system fonts" στο Microsoft Word 2007 και νεότερα

<br />



### getFontEmbeddingOptions() {#getFontEmbeddingOptions--}
```
public static int[] getFontEmbeddingOptions()
```




**Returns:**
int[]
