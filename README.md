# Tyro Graduate Assessment

## Part A

Word DOCX

## Part B

I have invited you to the Postman workspace. However, I also have provided the file to be imported manually to Postman. Just import both JSON files. It should works

### Assumptions:

- Required to use the GET instead of POST
- Ideal API respond time is 250ms
- Using the <https://public.cdr.tyro.com/cds-au/v1/banking/products> instead of <https://api.cdr.tyro.com/cds-au/v1/banking/products>
- Allowed to use a random array generator to simulate the ERROR 400
- No Auth needed, force HTTPS and Cookies disabled

### Pre-requisites:

- Tyro OpenAPI specification from the website
- Postman
- Javascript knowledge for creating automated testing scripts 

### Issues found/faced:

- The API service was down for the whole day so needed to wait for the API service to be restored.
- Need to fidget around since Postman Github Sync is only available to paid enterprise user.
- For Business Load Product Details, sometimes it give Error 406 instead of Error 400 because on the documentation Error 400 and Error 406 can be reproduced by xv lower than 3
