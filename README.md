# page de chargement automatique de données météo
===========

Il s'agirait de faire une page de briefing météo facilement paramétrable pour s'adapter à chaque club.

##Pour rentrer son code aéroweb dans le script:

Ouvrez google chrome (c'est obligatoire de le faire avec chrome)  
Deconnectez votre session aeroweb si vous en avez une en cours.  
Ouvrez https://aviation.meteo.fr/login.php  
Entrez votre login et mot de passe mais ne validez pas!  
Affichez les outils de developpement (la fonctionalite de google qui nous interesse, on la trouve dans afficher -> option pour les developpeurs -> outils de developpement, ou aussi le bouton a droute de la barre d'adresse -> plus d'outils -> outils de developpement  
Sur l'onglet aeroweb bien sur ;) pas celui où vous visualisez ce message..  
N'ayez pas peur et cliquez sur l'onglet Network  
Juste en dessous cochez la case "preserve log"  
Maintenant vous pouvez vous logger dans ce qu'il reste de la fenetre.  
Quand tout ce joli bordel s'est arreté de bouger, remontez tout en haut de la liste de fichiers qui s'est créée pendant le chargement, le tout premier fichier devrait etre "login_valid.php"  
Cliquez dessus  
Allez voir tout en bas de ce qui vient d'apparaitre ( vous devez etre dans l'onglet "headers")  
Il y a votre login et votre mot de passe tels qu'ils on ete transféré au site de meteo france, pour moi "briffe" et une suite de chiffre et de lettres qui n'ont rien a voir avec mon mot de passe.  
Essayez avec ca dans le fichier html ;)  
