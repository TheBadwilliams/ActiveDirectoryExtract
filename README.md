# ActiveDirectoryExtract
Un script pour l'extraction des données des utilisateurs dans Active Directory au format CSV. Ce script pourra être lancé sur demande ou programmé pour s'exécuter régulièrement. Il regroupera toutes les informations requises dans un seul fichier.

Étapes principales du script :
1. Se connecter à Active Directory.
2. Filtrer les utilisateurs.
3. Collecter les informations suivantes :
   - Nom affiché
   - Prénom
   - Nom de famille
   - Identifiant AD
   - Adresse email
   - Poste
   - Statut (actif/inactif)
   - Date de création
   - Date d’expiration
   - Date de dernière connexion
4. Exporter les données au format CSV.
Langage utilisé :
PowerShell, car il fonctionne bien avec Windows et Active Directory, et propose des commandes pour interagir facilement avec ces données.
