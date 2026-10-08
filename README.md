LPDSD - LOGICIEL DE GESTION SCOLAIRE

Fichier principal : lpdsd_app.py
Base de données : lpdsd_data/lpdsd.db

Installation :
  pip install flask reportlab
  python lpdsd_app.py
Puis ouvrir http://127.0.0.1:5000

Connexion initiale :
  utilisateur : admin
  mot de passe : admin123

Fonctions :
- authentification administrateur
- base SQLite persistante
- élèves et classes
- enseignants
- paiements et reçus PDF
- notes et bulletins PDF

IMPORTANT : changer la clé secrète et le mot de passe administrateur avant déploiement public. Cette version est un prototype fonctionnel local; pour une mise en production, ajouter HTTPS, gestion avancée des rôles, sauvegardes automatiques, CSRF, audit et déploiement sécurisé. 
