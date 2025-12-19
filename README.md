🎄 Smashable Christmas Lights (Version Moderne)

Une version moderne et légère der la guirlande de Noël "cassable". Ce projet est une réécriture complète en Vanilla JavaScript et CSS moderne, sans aucune dépendance externe (pas d'images, pas de bibliothèques lourdes).

✨ Fonctionnalités

Zéro dépendance : Pas besoin de jQuery, YUI ou SoundManager2.

Performances : Animations via requestAnimationFrame et accélération matérielle CSS.

Rendu Vectoriel : Utilise SVG pour le fil et CSS pour les ampoules, garantissant une netteté parfaite sur tous les écrans (Retina/4K).

Audio Synthétique : Le son de bris de verre est généré en temps réel via l'API Web Audio, évitant le chargement de fichiers MP3.

Responsive : La guirlande s'adapte automatiquement à la largeur de la fenêtre.

🚀 Installation rapide

Il suffit d'inclure le fichier christmas_lights.html dans votre projet ou de copier le code CSS et JS dans vos fichiers respectifs.

Structure du projet

christmas_lights.html : Contient l'intégralité de la structure, des styles et de la logique.

🛠 Personnalisation

Vous pouvez facilement modifier les couleurs des ampoules dans le script JS :

const colors = ['#ff4d4d', '#4dff4d', '#4d94ff', '#ffdb4d', '#ff4dff'];


Ou ajuster l'espacement entre les lumières :

const bulbSpacing = 45; 


📜 Licence

Ce projet est sous licence MIT. Libre à vous de l'utiliser pour vos sites personnels ou commerciaux !

Inspiré par le travail original de Scott Schiller (Schillmania). https://github.com/Prosk8er/Smashable-Christmas-Lights
