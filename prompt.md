Tu es un développeur web fullstack expert. Crée-moi une application web complète de création de CV en ligne que n'importe quelle personne peut utiliser pour générer son propre CV professionnel. Tout doit être dans un seul fichier index.html (CSS et JS intégrés).
Concept de l'application :
L'utilisateur remplit un formulaire interactif avec ses informations personnelles, et l'application génère automatiquement un CV professionnel en temps réel avec aperçu instantané et option de téléchargement.
L'application doit avoir 2 parties principales :

PARTIE 1 — FORMULAIRE DE SAISIE (panneau gauche ou étapes)
Organiser la saisie en étapes (steps) avec boutons Suivant / Précédent :

Étape 1 – Informations personnelles :

Photo de profil (upload image)
Nom complet, Titre professionnel
Email, Téléphone, Adresse/Ville, Pays
LinkedIn, GitHub, Site web (optionnels)


Étape 2 – À propos :

Zone de texte : résumé/biographie professionnelle


Étape 3 – Formation :

Bouton "Ajouter une formation"
Champs par entrée : Période, Établissement, Diplôme obtenu
Bouton supprimer chaque entrée


Étape 4 – Expériences professionnelles :

Bouton "Ajouter une expérience"
Champs : Période, Poste/Fonction, Entreprise/Institution, Description des tâches
Bouton supprimer chaque entrée


Étape 5 – Compétences :

Compétences techniques : ajouter compétence + niveau (Débutant / Intermédiaire / Avancé / Expert)
Compétences personnelles (soft skills) : liste avec bouton ajouter/supprimer


Étape 6 – Projets :

Bouton "Ajouter un projet"
Champs : Nom du projet, Description, Technologies utilisées, Lien (optionnel)
Bouton supprimer chaque entrée


Étape 7 – Langues :

Bouton "Ajouter une langue"
Champs : Langue + Niveau (Notions / Bien / Très bien / Courant / Bilingue / Maternelle)


Étape 8 – Centres d'intérêt (optionnel) :

Tags ajoutables (ex : Programmation, Sport, Musique…)




PARTIE 2 — APERÇU CV EN TEMPS RÉEL (panneau droit)

Le CV se met à jour instantanément à chaque saisie (live preview)
Design CV professionnel : en-tête coloré avec photo, nom, titre, contacts
Toutes les sections s'affichent proprement avec icônes
Mise en page A4 simulée dans le navigateur


FONCTIONNALITÉS OBLIGATOIRES :

Télécharger en PDF : bouton qui génère et télécharge le CV au format PDF (utiliser la librairie jsPDF + html2canvas via CDN)
Télécharger en HTML : exporter le CV comme fichier HTML standalone
Sauvegarder / Charger : sauvegarder les données dans localStorage pour ne pas perdre la saisie, et bouton pour recharger
Réinitialiser : bouton pour tout effacer et recommencer
Choix de thème de couleur : au moins 5 couleurs de thème pour le CV (bleu, vert, rouge, violet, orange)
Choix de modèle/template : au moins 2 layouts de CV différents (ex : classique avec sidebar, moderne sans sidebar)
Barre de progression des étapes en haut du formulaire
Validation des champs obligatoires avant passage à l'étape suivante
100% responsive : sur mobile, formulaire et aperçu s'affichent en onglets (Formulaire / Aperçu)


CONTRAINTES TECHNIQUES OBLIGATOIRES :

Tout dans un seul fichier index.html — zéro fichier externe
CDN autorisés : Google Fonts (Poppins), Font Awesome, jsPDF, html2canvas
Aucun framework (pas de React, Vue, Angular) — JavaScript vanilla uniquement
Code propre, commenté, structuré
Compatible avec tous les navigateurs modernes
Prêt à déployer sur GitHub Pages, Netlify ou Render sans aucune modification


FORMAT DE RÉPONSE OBLIGATOIRE :

Donne-moi uniquement le code complet du fichier index.html
Aucune explication, aucun texte avant ou après le code
Aucune troncature — le code doit être entier de <!DOCTYPE html> jusqu'à </html>
Si le code est long, continue sans t'arrêter jusqu'à la fin complète du fichier


Ajoute aussi une page d'accueil (landing page) présentant l'application avec un bouton 'Créer mon CV' qui redirige vers le formulaire