Keep a Track of countries you have visited and get an idea of which part of world you want to head on next! <br>
Database used - PostgreSQL
<br>
<br>

npm i pg <br>
import pg from "pg";  <br>
<br>
<br>
const db = new pg.Client ({ <br>
  user : " " , <br>
  host : " " , <br>
  database : " " , <br>
  password : " " , <br>
  port : 5432 <br>
}); <br>
<br>
<br>
db.connect(); <br>


