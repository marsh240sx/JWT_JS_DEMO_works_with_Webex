# JWT_JS_DEMO_works_with_Webex

Based off of https://github.com/msatyan/JWT_JS_Demo and modified to work with Webex [Guest Issuer](https://developer.webex.com/docs/guest-issuer) applications.

Generate Webex JWT in pure Javascript using CryptoJS. 

This will only generate the JWT, which you can copy of from the page and then issue a POST to https://webexapis.com/v1/jwt/login to exchange the JWT for the guest access token. 

POST example using cURL: 
```
curl --location --request POST 'https://webexapis.com/v1/jwt/login' \
--header 'Authorization: Bearer YOUR_JWT'
```
