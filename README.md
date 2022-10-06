# 0233-MARKDOWN-Synoptique_gnp_gap_gpp

## Mes Utilitaires Git

|Commande|gnp|gap|gpp|
|:---:|---|---|---|
|**Titre**|**Git New Project to GitHub**|**Git Add Project to GitHub**|**Git Add Commit Push Project to GitHub**|
|**Fichier**|`gnp.sh`|`gap.sh`|`gpp.sh`|
|**Usage**<br />(Pas de guillemet !)|`gnp folderName`|`gap repositoryName`|`gpp commitMessage`|
|**<span style="color: orange">Proposition nouveau titre</span>**|**<span style="color: orange">Make local project folder and push it to an existing repository to GitHub</span>**|**<span style="color: orange">Push the existing local project folder to GitHub repository</span>**|**<span style="color: orange">Git Add Commit Push Project to GitHub</span>**|
|**Instructions**|1. Création dossier<br />2. Aller dans dossier<br />3. Renseignement du README avec le nom du dossier en titre h1<br />4. Initialisation Git<br />5. Ajout à l'index<br />6. Commit<br />7. Création branche `main` et remplacement en force de la branche `master`<br />8. Connexion au dépôt<br />9. Envoi des données et mise à jour du dépôt|1. ***Le dossier existe***<br />2. ***On est dans le dossier***<br />3. Renseignement du README avec le nom du dossier en titre h1<br />4. Initialisation Git<br />5. Ajout à l'index<br />6. Commit<br />7. Création branche `main` et remplacement en force de la branche `master`<br />8. Connexion au dépôt<br />9. Envoi des données et mise à jour du dépôt|1. ***Le dossier existe***<br />2. ***On est dans le dossier***<br />3. ***Le README est déjà renseigné***<br />4. ***Git est déjà initialisé***<br />5. Ajout à l'index<br />6. Commit<br />7. **La  branche `main` est déjà créée et on est dessus**<br />8. ***Le dépôt est déjà connecté***<br />9. Envoi des données et mise à jour du dépôt|
|**Dossier / Dépôt**|*[0180-BASH-gnp-Git_New_Project_to_GitHub](https://github.com/LDdvlp/0180-BASH-gnp-Git_New_Project_to_GitHub)*|*[0181-BASH-gap-Git_Add_Project_to_GitHub](https://github.com/LDdvlp/0181-BASH-gap-Git_Add_Project_to_GitHub)*|*[0201-BASH-gpp-Git_Add_Commit_Push_Project_to_GitHub](https://github.com/LDdvlp/0201-BASH-gpp-Git_Add_Commit_Push_Project_to_GitHub)*|
|1|mkdir|-|-|
|2|cd|-|-|
|3|echo to `README.md`|echo to `README.md`|-|
|4|git init|git init|-|
|5|git add|git add|git add|
|6|git commit -m "v.1.0.0"|git commit -m "v.1.0.0"|git commit -m|
|7|git branch -M main|git branch -M main|-|
|8|git remote add origin|git remote add origin|-|
|9|git push -u origin main|git push -u origin main|git push -u origin main|


