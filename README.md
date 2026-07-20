# OPÉRATION BOUCLIER

Serious game de prévention ANDRAGOPS Académie — Sûreté (SEOD Close Protect), Secours (SST) et Incendie (EPI).

Jeu : https://andragops-academie.github.io/operation-bouclier/

## LA LIGNE ROUGE — Simulateur d'appel aux secours

Simulateur vocal d'appel au 15 / 18 / 112 pour les apprenants en formation (SST, EPI) : `la-ligne-rouge.html`

- 100 % navigateur, aucun coût, aucune clé API (reconnaissance et synthèse vocales du navigateur — Chrome recommandé, micro requis, mode clavier de secours inclus)
- Le formateur briefe l'apprenant à l'oral, choisit le scénario (hémorragie, inconscience, arrêt cardiaque, douleur thoracique, départ de feu, feu avec personne bloquée) et passe l'appareil
- L'apprenant compose le bon numéro puis dialogue à la voix avec l'opérateur, qui relance sur chaque élément manquant du message d'alerte
- Évaluation sur la grille INRS : bon numéro, nature, localisation, nombre de victimes, état, gestes effectués, risques, identité/rappel, ne pas raccrocher le premier — points doublés si l'information est donnée spontanément
- Débrief complet : score /100, badge, grille détaillée, transcription de l'appel, conseils ; historique des passages et export CSV pour le formateur

Simulateur : https://andragops-academie.github.io/operation-bouclier/la-ligne-rouge.html

## MODE ARÈNE — Quiz sécurité en direct (multijoueur)

Quiz collectif type « la salle répond en même temps » pour animer une session : `mode-arene.html`

- Trois thèmes prêts : Secours SST 🩹, Incendie EPI 🔥, Sûreté 🛡️ (banque de questions à choix multiples, tirage aléatoire)
- L'animateur crée une partie → un code à 4 chiffres s'affiche ; les apprenants rejoignent depuis leur téléphone et répondent en simultané ; classement en direct après chaque manche, podium final
- Score au temps : bonne réponse rapide = plus de points (500 + bonus de rapidité)
- **Mode démo** immédiat (joueurs simulés, un seul écran) pour tester sans rien configurer
- **Vrai multijoueur cross-appareils** via Supabase Realtime Broadcast : coller l'URL + la clé anon du projet dans l'écran ⚙️ Connexion (aucune table à créer). Accès direct apprenant : `mode-arene.html?role=player&c=CODE`
- 100 % navigateur ; la librairie Supabase est chargée depuis un CDN (nécessaire seulement pour le mode en direct)

Arène : https://andragops-academie.github.io/operation-bouclier/mode-arene.html

ANDRAGOPS Académie · Strasbourg · andragops-academie.fr
