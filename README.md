# Tp2_Docker
Tp2_Docker

question 2.A :
    l'option --production de npm permet de n'installer que le nécessaire, ce qui nous permet d'avoir un conteneur propre

question 3 : 
    pour créerl'image à l'aide du dockerfile on tape la commande : 
    docker build -t ma_super_app -f Dockerfile .

question4 :
    après avoir remplis le docker compose avec les donnés de notre image créé précedemment, on ajoute les variables d'environnements ainsi que l'environement de notre bdd mysql.

    On peut ensuite lancer "docker-compose up" 