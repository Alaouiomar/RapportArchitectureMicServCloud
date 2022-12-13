
# Rapport architecture micro-service

# Objectif :

Créer une application basée sur une architecture micro-service 
qui permet de gérer les factures contenant des produits et
appartenant à un client.



# customer-service
 1 - gérer les client: 

![alt text](https://github.com/Alaouiomar/image/blob/master/customers-service.png?raw=true)

# inventory-service 
 2 - gérer les produits:

![alt text](https://github.com/Alaouiomar/image/blob/master/Product-service.png?raw=true)

# Gateway Spring cloud Gateway
3 - Configuration statique du système de routage:


![alt text](https://github.com/Alaouiomar/image/blob/master/prod-serv.png?raw=true)
![alt text](https://github.com/Alaouiomar/image/blob/master/cust-serv.png?raw=true)



# Eureka Discrovery Service
4 - Créer l'annuaire Eureka:

![alt text](https://github.com/Alaouiomar/image/blob/master/eureka.png?raw=true)


# configuration dynamique des routes de la gateway
5 - Faire une configuration dynamique des routes de la gateway

![alt text](https://github.com/Alaouiomar/image/blob/master/Product-service.png?raw=true)
![alt text](https://github.com/Alaouiomar/image/blob/master/customers-service.png?raw=true)


#  Billing-Service
6 - Créer le service de facturation Billing-Service:

![alt text](https://github.com/Alaouiomar/image/blob/master/Billing-service.png?raw=true)

# Créer un client Web Angular Products
7 -

![alt text](https://github.com/Alaouiomar/image/blob/master/products.png?raw=true)

# Créer un client Web Angular  Clients
8 -

![alt text](https://github.com/Alaouiomar/image/blob/master/customers.png?raw=true)

# Créer un client Web Angular  Factures
9 -

![alt text](https://github.com/Alaouiomar/image/blob/master/Billings.png?raw=true)

