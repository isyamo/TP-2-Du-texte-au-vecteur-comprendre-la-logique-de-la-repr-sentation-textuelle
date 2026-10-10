# Partie 5 — Représentation Bag of Words :


<img width="609" height="141" alt="TP2 IA BOW" src="https://github.com/user-attachments/assets/a40c02db-dbe7-44c8-99a5-85ead9a545de" />


1] chaque colonne de la matrice représente Un mot du vocabulaire de la phrase classé par ordre alphabétique.


2] les limites du modèle Bag of Word sont :
	    - Ignore la position des mots.
    	- Pas de pondération entre mots fréquents et rares.
	    - Les mots fréquents comme “le”, “la”, “et” dominent souvent la représentation.


3] en supprimant l’ordre des mots on perd le contexte de la phrase.



# Partie 6 — Représentation TF-IDF :


<img width="706" height="211" alt="TP2 IA TFIDF" src="https://github.com/user-attachments/assets/a47a9d93-bf38-4694-9537-fac21c5c173a" />


** Comparez les poids obtenus pour chaque mot :

      pour la 1 ere phrase:

         - les mots "effort,mene,victoire" dont le poids est de 0,53 sont des mots rares appartenant a la 1ere phrase uniquement. 

         - le mot "la" dont le poids est de 0,4 est un mot present dans la phrase 1 et 2.


      pour la 2 ème phrase:

         - les mots "bag,of,words,ignore,mots,position,des" dont le poids est de 0,36 sont des mots rares appartenant a la 2 eme phrase uniquement. 

         - le mot "la" dont le poids est de 0,28 est un mot present dans la phrase 1 et 2.


      pour la 3 eme phrase:

         - les mots "allume,instantanément,écran " dont le poids est de 0,58 sont des mots rares appartenant a la 3 eme phrase uniquement. 



  4]la différence principale entre BoW et TF-IDF est :

      - Le TF-IDF pondère les mots fréquents moins informatifs et valorise les mots rares significatifs.

      - Le BoW compte la fréquence des mots dans un document.

      

  5] les mots très fréquents ont souvent un poids faible car :Ils n'apportent pas d'information utile .
