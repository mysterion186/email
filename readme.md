# Email cleaner

Le but de ce programme est de supprimer les emails 'spam', dans le cas où on ne peut pas juste se désabonner (comme une boîte d'intérim qui envoie des missions tous les jours...)

Fonctionnement du programme :   
  -  Vous devez créer un fichier json nommé ```log.json```.
  Il devrait avoir cette structure : 
    
    
    {
        "domaine adresse mail 1 ": { 
            "mail" : "Votre adresse mail 1", 
            "mdp":"Votre mot de passe 1"
            },
        "domaine adresse mail 2 ": { 
            "mail":"Votre adresse mail 2", 
            "mdp":"Votre mot de passe 2" 
        }
    }

où ```domaine adresse mail``` correspond aux fournisseurs chez qui vous avez une adresse mail par exemple gmail ou hotmail/outlook