# lossless-Compression

# Περιγραφή Εφαρμογής
Αυτή η εφαρμογή Bash εκτελεί μια σειρά από διαδικασίες για την ανάλυση, κωδικοποίηση, και συμπίεση κειμένου. Συγκεκριμένα, η εφαρμογή:

Ανάλυση Συχνότητας Λέξεων: Εξάγει λέξεις από ένα αρχείο κειμένου (Adams.txt), υπολογίζει τη συχνότητά τους και αποθηκεύει τις πληροφορίες αυτές μαζί με το μήκος κάθε λέξης και το συνολικό "κόστος" της λέξης.

Κωδικοποίηση Λέξεων: Κάθε λέξη κωδικοποιείται με έναν μοναδικό ASCII χαρακτήρα ή συνδυασμό χαρακτήρων. Εάν οι διαθέσιμοι χαρακτήρες εξαντληθούν, δημιουργούνται συνδυασμοί πολλών χαρακτήρων.

Δημιουργία Κωδικοποιημένου Κειμένου: Το αρχικό κείμενο (Adams.txt) μετατρέπεται σε ένα νέο κωδικοποιημένο αρχείο (coded.txt) χρησιμοποιώντας τον κωδικοποιημένο χάρτη λέξεων.

Αποκωδικοποίηση Κειμένου: Το κωδικοποιημένο κείμενο αποκωδικοποιείται και συγκρίνεται με το αρχικό αρχείο για να διασφαλιστεί η ακρίβεια της διαδικασίας.

Συμπίεση Αρχείων: Συμπιέζει το αρχικό και το κωδικοποιημένο κείμενο με τη χρήση Gzip και υπολογίζει το ποσοστό συμπίεσης, συγκρίνοντας την αποδοτικότητα της διαδικασίας.

Διαχείριση Αρχείων: Μετά την ολοκλήρωση της διαδικασίας, τα προσωρινά αρχεία διαγράφονται για να εξασφαλιστεί η βέλτιστη διαχείριση πόρων.

Αυτή η εφαρμογή είναι χρήσιμη για όσους θέλουν να πειραματιστούν με τεχνικές κωδικοποίησης και συμπίεσης κειμένων, και να δουν τα αποτελέσματα σε πραγματικό χρόνο.
