---
title: TextualFormats
second_title: GroupDocs.Editor για Αναφορά API .NET
description: Ενσωματώνει όλες τις μορφές κειμένου με βάση το κείμενο συμπεριλαμβανομένης της σήμανσης XML HTML και άλλων. Περιλαμβάνει τις ακόλουθες μορφές Html./textualformats/html  Txt./textualformats/txt  Xml./textualformats/xml . Md./textualformats/md  Json./textualformats/json .
type: docs
weight: 150
url: /el/net/groupdocs.editor.formats/textualformats/
---
## TextualFormats structure

Ενσωματώνει όλες τις μορφές κειμένου (με βάση το κείμενο), συμπεριλαμβανομένης της σήμανσης (XML, HTML) και άλλων. Περιλαμβάνει τις ακόλουθες μορφές: [`Html`](./html) , [`Txt`](./txt) , [`Xml`](./xml) . [`Md`](./md) , [`Json`](./json) .

```csharp
public struct TextualFormats : IDocumentFormat, IEquatable<TextualFormats>
```

## Ιδιότητες

| Ονομα | Περιγραφή |
| --- | --- |
| [Extension](../../groupdocs.editor.formats/textualformats/extension) { get; } | Επιστρέφει μια επέκταση (χωρίς χαρακτήρα κύριας κουκκίδας) αυτής της μορφής κειμένου σε πεζά |
| [Mime](../../groupdocs.editor.formats/textualformats/mime) { get; } | Επιστρέφει έναν κωδικό MIME για αυτήν τη μορφή |
| [Name](../../groupdocs.editor.formats/textualformats/name) { get; } | Επιστρέφει ένα επίσημο πλήρες όνομα αυτής της μορφής κειμένου |

## Μέθοδοι

| Ονομα | Περιγραφή |
| --- | --- |
| static [FromExtension](../../groupdocs.editor.formats/textualformats/fromextension)(string) | Επιστρέφει την παρουσία του[`TextualFormats`](../textualformats) δομή, συσχετίζεται με καθορισμένη επέκταση ονόματος αρχείου ή δημιουργεί μια εξαίρεση, εάν η επέκταση δεν μπορεί να αναλυθεί σωστά |
| [Equals](../../groupdocs.editor.formats/textualformats/equals#equals)(IDocumentFormat) | Καθορίζει εάν αυτή η παρουσία είναι ίση με την άλλη καθορισμένη IDocumentFormat instance |
| override [Equals](../../groupdocs.editor.formats/textualformats/equals#equals_2)(object) | Καθορίζει εάν αυτό το στιγμιότυπο είναι ίσο με το άλλο καθορισμένο αντικείμενο, το οποίο είναι πιθανώς σε πλαίσιο TextualFormats |
| [Equals](../../groupdocs.editor.formats/textualformats/equals#equals_1)(TextualFormats) | Καθορίζει εάν αυτή η παρουσία είναι ίση με την άλλη καθορισμένη TextualFormats instance |
| override [GetHashCode](../../groupdocs.editor.formats/textualformats/gethashcode)() | Επιστρέφει έναν κωδικό κατακερματισμού, ο οποίος είναι αμετάβλητος για αυτήν την περίπτωση |
| override [ToString](../../groupdocs.editor.formats/textualformats/tostring)() | Επιστρέφει το όνομα αυτής της συγκεκριμένης μορφής, όπως και η ιδιότητα "Όνομα" |
| [operator ==](../../groupdocs.editor.formats/textualformats/op_equality) | Ελέγχει δύο δεδομένες περιπτώσεις TextualFormats για την ισοτιμία |
| [operator !=](../../groupdocs.editor.formats/textualformats/op_inequality) | Ελέγχει δύο δεδομένες περιπτώσεις TextualFormats στο inequality |

## Πεδία

| Ονομα | Περιγραφή |
| --- | --- |
| static readonly [Chm](../../groupdocs.editor.formats/textualformats/chm) | Η Microsoft Compiled HTML Help είναι μια ιδιόκτητη ηλεκτρονική μορφή δυαδικής βοήθειας της Microsoft, που αποτελείται από μια συλλογή σελίδων HTML, ένα ευρετήριο και άλλα εργαλεία πλοήγησης. Μάθετε περισσότερα για αυτήν τη μορφή αρχείου[εδώ](https://docs.fileformat.com/web/chm/) . |
| static readonly [Html](../../groupdocs.editor.formats/textualformats/html) | Το έγγραφο HyperText Markup Language (HTML) είναι η επέκταση για ιστοσελίδες που δημιουργούνται για εμφάνιση σε προγράμματα περιήγησης. Μάθετε περισσότερα σχετικά με αυτήν τη μορφή αρχείου[εδώ](https://wiki.fileformat.com/web/html) . |
| static readonly [Json](../../groupdocs.editor.formats/textualformats/json) | Το JSON (JavaScript Object Notation) είναι μια ανοιχτή τυπική μορφή αρχείου για κοινή χρήση δεδομένων που χρησιμοποιεί κείμενο αναγνώσιμο από τον άνθρωπο για αποθήκευση και μετάδοση δεδομένων. Μάθετε περισσότερα για αυτήν τη μορφή αρχείου[εδώ](https://docs.fileformat.com/web/json/) . |
| static readonly [Md](../../groupdocs.editor.formats/textualformats/md) | Η Markdown είναι μια ελαφριά γλώσσα σήμανσης για τη δημιουργία μορφοποιημένου κειμένου χρησιμοποιώντας ένα πρόγραμμα επεξεργασίας απλού κειμένου. Μάθετε περισσότερα για αυτήν τη μορφή αρχείου[εδώ](https://docs.fileformat.com/word-processing/md/) . |
| static readonly [Mhtml](../../groupdocs.editor.formats/textualformats/mhtml) | Η MIME ενθυλάκωση συγκεντρωτικών εγγράφων HTML είναι μια μορφή αρχείου ιστοσελίδων που χρησιμοποιείται για να συνδυάσει, σε ένα μόνο αρχείο υπολογιστή, τον κώδικα HTML και τους συνοδευτικούς πόρους του. Μάθετε περισσότερα για αυτήν τη μορφή αρχείου[εδώ](https://docs.fileformat.com/web/mhtml/) . |
| static readonly [Txt](../../groupdocs.editor.formats/textualformats/txt) | Το Το έγγραφο απλού κειμένου (TXT) αντιπροσωπεύει ένα έγγραφο κειμένου που περιέχει απλό κείμενο με τη μορφή γραμμών. Μάθετε περισσότερα για αυτήν τη μορφή αρχείου[εδώ](https://wiki.fileformat.com/word-processing/txt) . |
| static readonly [Xml](../../groupdocs.editor.formats/textualformats/xml) | Έγγραφο εκτεταμένης γλώσσας σήμανσης (XML) που είναι παρόμοιο με το HTML αλλά διαφέρει στη χρήση ετικετών για τον καθορισμό αντικειμένων. Μάθετε περισσότερα για αυτήν τη μορφή αρχείου[εδώ](https://wiki.fileformat.com/web/xml) . |
| static readonly [All](../../groupdocs.editor.formats/textualformats/all) | Επιστρέφει μια εσωτερική κλάση, που παρέχει αναρίθμητες δυνατότητες σε όλες τις υπάρχουσες μορφές κειμένου. |

## Άλλα Μέλη

| Ονομα | Περιγραφή |
| --- | --- |
| class [AllEnumerable](textualformats.allenumerable) | Υλοποιεί IEnumerable γενική διεπαφή, που επιτρέπει μια δυνατότητα «foreach» για το TextualFormats type |

### Δείτε επίσης

* interface [IDocumentFormat](../idocumentformat)
* χώρος ονομάτων [GroupDocs.Editor.Formats](../../groupdocs.editor.formats)
* συνέλευση [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->
