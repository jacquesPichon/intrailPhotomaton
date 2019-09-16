# intrailPhotomaton
Dispositif de prise de photo automatique pour l'évènement Intrail muros St-Malo.
Développement en python d'un photomaton automatique.
Ce projet est en cours.

## Expression du besoin
Le trail urbain intrail muros est une course nocturne dans la ville de St-Malo. Depuis sa création, le nombre de participants ne cesse de croitre.
Les coureurs aiment conserver une photo souvenir de l'évènement. Avec 5600 coureurs au départ entre 18h30 et 21h00, il faut pouvoir proposer un service de photomaton automatisé.

## stratégie
### Au départ,
les appareils automatiques sont en libre service, un bénévole animateur surveille le bon fonctionnement et guide les coureurs dans l'utilisation.
La prise de vue se fait sur détection d'une personne. Un signal avec décompte donne le décompte 3 -2 -1 puis photo. 
La photo est affichée sur écran. puis sauvegardée. 
La reconnaissance du dossard par OCR sur la photo est faite pour renommer la photo avec le nom : <N°dossard>.jpg
Les photos sont diffusées sur le site de l'association ou un autre site, et disponible par le nom de fichier personnalisé.
si plusieurs photos sont prises, alors on ajoute 1, 2, au nom .
### A l'arrivée
Podium finisher. on prend les photos au moment de l'arrivée. Meme démarche avec stockage des photos séparé.Un bénévole accompagne les points photo
.



## Compétences et tâches à développer

 - Gestion d'un appareil photo en automatique par usb
 - Reconnaissance d'une personne dans un flux vidéo (open CV)
 - détection du dossard et lecture des caractères (numéro ) du dossard
 - renommer un fichier.
 - déposer une photo sur un site web
 * coté web
 - générer la liste des photos d'un répertoire
 - permettre la recherche d'un dossard
 - afficher une photo à la demande
 
# Restriction du projet
Le droit à l'image !!! Avertissement des utilisateur sur la diffusion de leur photo sur internet.

# objectifs
une premiere version pour janvier. 

Finalisation et test fevrier

 
 
