# Psa ConnectedCar Api 🚗

## Introduction
Ce repository a pour vocation d'expliquer et de partager des informations autours de l'API de PSA. 
Cette dernière est documentée à cet URL mais la documentation est assez pauvre et pourrais être clarifée.
N'hésitez pas à contribuer pour améliorer cette documentation 👍

## Routes

### Login
Tout d'abord l'api de PSA utilise OAuth2 avec un authorization code. La première étape est donc de récupérer un code.
Si vous utilisez Insomnia ou Postman, il est plutôt simple de générer un Token. Il suffit de configurer une authentification :
![image](https://github.com/user-attachments/assets/0a42083e-a274-4256-bd00-80f867f2d47b)

https://idpcvs.peugeot.com/am/oauth2/authorize?client_id=1eebc2d5-5df3-459b-a624-20abfcf82530&response_type=code&redirect_uri=mymap://oauth2redirect/fr&scope=openid


## Variables
Client Id : `1eebc2d5-5df3-459b-a624-20abfcf82530`

Client Secret : `T5tP7iS0cO8sC0lA2iE2aR7gK6uE5rF3lJ8pC3nO1pR7tL8vU1`

Authorization Url : `https://idpcvs.peugeot.com/am/oauth2/authorize`

Realm : `clientsB2CPeugeot`

API Base Url : `https://api.groupe-psa.com/connectedcar/v4/`


Ces infomrations peuvent être trouvées en décompilant l'APK MyPeugeot
