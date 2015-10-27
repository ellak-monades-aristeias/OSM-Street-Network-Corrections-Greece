### Επεξεργασία δεδομένων του OpenStreetMap Project για χρήση από εφαρμογές GIS - Μέρος Β’
**Επέκταση στην υπόλοιπη Ελλάδα _(OSM-Street-Network-Corrections-Greece)_**

Το έργο αυτό αποτελεί επέκταση εφαρμογής του έργου "Επεξεργασία δεδομένων του OpenStreetMap Project για χρήση από εφαρμογές GIS - Μέρος Α’: Πιλοτική Εφαρμογή στην Περιφέρεια Αττικής (πλην Νήσων)" ([OSM-Street-Network-Corrections-Attica](https://github.com/ellak-monades-aristeias/OSM-Street-Network-Corrections-Attica)) στο υπόλοιπο του ελλαδικού χώρου.

Το OpenStreetMap Project παρέχει δεδομένα οδικού δικτύου με εκτενή γεωγραφική κάλυψη που μπορούν να εξυπηρετήσουν πολλαπλές ανάγκες. Η λεπτομέρεια των δεδομένων καθώς και η διαρκής ενημέρωσή τους από μία ευρεία κοινότητα χρηστών παρέχουν ένα πολύ καλό υπόβαθρο για εφαρμογές που σχετίζονται με οδικά συγκοινωνιακά δίκτυα.

Ωστόσο, στην πρωτογενή τους μορφή τα δεδομένα αυτά δεν μπορούν να χρησιμοποιηθούν άμεσα από αρκετές εφαρμογές GIS, όπως εφαρμογές πλοήγησης, εύρεσης βέλτιστης διαδρομής κλπ., λόγω ορισμένων αδυναμιών που παρουσιάζουν, όπως:

1. Μη ύπαρξη τοπολογικών κόμβων (nodes) στις περισσότερες διασταυρώσεις των αξόνων.
2. Ατέλειες και ασυνέχειες της κατηγοριοποίησης των οδικών αξόνων.

Στόχος του παρόντος έργου είναι η αντιμετώπιση των προβλημάτων αυτών, ώστε να καταστεί το οδικό δίκτυο του OSM περισσότερο αξιοποιήσιμο από εφαρμογές GIS, κάνοντας τη λιγότερη δυνατή χειρωνακτική εργασία. Για τον λόγο αυτό εφαρμόστηκαν η εξειδικευμένη μεθοδολογία και τα customization scripts που δημιουργήθηκαν για το Μέρος Α' (πιλοτική εφαρμογή στην Αττική) στο σύνολο του ελλαδικού χώρου, μέσα στο περιβάλλον του ελεύθερου open-source λογισμικού QGIS.

Υπάρχουν πολλά ακόμη που μπορούν να γίνουν ώστε να καταστεί ένα οδικό δίκτυο ακόμη πιο αξιοποιήσιμο από εφαρμογές GIS (όπως λεπτομερέστερη κατηγοριοποίηση των τόξων του δικτύου, εισαγωγή ειδικών περιορισμών κίνησης, τυποποίηση αναγραφών ονομασιών οδών κ.α.), εντούτοις σκοπός του παρόντος έργου είναι η αντιμετώπιση των δύο κυριότερων αδυναμιών που προαναφέρθηκαν.

Για περισσότερες πληροφορίες, παρακαλώ δείτε το [Wiki Page](https://github.com/ellak-monades-aristeias/OSM-Street-Network-Corrections-Greece/wiki).

Για πληροφορίες σχετικά με τη διαδικασία παραγωγής των διορθωμένων δεδομένων OSM, παρακαλώ δείτε το [Wiki Page του έργου
"OSM-Street-Network-Corrections-Attica"](https://github.com/ellak-monades-aristeias/OSM-Street-Network-Corrections-Attica/wiki).

Τεκμηρίωση για τη διαδικασία παρέχεται στα pdf αρχεία:
* **Διαδικασία_Διορθώσεων_OSM_QGIS.pdf**: Πλήρης καταγραφή διαδικασίας & εργασιών για developers και χρήστες που ενδιαφέρονται να την εφαρμόσουν, τροποποιήσουν, επεκτείνουν κλπ.
* **Διαδικασία_Διορθώσεων_OSM_Simple.pdf**: Συνοπτικές οδηγίες για απλούς χρήστες.

Τα παραπάνω αρχεία βρίσκονται στο archive του Μέρους Α' (OSM-Street-Network-Corrections-Attica): [_OSM_Street_Network_Corrections_Reports.7z_](https://github.com/ellak-monades-aristeias/OSM-Street-Network-Corrections-Attica/blob/master/OSM_Street_Network_Corrections_Reports.7z)

Μπορείτε να καταχωρείτε ως [issues](https://github.com/ellak-monades-aristeias/OSM-Street-Network-Corrections-Greece/issues) όποιες βελτιώσεις, δυσλειτουργίες, προτάσεις κλπ. έχετε εντοπίσει σχετικά με το έργο αυτό.

**Παραδοτέα**

Τα παραδοτέα αρχεία του έργου βρίσκονται στους εξής συνδέσμους:

|       |                          **Παραδοτέο**                            |**URL**|
|:-----:|:------------------------------------------------------------------|:-----:|
|   1   |Part 1/4 σε WGS'84|https://www.dropbox.com/s/tt1k35cq4gfozcc/roads_corrected_wgs84_part1of4.7z?dl=0|
|   2   |Part 2/4 σε WGS'84|https://www.dropbox.com/s/lznwm1xf8bkr0uz/roads_corrected_wgs84_part2of4.7z?dl=0|
|   3   |Part 3/4 σε WGS'84|https://www.dropbox.com/s/qwvvzpr8tvuintm/roads_corrected_wgs84_part3of4.7z?dl=0|
|   4   |Part 4/4 σε WGS'84|https://www.dropbox.com/s/u7jk7x94mgm7127/roads_corrected_wgs84_part4of4.7z?dl=0|
|   5   |**Άξονες Ελλάδας σε WGS'84**|**https://www.dropbox.com/s/o94z93vi98gabli/roads_corrected_wgs84.7z?dl=0**|
|   6   |Part 1/4 σε ΕΓΣΑ'87|https://www.dropbox.com/s/lmo2s3sq2bp0iye/roads_corrected_ggrs87_part1of4.7z?dl=0|
|   7   |Part 2/4 σε ΕΓΣΑ'87|https://www.dropbox.com/s/ycsd8c71gcbnm6w/roads_corrected_ggrs87_part2of4.7z?dl=0|
|   8   |Part 3/4 σε ΕΓΣΑ'87|https://www.dropbox.com/s/g3od7oi0qi71zv1/roads_corrected_ggrs87_part3of4.7z?dl=0|
|   9   |Part 4/4 σε ΕΓΣΑ'87|https://www.dropbox.com/s/hoiks7femj34auj/roads_corrected_ggrs87_part4of4.7z?dl=0|
|  10   |**Άξονες Ελλάδας σε ΕΓΣΑ'87**|**https://www.dropbox.com/s/qo5wh9aafwwotsu/roads_corrected_ggrs87.7z?dl=0**|

Όπου:
  * Part 1/4 = Διορθωμένοι άξονες οδικού δικτύου Πελοποννήσου, Δυτικής Ελλάδας, Στερεάς Ελλάδας, Αττικής (Νήσων)
  * Part 2/4 = Διορθωμένοι άξονες οδικού δικτύου Θεσσαλίας, Ηπείρου, Ιονίων Νήσων
  * Part 3/4 = Διορθωμένοι άξονες οδικού δικτύου Δυτικής Μακεδονίας, Κεντρικής Μακεδονίας, Ανατολικής Μακεδονίας και Θράκης
  * Part 4/4 = Διορθωμένοι άξονες οδικού δικτύου Βορείου Αιγαίου, Νοτίου Αιγαίου, Κρήτης

Μπορείτε να [κατεβάσετε και από Dropbox τα παραδοτέα αρχεία](https://www.dropbox.com/sh/zuirfdyw40qjmaa/AADnVgnV5dkfuyRs9ugll5s1a?dl=0) του έργου. _Ορισμένα αρχεία λόγω του μεγέθους τους δεν στάθηκε δυνατόν να ανέβουν στο αποθετήριο του έργου._

Δείτε εδώ αναλυτικότερες [πληροφορίες για τα Παραδοτέα](https://github.com/ellak-monades-aristeias/OSM-Street-Network-Corrections-Greece/wiki/Deliverables).

**Το υλικό του έργου αυτού διατίθεται υπό τις Άδειες:**
- CC-BY-SA 4.0: Αρχεία διαδικασιών, πινάκων, κειμένων κλπ.
- EUPL 1.1: Scripts παραμετροποίησης
- ODbL 1.0: Χαρτογραφικά δεδομένα (shapefiles) από OSM (πρωτογενή αρχεία) & διορθωμένα παράγωγα αυτών
