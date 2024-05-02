This Node.js Express API simplifies user management, offering registration, login, user data retrieval, delete and update functionalities. 
User can access to their accounts with limited authorization when it comes to deleting accounts or updating details. 
Tested with Postman and MongoDB, it ensures reliability and security.


User Registration & Log In (Authentication)
<img width="960" alt="Postman1" src="https://github.com/iansmithn/rest-api-express-node/assets/26427086/4c842e83-5c45-4f22-be7a-1c0c942ea514">
<img width="960" alt="Postman5" src="https://github.com/iansmithn/rest-api-express-node/assets/26427086/ed83129b-4e2e-4bd5-a9be-5057006c0511">

User data retreival
Once  a user is logged in a session is created.
Users have to be logged in to fetch user details. 
<img width="960" alt="Postman2" src="https://github.com/iansmithn/rest-api-express-node/assets/26427086/7d421da1-2a9d-47d7-9034-364ae2f3491e">

Authorization
Users can only update their own credentials and not anyone elses. This also applies to deleting a users as well where a user can only delete their own profile.
When a user tries an unauthorized action such as updating or deleting another user they will not be allowed
<img width="960" alt="Postman4" src="https://github.com/iansmithn/rest-api-express-node/assets/26427086/d064871c-6322-42de-97b7-0c33f76e17de">

Updating user details
<img width="960" alt="Postman3" src="https://github.com/iansmithn/rest-api-express-node/assets/26427086/8d0b0b99-f3b4-40bb-8fd0-abb02bd43ae4">

Database(Mongo DB)
<img width="960" alt="MongoDB" src="https://github.com/iansmithn/rest-api-express-node/assets/26427086/8ae127e8-f82a-496c-9fea-f3150ea322bd">





