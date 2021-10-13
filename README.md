# JWT_JS_DEMO_works_with_Webex
Generated Webex JWT in pure Javascript using CryptoJS. 

This will only generate the JWT, which you can copy of from the page and then issue a POST to https://webexapis.com/v1/jwt/login to exchange the JWT for the guest access token. 

Post example using cURL: 
```
curl --location --request POST 'https://webexapis.com/v1/jwt/login' \
--header 'Authorization: Bearer YOUR_JWT'
```
