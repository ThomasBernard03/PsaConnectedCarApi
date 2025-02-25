# PSA ConnectedCar API 🚗

<img width="328" alt="image" src="https://github.com/user-attachments/assets/5f2595d8-4e07-4852-bcec-18928832a1e4" />


## Introduction  
This repository aims to explain and share information about the PSA API.  
The API is documented at this URL, but the documentation is quite poor and could be clarified.  
Feel free to contribute to improve this documentation 👍  

## Routes  

### Login  
First, the PSA API uses OAuth2 with an authorization code. The first step is to obtain a code.  
If you use Insomnia or Postman, it is quite easy to generate a token. You just need to configure an authentication:  
![image](https://github.com/user-attachments/assets/0a42083e-a274-4256-bd00-80f867f2d47b)  

[Authorization URL](https://idpcvs.peugeot.com/am/oauth2/authorize?client_id=1eebc2d5-5df3-459b-a624-20abfcf82530&response_type=code&redirect_uri=mymap://oauth2redirect/fr&scope=openid)

## Variables  

- **Client Id**: `1eebc2d5-5df3-459b-a624-20abfcf82530`  
- **Client Secret**: `T5tP7iS0cO8sC0lA2iE2aR7gK6uE5rF3lJ8pC3nO1pR7tL8vU1`  
- **Authorization Url**: `https://idpcvs.peugeot.com/am/oauth2/authorize`  
- **Realm**: `clientsB2CPeugeot`  
- **API Base Url**: `https://api.groupe-psa.com/connectedcar/v4/`  

These details can be found by decompiling the MyPeugeot APK.
