# Strapi application

A quick description of your strapi application

# Pour créer un utilisateur 

/auth/local/register

Body :

{
	"password": "example",
	"email": "examples@examples.com",
	"username" : "example"
}

Ensuite récupération du token jwt 

Pour voir les poissons: /poissons   et dans l'onglet "Authorization" Type "Bearer" et vous copiez votre token

Pour ajouter un poissons : /poissons/add 

Body: 

{
        "id": 1,
        "Nom": "Brochet",
        "Taille": 80,
        "Poids": 8,
        "Lieu": "Cognac",
        "Date": "2020-02-12",
        "created_at": "2020-02-17T18:21:17.285Z",
        "updated_at": "2020-02-17T18:21:17.285Z"
    }






