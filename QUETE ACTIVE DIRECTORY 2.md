### Création d'une OU, d'un Groupe et d'un Utilisateur

- Dans le gestionnaire serveur: Outils > Utilisateurs et ordinateurs Active Directory
- Clic droit sur wilders.lan > nouveau > unité d'organisation 
  ![OU1](https://github.com/Waxausaurus/ImgStorage/blob/main/Quest_AD2/OU1.png?raw=true)
  
- Nommer l'OU "Wilders_students"
  ![OU2](https://github.com/Waxausaurus/ImgStorage/blob/main/Quest_AD2/OU2.png?raw=true)
  
- Clic droit sur Wilders_students > nouveau > groupe 
  ![OU3](https://github.com/Waxausaurus/ImgStorage/blob/main/Quest_AD2/OU3.png?raw=true)
  
- Le nommer Students et garder coché portée globale et groupe de sécurité 
  ![OU4](https://github.com/Waxausaurus/ImgStorage/blob/main/Quest_AD2/OU4.png?raw=true)
  
- Clic droit sur Wilders_students > nouveau > utilisateur 
  ![OU5](https://github.com/Waxausaurus/ImgStorage/blob/main/Quest_AD2/OU5.png?raw=true)
  
- Insérer les infos 
  ![OU6](https://github.com/Waxausaurus/ImgStorage/blob/main/Quest_AD2/OU6.png?raw=true)
  
- Insérez un mot de passe et laisser coché "l'utilisateur doit changer le mot de passe à la prochaine ouverture de session" si vous le souhaitez (mais par principe c'est mieux quand même) 
  ![OU7](https://github.com/Waxausaurus/ImgStorage/blob/main/Quest_AD2/OU7.png?raw=true)
  
- Cliquez sur terminer
- On voit notre nouvel utilisateur dans l'OU mais pas dans le groupe 
  ![OU8](https://github.com/Waxausaurus/ImgStorage/blob/main/Quest_AD2/OU8.png?raw=true)
  
- Clic droit sur l'utilisateur > ajouter à un groupe
- Insérez le nom du groupe créé puis cliquez sur vérifier les noms (très important) puis OK 
  ![OU9](https://github.com/Waxausaurus/ImgStorage/blob/main/Quest_AD2/OU9.png?raw=true)
  
- Vérification du groupe > l'utilisateur est bien dedans 
  ![OU10](https://github.com/Waxausaurus/ImgStorage/blob/main/Quest_AD2/OU10.png?raw=true)
  