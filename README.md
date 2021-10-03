# Choreographic sound production through Benesh system

## Μια θεωριτική προσέγγιση στην αλγορυθμική παραγωγή ήχων μέσω κινησιολογικού συστήματος Benesh

**Παύλος Νάνος**

**a20nano**

**ΙΟΝΙΟ ΠΑΝΕΠΙΣΤΗΜΙΟ**

**Τμήμα Τεχών Ήχου και Εικόνας**

**ΔΙΑΔΡΑΣΤΙΚΟΣ ΗΧΗΤΙΚΟΣ ΣΧΕΔΙΑΣΜΟΣ**

**Διδάσκων: Ιωάννης Ζάννος**

**Κέρκυρα, Εαρινο Εξάμηνο 2020 -2021**


Υπάρχουν υπεράριθμοι τρόποι να γεννήσουμε ήχο με την κίνηση του σώματος, από το απλό πάτημα των δακτύλων στα πλήκτρα ενός πιάνου έως και την τοποθέτηση αισθητήρων στο σώμα ενός χορευτή και την επεξεργασία των χωροχρόνων δεδομένων σε κώδικα. Οι συνδυασμοί και οι παράμετροι είναι άπειροι, όσα και τα σημεία του τρισδιάστατου χώρου επί τους τρόπους που μπορούμε να αντιστοιχήσουμε κάθε σημείο με μια τεχνική παραγωγής ήχου. Η χαοτική διαδικασία αυτή μπορεί να απλοποιηθεί και να αποτυπωθεί αλγοριθμικά μέσω της ευφυούς μεθόδου σημειογραφίας κινήσεων Benesh.

Ο χορός είναι μια αρχέγονη τέχνη τα πρώτα ίχνη της οποίας χρονολογούνται στα 10.000 έτη, στις ζωγραφιές σπηλαίων που ανασκάφθηκαν στα καταφύγια βράχων Bhimbetka της Ινδίας. Ενώ τα έργα τέχνης σε άλλους τομείς διασώζονται εως σήμερα όπως η ποίηση του Ομήρου, τα δράματα του Ευριπίδη, τα γλυπτά του Πραξιτέλη, οι ζωγραφιές στο Lascaux ο χορός μεταφέρεται μέσω της μνήμης. Αν δεν διδαχθεί από δάσκαλο σε μαθητή από γενια σε γενιά θα χαθεί στο πέρασμα του χρόνου. Η ανάγκη καταγραφής των χορογραφιών γεννησε τα σημειογραφικά συστήματα χορού, που επιπροσθέτως λειτουργούν και ως μέσα επικοινωνίας μεταξύ των δημιουργών-χορογράφων και των εκτελεστών-χορευτων. (Don Herbison Evans, 1988, 45)

Το Bebesh Movement Notation αποτελεί σύστημα καταγραφής των κινήσεων μιας χορογραφίας πάνω σε πεντάγραμο με τη χρήση συμβόλων. Επινοήθηκε το 1947 απο τον Βρετανό μαθηματικό Rudolf Benesh και την γυναίκα του Joan, χορεύτρια μπαλέτου για να απεικονίσουν συμβολικά την κίνηση του ανθρώπινου σώματος πάνω σε χαρτί (Fernau Hall, 1967, 188-189). Οι γραμμές του πενταγράμμου αναπαριστούν τα πέντε κύρια επίπεδα που διαιρείται υψομετρικά το ανθρώπινο σώμα, τα πέλματα, τα γόνατα, τη μέση, τους ώμους και την κορυφή του κεφαλιού. Κάθετα διέρχεται μια διακεκομμένη γραμμη που ορίζει τον κατακόρυφο άξονα που χωρίζει το σώμα στο δεξί και το αριστερό μέρος. Η οπτική  κατα σύμβαση είναι στην πλάτη του χορευτή δηλαδή η παρατήρηση των κινήσεων γίνεται από το πίσω μέρος. Στο νοητό αυτό πίνακα που πλαισιώνει τη μορφή καταγράφονται οι θέσεις των άκρων σε σχέση με τον κορμό με σύμβολα, για παράδειγμα το "-" χαρακτηρίζει το συνεπίπεδο, το "." το προεκτεταμένο προς τα πίσω ενω το "Ι" το προεκτεταμένο προς τα μπροστά. Παρομοίως αναπαριστούνται και οι θέσεις των αρθώσεων αγκώνων και γονάτων και του κεφαλιού. Κάθε συμπληρωμενος πίνακας αποτελεί ενα στιγμιότυπο της κίνησης και η χρονική διαδοχή διαβάζεται από τα αριστερά προς τα δεξιά. (Ryman, Singh, Beatty, Booth, 1984, 27-28)

Το σύστημα Benesh καθώς και τα υπόλοιπα συστήματα σημειογραφίας κίνησης όπως το επίσης διαδεδομένο Labanotation είχαν κάποια λειτουργικά μειονεκτήματα που ήρθαν να καλύψουν αργότερα οι υπολογιστές. Αρχικά είναι αδύνατο να καταγραφεί η χορογραφία σε πραγματικό χρόνο σε οποιοδήποτε σύστημα. Επίσης ελάχιστοι χορευτές γνωρίζουν καλά να διαβάζουν και να γράφουν Benesh η Labanotation. Επιπροσθέτως σε περίπτωση που ο χορογραφος θέλει να κάνει μια μικρή αλλαγή στη χορογραφία πρέπει να ξαναγράψει εξ'ολοκλήρου την ενότητα της χορογραφίας εκ νέου. Από την άλλη η απλή βιντεοσκόπιση ως μεσο καταγραφής μιας χορευτικής πραστασης υστερεί σε μεγάλο βαθμό αφού ο θεατής μπορεί να παρατηρήσει μεσά από μια συγκεκρημένη οπτική γωνία. Με αυτό τον τρόπο δεν είναι εμφανείς οι κινήσεις του συνόλου των χορευτώνν αφου κάποιοι μπορεί να βρίσκονται πίσω από άλλους. Ακόμα και εγγραφές από πολλές οπτικές γωνίες δεν θα ήταν επαρκείς αφού οι δυνατότητες επεξεργασίας του υλικού είναι περιορισμένες και έως πρόσφατα η αλλαγή των μέσων αποθήκευσης των βίντεο από ταινίες σε κασέτες σε DVD κτλ. οδηγούσαν στην απώλεια ποιότητας. Η χρήση ηλεκρτονικών υπολογιστών έδωσε νέες δυνατότητες σε χορευτές και χορογράφους. Με την ψηφιακή κωδικοποίηση των σημειογραφικών συστημάτων μπορούσε να γίνει αποθήκευση και επεξεργασία της κινησιολογίας με ευκολία και ταχύτητα. Επίσης έγινε δυνατή η αναπαραγωγή της χορογραφίας με animation σε πραγματικό χρόνο με θέαση από όλες τις οπτικές γωνίες, πράγμα που έδωσε νέες δημιουργικές προοπτικές στους χορογράφους και ευκολία ανάγνωσης και κατανόησης στους χορευτές. (Don Herbison Evans, 1988, 46-48)

Το 1979 στο Πανεπιστήμιο της Πενσυλβάνια ο N.I. Badler και ο S.W. Smoliar επιχείρησαν να σχεδιάσουν ένα γραφικό επεξεργαστή που χρησιμοποιούσε Labanotation και μέσω μεταγλωττιστή να παράγει animation. Το 1986 στον Καναδά ο Thomas Calvert, από το πανεπιστήμιο της Βρετανικής Κολομβίας, και ο Simon Frazer, από το Πανεπιστήμιο Waterloo στο Ontario, ανέπτυξαν σε Macintosh, λογισμικό επεξεργασίας συστήματος Benesh που κινούσε φιγούρες στον τρισδιάστατο χώρο. Επίσης με γραφική αναπαράσταση συστήματος Benesh με ελλειψοειδή μοντέλα animation ασχολήθηκαν και οι G. Politis και Don Herbison Evans την ίδια χρονιά. (Fugedi, 1991, 105-106)

Το επόμενο βήμα στην τεχνολιγική εξέλιξη του χορού ήταν η ψηφιακή καταγραφή των κινήσεων σε πραγματικό χρόνο σε υπολογιστή μέσω αισθητήρων. Οι υπολογιστές προγραμματίζονται ωστε να λαμβάνουν τα δεδομένα, να τα αποθηκέυουν και να τα αναπαριστούν γραφικά. Στο πανεπιστήμιο Tufts της Μασσαχουσέτης H Alice Trexler και ο Ronald Thorton στις αρχές της δεκαετίας του 1990 χρησιμοποίησαν αισθητήρες που έστελναν υψίσυχνους παλμούς ήχου σε φάσμα 30 μοιρών που ανακλούσαν πάνω σε αντικείμενα και έπειτα ανίχνευαν την ηχώ που επέστρεφε. Ο υπολογιστής μετρώντας το μεσοδιάστηματα μεταξύ μετάδοσης και πρόσληψης επέστρεφε δεδομένα για τη θέση, την κατευθυνση, την ταχύτητα και την επιτάχυνση κάθε μέρος του σώματος. Η επεξεργασία των δεδομένων έγινε σε Macintosh. Το πρόγραμμα αυτό χρησιμοποιήθηκε εκτενώς με επιτυχία από τους φοιτητές στα εργαστήρια του Tufts για την εκμάθηση χορογραφιών, την δημιουργία κινησιολογικών μοτίβων και τον καλλιτεχνικό σχεδιασμό εικαστικών έργων που μπορούσαν να παραχθούν με την χαρτογράφηση των κινήσεων. H εφαρμογή των μελετων του πανεπιστημίου δεν περιορίστηκε εκεί. Κατασκεύασαν με τη βοήθεια των αισθητήρων μια διαραστική παράσταση που παρήγαγε γραφικά σε δύο οθόνες προβολής ανάλογα με τις κινήσεις δυο χορευτών. Το μεταβαλλόμενο αυτό σκηνικό πλαισίωνε τους καλλιτέχνες οι οποίοι το ενορχηστρώνανε οπτικά μεσα από την αλληλεπίδραση με τους αισθητήρες. (Gray, 1989, 69-73)

Ένα άλλο είδος καταγραφής και ανάλυσης κίνησης μπορεί να γινει μέσω μηχανογραφικής επεξεργασίας εικόνων βίντεο. Αρχικά η εικόνα μετατρέπεται από αναλογική σε ψηφιακή. Στην συνέχεια το ψηφοποιημένο καρέ αναλύεται και οι πληροφορίες χρησιμοποιούται για την εξαγωγή συμπερασμάτων για τις θέσεις των σημείων του σώματος καθώς και το είδος των κινήσεων. (Gray, 1989, 130-132). Το 2012 οι Saad, De Beul, Mahmoudi και Mannerback από το πανεπιστήμιο UMONS του Βελγίου πρότειναν ένα σύστημα οντολογίας κίνησης βίντεο (VMO) με τη χρήση οντολογικής γλώσσας ιστού (OWL) βασισμένο στο σύστημα Benesh για την περιγραφή οποιασδήποτε μορφής ανθρώπινης κίνησης. Με την βοήθεια της γλώσσας σημασιολογικών κανόνων ιστού (SQRL) ορίσανε τις έννοιες και ένα πλήρες αξιωματικό σύστημα που περιγράφει με ακρίβεια όλες τις θέσεις και κινήσεις του σώματος. (Saad, De Beul, Mahmoudi,Mannerback, 2012, 1-5)

Η παραγωγή ήχου με ηλεκτρικά μέσα χωρίς επαφή εγινε για πρώτη φορά με την εφεύρεση του Theremin. Σήμερα οι χειρονομίες και οι κινήσεις μπορούν να μεταφραστούν σε ψηφικά δεδομένα που παράγουν ηχητικές συνθέσεις. Διακρίνουμε δύο είδη αισθητήρων, οι χωρικοί που ανιχνεύουν είτε τη θέση του αντικειμένου στον τρισδιάστατο χώρο με βάση αποστάσεις από σημεία αναφοράς και οι αισθητήρες σώματος που μετρούν την θέση, ορμη και γωνία των διαφόρων μερώ του σώματος. Παραδείγματα χωρικών αισθητήρων αποτελεί το Radio Drum που μετράει τη θέση δύο μπαγκετών σε σχέση με εναν ορθογώνιο δέκτη, ο Donald Bucha's Lightning που χρησιμοποιεί υπέρυθρες ακτίνες για τον εντοπισμό του χορευτή με δισδιάστατες συντεταγμένες, το David Rokby's Very Nervous System και το Virtual Stage Enviroment  που αναλύουν την κίνηση με τη χρήση βιντεοκαμερών κ.α. Παραδείγματα σωματικών αισθητήρων είναι ο MIDI Dancer που αναλύει την τοποθέτηση των μελών του σώματος, το BioMuse που μετρά την ηλεκτρική τάση που παράγει η σύσπαση των μυών, το The Hands που αναγνωρίζει τις χειρονομίες κ.α. Τα δεδομένα των αισθητήρων μπορούν να μεταφραστούν με πλήθος τρόπων δίνοντας διαφορετικές μουσικές δυνατότητες. (Winkler, 1995, 1-3)

Το σύστημα Benesh προτείνει μια πλήρη αλλά απλή κωδικοποίηση θέσεων και κινήσεων του σώματος. Όπως είδαμε διάφοροι αισθητήρες μπορούν να εισάγουν τα δεδομένα αυτά στον υπολογιστή και αυτός με τη σειρά του να τα μεταγλωττίσει με ευκολία στο σημειογραφικό σύστημα Benesh. Στη συνέχεια μπορούν να χρησιμοποιηθούν συναρτήσεις που αντιστοιχούν τα σημεία της χορογραφίας σε ήχους. Για παράδειγμα οι κινήσεις χεριών, ποδιών και κεφαλιού θα μπορούσαν να μεταφραστούν αριθμητικά με κατάλληλη χαρτογράφηση σε ορίσματα συναρτήσεων παραγωγής ήχου 3 μεταβλητών στο supercolider, όπως η συνάρτηση SinOsc. Μπορούν να γραφούν διάφοροι αλγόρυθμοι όπου η μουσική σύνθεση να εναρμονίζεται με την κίνηση ή να δρα αντίθετα με τους φυρικούς νόμους, όπως για παράδειγμα για έντονη κίνηση να παράξει μια ήπια μελωδία ενώ μια αρμονική να γεννήσει έναν εκοφαντικό κρότο. Η ερμηνία των κινήσεων ενός χορευτή μέσω διαδραστικών συστημάτων σε συνδιασμό με την δυναμική των ήχων δίνει απεριόριτσες δυνατότητες για καλλιτεχνική δημιουργία.   


## Βιβλιογραφία
1. (Don Herbison Evans, 1988, 45)
2. (Fernau Hall, 1967, 188-189)
3. (Ryman, Singh, Beatty, Booth, 1984, 27-28)
4. (Fugedi, 1991, 105-106)
5. (Gray, 1989, 69-73)
6. (Saad, De Beul, Mahmoudi,Mannerback, 2012, 1-5)
7. (Winkler, 1995, 1-3)




