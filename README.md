Empty App without FTP access.
==================

[Yunohost project](https://yunohost.org/#/)

Empty App without FTP access.

Modification de la Custom Webapp + FTP de Yunohost pour ajouter la possibilité d'en installer plusieurs.
Le support FTP est dissocié dans l'app ftp_support_webapp_ynh
https://github.com/YunoHost-Apps/ftp_support_webapp_ynh

**Mise à jour du package:**  
sudo yunohost app upgrade -u https://github.com/YunoHost-Apps/multi_webapp_ynh

**Multi-utilisateur:** En fonction de l'application installée dans le conteneur.
