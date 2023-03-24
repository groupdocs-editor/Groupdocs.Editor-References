---
title: WordProcessingSaveOptions
second_title: GroupDocs.Editor για Αναφορά API .NET
description: Επιτρέπει τον καθορισμό προσαρμοσμένων επιλογών για τη δημιουργία και αποθήκευση εγγράφων συμβατών με WordProcessing μετά την επεξεργασία τους
type: docs
weight: 1240
url: /el/net/groupdocs.editor.options/wordprocessingsaveoptions/
---
## WordProcessingSaveOptions class

Επιτρέπει τον καθορισμό προσαρμοσμένων επιλογών για τη δημιουργία και αποθήκευση εγγράφων συμβατών με WordProcessing μετά την επεξεργασία τους

```csharp
public sealed class WordProcessingSaveOptions : ICloneable, ISaveOptions
```

## Κατασκευαστές

| Ονομα | Περιγραφή |
| --- | --- |
| [WordProcessingSaveOptions](wordprocessingsaveoptions)(WordProcessingFormats) | Δημιουργεί μια νέα παρουσία του WordProcessingSaveOptions με καθορισμένη υποχρεωτική μορφή εξόδου WordProcessing, ενώ όλες οι άλλες παράμετροι είναι default |

## Ιδιότητες

| Ονομα | Περιγραφή |
| --- | --- |
| [EnablePagination](../../groupdocs.editor.options/wordprocessingsaveoptions/enablepagination) { get; set; } | Επιτρέπει την ενεργοποίηση ή απενεργοποίηση της σελιδοποίησης που θα χρησιμοποιηθεί για την αποθήκευση του εγγράφου WordProcessing. Εάν το αρχικό έγγραφο ανοίχτηκε και υποβλήθηκε σε επεξεργασία σε λειτουργία σελιδοποίησης, θα πρέπει επίσης να ενεργοποιηθεί αυτή η επιλογή. Από προεπιλογή είναι απενεργοποιημένο. |
| [FontEmbedding](../../groupdocs.editor.options/wordprocessingsaveoptions/fontembedding) { get; set; } | Υπεύθυνος για την ενσωμάτωση πόρων γραμματοσειράς σε έγγραφο εξόδου WordProcessing. Από προεπιλογή δεν ενσωματώνει καμία γραμματοσειρά (NotEmbed). |
| [Locale](../../groupdocs.editor.options/wordprocessingsaveoptions/locale) { get; set; } | Επιτρέπει τον ορισμό αντικατάστασης προεπιλεγμένων τοπικών ρυθμίσεων (γλώσσα) για το έγγραφο WordProcessing, το οποίο θα εφαρμοστεί κατά τη δημιουργία του. Όταν δεν καθορίζεται (προεπιλεγμένη τιμή), το MS Word (ή άλλο πρόγραμμα) θα εντοπίσει (ή θα επιλέξει) το έγγραφο locale σύμφωνα με στις δικές του ρυθμίσεις ή άλλους παράγοντες. |
| [LocaleBi](../../groupdocs.editor.options/wordprocessingsaveoptions/localebi) { get; set; } | Επιτρέπει τον ορισμό τοπικών ρυθμίσεων (γλώσσας) παράκαμψης για το έγγραφο WordProcessing για το κείμενο RTL (από δεξιά προς τα αριστερά), το οποίο θα εφαρμοστεί κατά τη δημιουργία του. Όταν δεν έχει καθοριστεί (προεπιλεγμένη τιμή), MS Word (ή άλλο πρόγραμμα) θα εντοπίσει (ή θα επιλέξει) το έγγραφο RTL locale σύμφωνα με τις δικές του ρυθμίσεις ή άλλους παράγοντες. |
| [LocaleFarEast](../../groupdocs.editor.options/wordprocessingsaveoptions/localefareast) { get; set; } | Επιτρέπει την παράκαμψη της τοπικής ρύθμισης (γλώσσα) για το έγγραφο WordProcessing για το κείμενο της Ανατολικής Ασίας, το οποίο θα εφαρμοστεί κατά τη δημιουργία του. Όταν δεν καθορίζεται (προεπιλεγμένη τιμή), το MS Word (ή άλλο πρόγραμμα) θα εντοπίσει (ή θα επιλέξει ) το έγγραφο Ανατολικής Ασίας locale σύμφωνα με τις δικές του ρυθμίσεις ή άλλους παράγοντες. |
| [OptimizeMemoryUsage](../../groupdocs.editor.options/wordprocessingsaveoptions/optimizememoryusage) { get; set; } | Ενεργοποιεί μηχανισμούς βελτιστοποίησης μνήμης κατά τη δημιουργία εγγράφων από HTML, γεγονός που υποβαθμίζει την απόδοση ως κόστος μείωσης της χρήσης μνήμης. Η ρύθμιση αυτής της επιλογής σε true μπορεί να μειώσει σημαντικά την κατανάλωση μνήμης ενώ δημιουργεί μεγάλα έγγραφα με κόστος μικρότερης εξοικονόμησης χρόνου. Η προεπιλογή είναι ψευδής (η βελτιστοποίηση μνήμης είναι απενεργοποιημένη για λόγους καλύτερης απόδοσης). |
| [OutputFormat](../../groupdocs.editor.options/wordprocessingsaveoptions/outputformat) { get; set; } | Επιτρέπει τον καθορισμό μιας μορφής επεξεργασίας κειμένου, η οποία θα χρησιμοποιηθεί για την αποθήκευση του εγγράφου |
| [Password](../../groupdocs.editor.options/wordprocessingsaveoptions/password) { get; set; } | Επιτρέπει τον καθορισμό, την τροποποίηση, τη λήψη ή την αφαίρεση ενός κωδικού πρόσβασης, ο οποίος θα χρησιμοποιηθεί για την κωδικοποίηση του παραγόμενου εγγράφου WordProcessing. Καθορίστε NULL ή κενή συμβολοσειρά για την αφαίρεση (καθαρισμό) του κωδικού πρόσβασης. |
| [Protection](../../groupdocs.editor.options/wordprocessingsaveoptions/protection) { get; set; } | Επιτρέπει τον έλεγχο και την εφαρμογή των επιλογών προστασίας εγγράφων για το έγγραφο WordProcessing οποιασδήποτε μορφής, το οποίο υποστηρίζει προστασία εγγράφων. Από προεπιλογή είναι NULL - η προστασία εγγράφων δεν θα χρησιμοποιηθεί. |

## Μέθοδοι

| Ονομα | Περιγραφή |
| --- | --- |
| [Clone](../../groupdocs.editor.options/wordprocessingsaveoptions/clone)() | Δημιουργεί και επιστρέφει ένα πλήρες αντίγραφο αυτής της παρουσίας του WordProcessingSaveOptions class |

### Παρατηρήσεις

Το WordProcessingSaveOptions εφαρμόζεται σε περιπτώσεις όπου υπάρχει μια παρουσία της κλάσης EditableDocument, η οποία περιέχει ένα επεξεργασμένο περιεχόμενο εγγράφου και απαιτείται η αποθήκευση αυτού του περιεχομένου στο νέο έγγραφο της μορφής WordProcessing.

### Δείτε επίσης

* interface [ISaveOptions](../isaveoptions)
* χώρος ονομάτων [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* συνέλευση [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->
