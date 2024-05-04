This Node.js Express API simplifies user management, offering registration, login, user data retrieval, delete and update functionalities. 
User can access to their accounts with limited authorization when it comes to deleting accounts or updating details. 
API tests have done using ThunderClient/Postman and MongoDB.


User Registration & Log In (Authentication)
<img width="960" alt="TC1" src="https://github.com/iansmithn/rest-api-express-node/assets/26427086/71cb0d4f-6af0-46fb-b19b-8f72a972e7ae">
<img width="960" alt="TC2" src="https://github.com/iansmithn/rest-api-express-node/assets/26427086/fb942e03-3513-4534-8fa8-fcf58c6ccd62">


User data retreival:
Once  a user is logged in a session is created.
Users have to be logged in to fetch user details. 
<img width="960" alt="TC3" src="https://github.com/iansmithn/rest-api-express-node/assets/26427086/a965c81c-4a1e-4e52-9c5e-d95baaaa8719">

Authorization:
Users can only update their own credentials and not anyone elses. This also applies to deleting a users as well, where a user can only delete their own profile.
When a user tries an unauthorized action such as updating or deleting another user they will not be allowed.
<img width="960" alt="TC4" src="https://github.com/iansmithn/rest-api-express-node/assets/26427086/756baef2-ccac-4861-936c-ab274ce96eed">


Updating (Patch) user details with the right authorization:
<img width="960" alt="TC5" src="https://github.com/iansmithn/rest-api-express-node/assets/26427086/ee9506c8-6d1a-471f-9e4e-6e68aa97f46f">

Database(Mongo DB):
<img width="960" alt="MongoDB" src="https://github.com/iansmithn/rest-api-express-node/assets/26427086/bf7a50ce-7d8d-4f1d-ada1-4fe7a5dd3059">





