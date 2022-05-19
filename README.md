# HomeAssistant
Mise en place de Home Assistant (Projet Open Source) sur un Raspberry Pi 3 B+

Projet liée : https://www.youtube.com/watch?v=e7MKEdTGX1U | Auteur de la vidéo : Abrège

| INSTALLATION 

Telecharger et installer Raspberry Pi Imager : https://www.raspberrypi.com/software/

1. Exécuter le avec les droits administrateur.
2. Dans 'Raspberry Pi Imager', clicker sur 'Choisissez l'OS', descender presque en bas jusqu'à 'Other Specific-purpose OS' puis 'Home assistants and home automation' enfin sur 'Homme Assistant'. Pour terminer, choisisser Home Assistant OS X.X (RPI + numéro de votre raspberry pi)

!!! L'étape suivante va entièrement supprimer toutes les données qui sont dessus (la carde SD) donc enregistrer les données avant

3. Appuyer sur Ecrire
4. Il suffit d'attendre jusqu'à la fin de l'opération (Message : 'Vous pouvez retire la carte SD')

|| ACTION !

- Brancher un cable HDMI d'un côté sur le Raspberry Pi, l'autre sur un écran
- Brancher (si vous pouvez) un cable ethernet sur le Raspberry Pi
- Insérer la carte SD à l'arrière puis brancher l'alimentation

Sur le moniteur vous devrier voir :
"Waiting for the Home Assistant CLI to be ready..."
"Welcome to the Home Assistant command line"

Affichage :

ha > _ 

ENTRER :

ha > login 

Appuyer sur Entrer puis ENTRER :

ha > nmcli device wifi list

Appuyer sur Entrer

La liste des wifi disponibles s'affiche, trouvez le votre puis entré cette commande :

ha > nmcli device wifi "nom_wifi_choisie" --ask

(remplacer nom_wifi_choisie par le wifi que vous allez utiliser mais vous devez garder les " " )

Si vous êtes sur un réseau de type wifi (maison/entreprise) vous pouvez entrer ceci dans un navigateur comme Chrome :

- http://www.homeassistant:8123

Si vous utilisé un partage de connexion (exemple : téléphone mobile (comme je le fais actuellement)) entrer ceci dans un navigateur comme Chrome :

- 


(En Cours d'écriture : 20/05/2022)
