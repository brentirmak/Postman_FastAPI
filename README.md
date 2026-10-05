<b>(10/5) Background</b><br>
<b>1.</b> Utilizes fastapi where the following need to be installed:<br>
   fastapi uvicorn sqlalchemy pymysql python-dotenv<br>
<b>2.</b> testdb and user is required to be setup in MySQL<br>
<b>3.</b> Run uvicorn main:app –reload (in same directory where the 5 .py files reside)<br>
<b>4.</b> http://127.0.0.1:8000/docs — Swagger UI to manually test all endpoints <br>
   http://127.0.0.1:8000/items — raw JSON <br>
<b>5.</b> Tests are basic GET, POST, PUT and DELETE requests that validate errocodes/response times/response content<br>
<b>6.</b> There are 2 folders. One is for a single CRUD test. The other one is for a series of POST and PUT requesst that are executed 5 times (i.e. CREATE/UPDATE) before all of the elements are deleted via a DELETE request. The multiple create/delete logic is within post-response script(s).
