Το BusyBox είναι ένα μικρό σε μέγεθος εκτελέσιμο αρχείο το οποίο περιλαμβάνει τις πιο βασικές λειτουργίες του UNIX. Είναι δηλαδή ένα απλοποιημένο UNIX. Παρά το γεγονός ότι είναι περιορισμένο, επομένως δεν ισοδυναμεί με ένα ολοκληρωμένο σύστημα GNU, φαίνεται όμως πως πραγματοποιεί  σχεδόν τις ίδιες λειτουργίες, όπως και ήταν αναμενόμενο.[1]

{.figure}

Έχει γραφτεί με σκοπό την μικρή χωρητικότητα, τη μικρή χρήση πόρων και την δυνατότητα να συμπεριλαμβάνουμε ή εξαιρούμε εντολές κατά τον χρόνο μεταγλώττισης. Αυτό σημαίνει ότι ή χρήση του είναι σημαντική σε ενσωματωμένα λειτουργικά συστήματα. Μπορεί να εκτελεστεί σε περιβάλλοντα όπως POSIX, Android, FReeBSD και ειδικά σε Linux λόγω του σχεδιασμού του να λειτουργεί με διεπαφές που παρέχονται από τον πυρήνα του. Έτσι για τη κατασκευή ενός λειτουργικού συστήματος χρειάζεται απλά μία προσθήκη από device nodes στο κατάλογο /dev , configuration files στο /etc και έναν πυρήνα Linux. Ακόμη η παρουσία του εμφανίζεται σε root εφαρμογές του Android , στο VMware ESXi , OpenWrt, OpenEmbedded.[2]

Η πρώτη ολοκληρωμένη συγγραφή του BusyBox πραγματοποιήθηκε το 1996 από τον Bruce Perens με αρχικό σκοπό να δημιουργήσει ένα GNU/Linux σύστημα  σε μία δισκέτα που θα χρησιμοποιούταν για εγκατάσταση ή θα είχε το ρόλο ως δισκέτα διάσωσης[3]. Έγινε το βασικό σύνολο εργαλείων για ενσωματωμένες  συσκευές Linux και installers χάρη στο βασικό του πλεονέκτημα για την εξοικονόμηση χώρου. Η συντήρηση του και η εξέλιξη του προήλθε από αρκετούς προγραμματιστές, όπως τον Enrique Zanardi που συνέχισε τον ρόλο με την ανάγκη του συστήματος εγκατάστασης για τις δισκέτες εκκίνησης  Debian, ενώ στη συνέχεια ο Dave Cinege το ανέλαβε για το Linux Router Project, καθώς το συνέχισε ο Erik Andersen και ύστερα από το 2006 ο Denys Vlassnko. Σημαντικό ακόμη είναι πως η φήμη του έγινε πολύ μεγάλη όταν το Linux είχε πολύ μεγάλο αριθμό αγορών.  

Η GNU General Public License (GPL-2.0) άδεια ως ελεύθερο λογισμικό, του αποδόθηκε το Σεπτέμβριο του 2006.[4]

Διαθέτει πολύ σπουδαία χαρακτηριστικά που εξυπηρετούν την ευελιξία του και αντιπροσωπεύουν τις δυνατότητες του. Παρέχει περισσότερες από διακόσιες λειτουργίες και χρησιμοποιεί το Almquist shell, ενώ μπορεί να υποστηρίξει και άλλα ανάλογα με τις προσαρμογές του[5]. Εξίσου σημαντικό είναι πως αποτελεί δυαδικό αρχείο. Αυτό σημαίνει πως μπορεί να κληθεί απευθείας και από οποιαδήποτε εφαρμογή χωρίς να πρέπει να είναι σε μορφή βιβλιοθήκης. Βέβαια οι εντολές που περιλαμβάνει είναι πιο απλουστευμένες από αυτές που παρέχει ένα ολοκληρωμένο λειτουργικό σύστημα για παράδειγμα στην εντολή ls δεν παρέχει τη δυνατότητα ταξινόμησης[6]. Είναι λογικό ότι, διαδραματίζει σημαντικό ρόλο στην έναρξη του συστήματος και για αυτό μπορεί να αντικαταστήσει την αρχική διεργασία init.

### Αναφορές

1. [Επίσημη ιστοσελίδα busybox](https://busybox.net/about.html)
2. [Wikipedia](https://en.wikipedia.org/wiki/BusyBox)
3. [Web Archieve](https://web.archive.org/web/20081209025021/http://www-128.ibm.com/developerworks/library/l-busybox/index.html)
4. [License GPL-2.0](https://lwn.net/Articles/202113/)
5. [Compatible Shells](https://web.archive.org/web/20100310193527/http://www.in-ulm.de/~mascheck/various/ash/#busybox)
6. [Εντολές BusyBox](https://www.busybox.net/downloads/BusyBox.html)