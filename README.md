# Mon application de gestion de livres

Cette application fournit une API pour gérer une liste de livres, permettant d'ajouter, de modifier, de supprimer et de récupérer des informations sur les livres.

## Routes HTTP

- GET /livres : Récupérer la liste de tous les livres.
- POST /livre : Ajouter un nouveau livre.
- GET /livre/{id} : Récupérer les informations d'un livre spécifique.
- PUT /livre/{id} : Mettre à jour les informations d'un livre existant.
- DELETE /livre/{id} : Supprimer un livre existant.
- GET /total_livres : Obtenir le nombre total de livres.
