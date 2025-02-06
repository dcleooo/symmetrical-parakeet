# symmetrical-parakeet

Brainstorming:

On va creer une balance connecté.
Les donnees seront envoyées par bluetooth sur le téléphone ou sur la base de donnée.
Une base de donnée ou il y aura utilisateurs, séances, performances.
On va créer une application avec differents programme d'entrainements.



Matériel necessaire :

Capteur de poids (load cell) – par exemple, une cellule de charge de 5 kg, 10 kg, etc.

Convertisseur analogique-numérique HX711 – car le Raspberry Pi Zero n'a pas d'entrée analogique. Le HX711 convertit les signaux analogiques du capteur en données numériques exploitables.

Raspberry Pi Zero (ou Zero W pour du WiFi intégré)

Écran LCD ou OLED (optionnel) – pour afficher le poids directement sur l’appareil.

Alimentation adaptée – si l'utilisation est en mobilité, une batterie LiPo + module de gestion peut être envisagée.

Connexion Bluetooth/WiFi – selon le mode de transmission des données (vers un smartphone, une API, une application web, etc.).



Logiciel :

Python avec la bibliothèque HX711 pour gérer les mesures.

Flask ou FastAPI si besoin d'une API pour envoyer les données.

React Native (comme tu veux faire du mobile) pour afficher les résultats sur une appli Android.



Améliorations possibles:

Affichage des mesures sur une appli mobile React Native en envoyant les données via Bluetooth ou MQTT.

Stockage des mesures sur un serveur (ex. base de données Firebase ou serveur local en Flask).



Fonctionnalités application :

connexion/inscription avec google/apple (bonus)

Création des programmes sportifs, 4 programmes (gagner en force, perte de poids, cardio, programme perso).

Intégration timer (ajout/réduction), nb de série et répétion, poids

intégration d'un graphique pour traquer le poids

Nombre de séance réalisé

enregistrement des mensurations (bonus)

Intégration d'un timer pour un circuit cardio

sauvegarde de la séance en cours si jamais l'utilisateur quitte l'application



Au niveau des points:

✅ Base de données avec utilisateurs, séances, performances → 3 points
✅ CRUD (gestion des programmes sportifs et séances) → 4 points
✅ Interaction utilisateur (ajout de programmes, timers, séries, etc.) → 2 points
✅ Algorithme avancé (suivi du poids et génération de graphiques) → 3 points
✅ Connexion Bluetooth pour envoyer les données de la balance → 6 points

Total actuel : 18 points (il manque 10 points pour atteindre 28).

Idees :

📌 Analyse et recommandations intelligentes (+3 points)
Un algorithme qui analyse l’évolution du poids et propose des ajustements aux entraînements.

📌 Mode défi ou challenge entre utilisateurs (+3 points)
Comparer ses performances avec d'autres utilisateurs (classements, records, badges).

📌 Sauvegarde Cloud et synchronisation multi-appareils (+3 points)
Permettre à l’utilisateur de retrouver ses données en changeant de téléphone.

📌 Notifications et rappels intelligents (+2 points)
Notifications pour rappeler à l’utilisateur de s’entraîner selon son programme.

📌 Mode multijoueur ou challenge entre utilisateurs (+3 à 5 points)

📌 Ajout d'un système de récompenses/motivation (badges, niveaux, classements) (+2 à 4 points)
