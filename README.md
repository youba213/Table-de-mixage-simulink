# Table-de-mixage-simulink

Ce projet consiste en la conception d'une table de mixage sous Simulink, une console de mixage utilisée pour modifier et améliorer le son d'une source audio. Elle trouve des applications dans divers domaines tels que la musique, le cinéma, la télévision, les événements en direct, etc.

## Instructions d'utilisation

Avant d'utiliser cette table de mixage, assurez-vous de suivre ces étapes :

1. Avoir une version de Matlab égale ou supérieure à R2023a.
2. Lancez Matlab et assurez-vous d'ouvrir Simulink dans le répertoire où se trouvent ces fichiers.
3. Une fois dans Simulink, accédez au menu -> "open" pour ouvrir le fichier .slx.

## Fichier de bibliothèque inclus

Ce projet comprend un fichier de bibliothèque contenant des fonctions/traitements Simulink utilisés dans le projet. Assurez-vous de le consulter pour comprendre les composants utilisés.

## Produit Final

Le fichier Table_de_mixage.slx résultant de ce projet comporte différents types d’effets, ainsi qu'un égaliseur, contrôlés par des potentiomètres et des sliders.

## Effets inclus

1. **Equalizer :** Outil permettant d'atténuer ou d'accentuer une ou plusieurs bandes de fréquences dans un signal audio. Il offre un contrôle précis sur les "graves", "medium" et "aigu".
   
2. **Filtre moyenneur :** Calcule la moyenne de son entrée sur un nombre fini d’échantillons, utile pour lisser le signal.
   
3. **Effet Echo :** Crée un effet de répétition en jouant une copie légèrement décalée du signal audio d'origine.

4. **Réverbération :** Simule l’acoustique d'un environnement physique, comme une salle de concert ou une cathédrale.

5. **Saturation :** Ajoute du caractère et de la chaleur au signal audio, simulant la distorsion dans les circuits analogiques.

6. **Flanger :** Modélise un effet de décalage temporel en décalant légèrement une copie du signal d'origine dans le temps.

## Notes
Veillez à explorer les fonctionnalités de chaque effet et à ajuster les paramètres tels que le gain, le délai, la fréquence, etc., pour obtenir l'effet sonore souhaité. N'hésitez pas à personnaliser le projet selon vos préférences et à expérimenter avec les différentes fonctionnalités offertes.
