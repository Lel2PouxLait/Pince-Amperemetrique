# Pince-Amperemetrique
Pince ampèremétrique permettant de transmettre le courant mesuré via Lora.
Projet IOT de Antoine Loubersanes et Julien Beltrame.

Notre projet utilise l'OS RiotOS. Pour pouvoir être compilé convenablement par ce dernier, le dossier endpoint/src/ doit-être placé dans 
le dossier RIOT/examples/ de RiotOS.

Voici l'architecture du dépot git :

endpoint/  
-------├── src/                    # Code source
-------├── report/  
----------------├── img/           #Dossier contenant les images utilisées dans le report.md
----------------├── Flyer          #Flyer de notre produit
----------------├── Presentation   #Diapo de présentation de notre produit
----------------├── report.md      #Rapport au format markdown

