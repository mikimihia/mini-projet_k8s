# Objectif Mini-projet kubernetes : 
Creation d'un PV (volume persistant) de type local /mini-data/,
Creation dans un PVC rattachant l'application Wordpress dans le manifest "mysql-deployment.yml" au pv-local-1,
Edition d' un manifest de deploiement de Mysql contenant un service de type ClusterIP,
Creation dans un PVC rattachant l'application Wordpress dans le manifest "wordpress-deployment.yml",
Edition d'un deploiement Wordpress avec les variables d'env pour ce connecter a Mysql,
Creation d'un service de type nodeport pour exposer le frontend de wordpress,
Encodage de l'authetification aux ressources mysql et wordpress,
Test et connexion au site wordpress et 
Validation du mini-projet K8S

![Capture d’écran (16)](https://github.com/mikimihia/mini-projet_k8s/assets/44511981/609843eb-8e17-4645-871e-e7d70bed48d7)
