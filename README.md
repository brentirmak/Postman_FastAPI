(7/3) Background

1. Utilizes fastapi where the following need to be installed:
   fastapi uvicorn sqlalchemy pymysql python-dotenv

2. testdb and user is required to be setup in MySQL

3. Run uvicorn main:app –reload (in same directory where the 5 .py files reside)

4. http://127.0.0.1:8000/docs — Swagger UI to manually test all endpoints 

   http://127.0.0.1:8000/items — raw JSON 

5. Tests are basic GET, POST, PUT and DELETE requests that validate error codes/response times/response content

6. There are 2 folders. One is for a single CRUD test. The other one is for a POST request that is executed 5 times (i.e. CREATE) before all of the elements are deleted via a DELETE request. The multiple create/delete logic is within post-response script(s).
