# Παραδοτέο 2 - Προσθήκες

[Αποθετήριο κώδικα παραδοτέου](https://github.com/p15zerv/pacman/tree/Deliverable1)

## Αλλαγές και προσθήκες στο tileset

![red-tiles](https://user-images.githubusercontent.com/22644005/35176914-a6cdbf10-fd84-11e7-8fe9-53194520ae8a.png)

* Αλλαγή χρωμάτων
* Προσθήκη νέων tile:
  - <img src="https://user-images.githubusercontent.com/22644005/35171551-db522388-fd6c-11e7-9805-eaa03d4d1428.PNG" alt="" width="30" height="30"> Αναπαριστά τα σημεία τοποθέτησης των λουλουδιών.
  - <img src="https://user-images.githubusercontent.com/22644005/35171950-39d5314c-fd6e-11e7-9780-05abd146a363.PNG" alt="" width="30" height="30"> Αναπαριστά τα σημεία τοποθέτησης των φρούτων (παραδοτέο 3).
  - <img src="https://user-images.githubusercontent.com/22644005/35172033-c1c9a61e-fd6e-11e7-86c0-59aa561c6d3c.png" alt="" width="30" height="30"> Αναπαριστά το σημείο τοποθέτησης του παίκτη.
  - <img src="https://user-images.githubusercontent.com/22644005/35172128-15ba0ade-fd6f-11e7-9016-e9d96758941e.PNG" alt="" width="30" height="30"> Αναπαριστά τα σημεία τοποθέτησης των εχθρών (παραδοτέο 3).
  - <img src="https://user-images.githubusercontent.com/22644005/35172814-d66533ba-fd71-11e7-886f-f78ada186360.PNG" alt="" width="30" height="30"> Αναπαριστά το σημείο τοποθέτησης της πέτρας (παραδοτέο 3).
  - <img src="https://user-images.githubusercontent.com/22644005/35172815-d7d64298-fd71-11e7-8ae6-8df2c05ae1ac.PNG" alt="" width="30" height="30"> Αναπαριστά το σημείο τοποθέτησης του καλαθιού.
  
  Πληροφορίες για τα αντικείμενα που δεν αναφέρονται σε αυτό το παραδοτέο μπορούν να βρεθούν στο παραδοτέο που αναφέρεται στις παρενθέσεις.
  
  Όλα τα παραπάνω tiles αντικαθίστανται με το αντίστοιχο αντικείμενο μόλις εντοπιστούν.
  
## Δημιουργία νέας πίστας μέσω Tiled

<img src="https://user-images.githubusercontent.com/22644005/35171451-818afc30-fd6c-11e7-9bdd-d062edde833a.PNG" alt="" width="225" height="250">

## Αλλαγή εμφάνισης του παίκτη

![red2](https://user-images.githubusercontent.com/22644005/32405822-2a9a6eb6-c175-11e7-8130-5228221c597f.png)

[Πηγή](https://slimsresources.wordpress.com/)

## Προσθήκη αντικειμένου που συλλέγει ο παίκτης

<img src="https://user-images.githubusercontent.com/22644005/32405905-e5d61e2c-c176-11e7-9241-53c15a2aead4.png" alt="" width="30" height="30">

[Πηγή](https://kandipatterns.com/patterns/misc/flower-20789)

Το λουλούδι είναι **νέο αντικείμενο**, που προστίθεται στην πίστα με τη βοήθεια του νέου tile που αναφέρεται παραπάνω. Αν ο παίκτης έρθει σε επαφή με αυτά αυξάνεται το score. Δεν είναι αναγκαία η συλλογή τους για τη συνέχεια σε επόμενη πίστα.

## Προσθήκη μουσικής και ηχητικών εφέ

* Προσθήκη **μουσικής**. Διαφορετική για το μενού και το gameplay. [Πηγή](http://freemusicarchive.org/music/Kevin_MacLeod/)
* Προσθήκη **ηχητικών εφέ**. Διαφορετικά για συλλογή κάθε αντικειμένου, χάσιμου ζωής, τέλους παιχνιδιού και τέλους πίστας. [Πηγή](https://freesound.org/people/LittleRobotSoundFactory/packs/16681/)

## Προσθήκη score, χρόνου, bonus και ζωών
* Προσθήκη **χρόνου** και **score**. 
* Προσθήκη καλαθιού. ![basket](https://user-images.githubusercontent.com/22644005/35177751-b29b002c-fd8a-11e7-8b7f-12c66104a59a.png) Nέο **αντικειμένου bonus** το οποίο εμφανίζεται στην πίστα σε μία τυχαία χρονική στιγμή μεταξύ 10 και 20 seconds. Αν ο παίκτης το συλλέξει, προσθέτει 1000 στο score και καταστρέφεται. Εναλλακτικά, αν περάσουν 10 δευτερόλεπτα από τη δημιουργία του και δεν έχει συλλεχθεί, το αντικείμενο καταστρέφεται χωρίς να αυξηθεί το score. [Πηγή](http://www.clipartpanda.com/clipart_images/picnic-basket-36837750)
* Προσθήκη **συστήματος ζωών**. Ο παίκτης ξεκινάει με 3 ζωές και χάνει μία αν έρθει σε επαφή με εχθρό. Αν χάσει όλες του τις ζωές, εμφανίζεται ανάλογη οθόνη και γίνεται αναπαραγωγή ηχητικού εφέ και επιστρέφει στο αρχικό menu.

