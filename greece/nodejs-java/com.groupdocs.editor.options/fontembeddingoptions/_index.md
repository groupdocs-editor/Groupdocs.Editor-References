---
title: "FontEmbeddingOptions"
second_title: "GroupDocs.Editor για Node.js μέσω Java API Reference"
description: "Οι επιλογές ενσωμάτωσης γραμματοσειρών ελέγχουν ποιοι πόροι γραμματοσειρών πρέπει να ενσωματωθούν στο τελικό έγγραφο WordProcessing"
type: docs
weight: 17
url: /el/nodejs-java/com.groupdocs.editor.options/fontembeddingoptions/
---
**Inheritance:**
java.lang.Object
```
public final class FontEmbeddingOptions
```

Οι επιλογές ενσωμάτωσης γραμματοσειρών ελέγχουν ποιοι πόροι γραμματοσειρών πρέπει να ενσωματωθούν σε
το τελικό έγγραφο WordProcessing


*** ** * ** ***

Οι επιλογές ενσωμάτωσης γραμματοσειρών εφαρμόζονται κατά την αποθήκευση του εγγράφου (από το ενδιάμεσο EditableDocument στο τελικό μορφότυπο WordProcessing), αυτό το enum περιλαμβάνεται ως ιδιότητα στο WordProcessingSaveOptions, από όπου πρέπει να χρησιμοποιηθεί

<br />


## Πεδία

| Πεδίο | Περιγραφή |
| --- | --- |
|  | [NotEmbed](#NotEmbed) | Μην ενσωματώσετε κανέναν πόρο γραμματοσειράς ούτε από το EditableDocument ούτε από το |
σύστημα.
|
|  | [EmbedAll](#EmbedAll) | Αναλύστε το περιεχόμενο του εγγράφου από το εισερχόμενο EditableDocument, βρείτε όλες τις χρησιμοποιημένες γραμματοσειρές |
και ενσωματώστε τις στο τελικό έγγραφο WordProcessing.
|
|  | [EmbedWithoutSystem](#EmbedWithoutSystem) | Ακριβώς όπως το [EmbedAll](../../com.groupdocs.editor.options/fontembeddingoptions#EmbedAll), αλλά εξαιρέστε αυτές τις γραμματοσειρές, |
που θεωρούνται από το λειτουργικό σύστημα ως συστημικές γραμματοσειρές
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


Αναλύστε το περιεχόμενο του εγγράφου από το εισερχόμενο EditableDocument, βρείτε όλες τις χρησιμοποιημένες γραμματοσειρές
και ενσωματώστε τις στο τελικό έγγραφο WordProcessing. Κατ' αρχάς
Το GroupDocs.Editor λαμβάνει γραμματοσειρές από τους πόρους γραμματοσειρών εντός του EditableDocument.
Εάν είναι ανεπαρκή ή λείπουν, τότε το GroupDocs.Editor παίρνει τις γραμματοσειρές
από το OS.


*** ** * ** ***

Κατ' αρχάς το GroupDocs.Editor αναλύει το περιεχόμενο του EditableDocument και δημιουργεί μια λίστα με όλες τις χρησιμοποιημένες γραμματοσειρές. Στη συνέχεια αυτές οι γραμματοσειρές αναζητούνται στους πόρους γραμματοσειρών του EditableDocument. Εάν το EditableDocument περιέχει κάποιους πόρους γραμματοσειρών που δεν συμμετέχουν στο περιεχόμενο του εγγράφου, αυτοί οι πόροι αγνοούνται. Εάν υπάρχουν κάποιες γραμματοσειρές που χρησιμοποιούνται στο περιεχόμενο του εγγράφου και δεν έχουν αντίστοιχους πόρους γραμματοσειρών στο EditableDocument, τότε το GroupDocs.Editor προσπαθεί να τις βρει στο OS. Αυτή η επιλογή μοιάζει με την επιλογή "Ενσωμάτωση γραμματοσειρών στο αρχείο" με όλες τις υποεπιλογές απενεργοποιημένες στο Microsoft Word 2007 και νεότερα

<br />



### EmbedWithoutSystem {#EmbedWithoutSystem}
```
public static final int EmbedWithoutSystem
```


Ακριβώς όπως το [EmbedAll](../../com.groupdocs.editor.options/fontembeddingoptions#EmbedAll), αλλά εξαιρέστε αυτές τις γραμματοσειρές,
που θεωρούνται από το λειτουργικό σύστημα ως συστημικές γραμματοσειρές


*** ** * ** ***

Το MS Windows έχει μια έννοια των γραμματοσειρών συστήματος, οι οποίες είναι οι πιο βασικές και χρησιμοποιούμενες γραμματοσειρές από το ίδιο το Windows. Κατά τη χρήση αυτής της επιλογής, το GroupDocs.Editor λειτουργεί όπως στην περίπτωση [EmbedAll](../../com.groupdocs.editor.options/fontembeddingoptions#EmbedAll), αλλά τελικά εξετάζει ένα σύνολο των ληφθέντων γραμματοσειρών και εξαιρεί εκείνες που θεωρούνται από το OS ως γραμματοσειρές συστήματος. Αυτή η επιλογή μοιάζει με τις επιλογές "Ενσωμάτωση γραμματοσειρών στο αρχείο" + "Να μην ενσωματωθούν κοινές γραμματοσειρές συστήματος" στο Microsoft Word 2007 και νεότερα

<br />



### getFontEmbeddingOptions() {#getFontEmbeddingOptions--}
```
public static int[] getFontEmbeddingOptions()
```




**Returns:**
int[]
