## Activité Pratique N°4 : Mise en oeuvre d'un micro-service 

### Objective:

1. Créer un projet Spring Boot avec les dépendances Web, Spring Data JPA, H2, Lombok
2. Créer l'entité JPA Compte
3. Créer l'interface CompteRepository basée sur Spring Data
4. Tester la couche DAO
5. Créer le Web service Restfull qui permet de gérer des comptes
6. Tester le web micro-service en utilisant un client REST comme Postman
7. Générer et tester le documentation Swagger de des API Rest du Web service
8. Exposer une API Restful en utilisant Spring Data Rest en exploitant des projections
9. Créer les DTOs et Mappers
10. Créer la couche Service (métier) et du micro service
11. Créer un Web service GraphQL pour ce micro-service 
        
        
===========================================================================

#### Projet Spring Boot avec les dépendances Web, Spring Data JPA, H2, Lombok pour gérer les comptes bancaires:
la liste des comptes dans la BD:
![image](https://github.com/lam843/TP4_micro-service/assets/78732216/97627e4d-2383-4894-829c-18d4f6189f3b)

la liste des bankaccounts:
![image](https://github.com/lam843/TP4_micro-service/assets/78732216/96cfb8c9-ba34-4716-a67d-43655decf2f7)

Consulter un compte usant un  id:
![image](https://github.com/lam843/TP4_micro-service/assets/78732216/bad09a1e-3709-4e6f-a9c3-50a5df715cd4)

Le Web Service restful  communique avec le monde exterieur via un rest API :
Le Test avec Postman usant le Id :
![image](https://github.com/lam843/TP4_micro-service/assets/78732216/9b5e61e6-266c-4681-93ce-265502eb96b7)

Creation d'un account en utilisant postman:
![image](https://github.com/lam843/TP4_micro-service/assets/78732216/818afbd9-b650-4e68-a535-e5ee3da3c595)

Mettre à jour currency du compte à l'aide de put on postman:
![image](https://github.com/lam843/TP4_micro-service/assets/78732216/b018e20d-1dbb-4a6b-96fe-4c7fd724954b)

7.Générer et tester le documentation Swagger:
![image](https://github.com/lam843/TP4_micro-service/assets/78732216/a7d755f8-6af8-4420-8df2-b510c4585fbb)

le documentation de rest API:
![image](https://github.com/lam843/TP4_micro-service/assets/78732216/08f3dfd6-d9c0-4e35-b27c-49235cf4fd84)

Tester un compte avec un id: 
![image](https://github.com/lam843/TP4_micro-service/assets/78732216/7761591b-6db6-4e91-a35f-e7870c6b4411)

Creation d'un account en utilisant post:
![image](https://github.com/lam843/TP4_micro-service/assets/78732216/864f8ce1-6d2d-4a7b-8252-d1d37b3d6790)

le compte est bien cree:
![image](https://github.com/lam843/TP4_micro-service/assets/78732216/c009d80d-9166-45c8-ac5e-742e2aa4b6db)

Tester le documentation avec postman:
![image](https://github.com/lam843/TP4_micro-service/assets/78732216/9d04a811-a431-41d1-8545-58f8d96d3073)


8. Exposer une API Restful en utilisant Spring Data Rest en exploitant des projections:

En donnant les link pour chaque account:
![image](https://github.com/lam843/TP4_micro-service/assets/78732216/323b6ef1-f2c2-4f98-b34c-d4dd987811e4)

Rechercher tous les comptes qui ont pour type des comptes d'épargne:
![image](https://github.com/lam843/TP4_micro-service/assets/78732216/8348957f-ce35-44d8-81ad-e4b607abbe84)

La projection:
![image](https://github.com/lam843/TP4_micro-service/assets/78732216/01eb3352-49e0-4299-8af8-6a65c05a774a)


9. Créer les DTOs et Mappers:

Test de DTO:
![image](https://github.com/lam843/TP4_micro-service/assets/78732216/cad65da8-e074-442a-a797-e6c5898328a0)

Mappers:
![image](https://github.com/lam843/TP4_micro-service/assets/78732216/54286ebd-1ec9-46da-8842-9288c06d1905)

11. Créer un Web service GraphQL pour ce micro-service :

liste de compte utilisant l'identifiant, le solde, la devise, le type et requête pour récupérer une liste de comptes:
![image](https://github.com/lam843/TP4_micro-service/assets/78732216/9fa35618-f226-45cb-bb7c-ed0de35b8cf7)

une query pour recuperer un compte sachant que l' Id:
![image](https://github.com/lam843/TP4_micro-service/assets/78732216/15fbda51-572c-42da-93c5-7c7bd2070609)

Exception handeler:
![image](https://github.com/lam843/TP4_micro-service/assets/78732216/9763ffd7-7895-4baf-96a4-a18032e68967)

Ajouter un compte en utilisant la mutation :
![image](https://github.com/lam843/TP4_micro-service/assets/78732216/b1195c03-1398-4fef-940f-567dba6cbcc1)


Mettre à jour le compte en utilisant l'identifiant :
![image](https://github.com/lam843/TP4_micro-service/assets/78732216/e249f1ab-af0a-4a03-8ca2-2b301b6d381e)

delete l'account :
![image](https://github.com/lam843/TP4_micro-service/assets/78732216/6b0c662f-5742-4f60-8c59-0b0674f1a1be)

BD:
![image](https://github.com/lam843/TP4_micro-service/assets/78732216/19364673-8362-42e4-bd06-d207d1f28d1e)

Rechercher par nom de client :
![image](https://github.com/lam843/TP4_micro-service/assets/78732216/c365a805-7d69-45ba-b59a-d7ef22afcaf6)






















