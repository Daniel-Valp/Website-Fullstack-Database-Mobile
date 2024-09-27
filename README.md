# Website-Fullstack-Database-Mobile
Fullstack website made for school with a group with frontend, backend, database and mobile.

(Complete Details can be seen on the Relatório.pdf writen in portuguese)

Website : Made with HTML, CSS, React and JavaScript
Api: Done in node.js, Express.js, Sequelize, JWT (JSON Web Token), bcrypt, Cloudinary, others...
Database: PostgreSQL, PgAdmin
Mobile: Dart

==============================================================================================================================

Start web
Go to the web folder and run the command npm install and then npm start.

Start backend
Go to the backend folder and run the command npm install and then npm start.

Start Mobile
. cd .\movel_pint\
. Start Emulator
. Npm Run
if problems do
. Run > Start Debugging

=================================================================================================================================

To connect the database in pgAdmin.
Go to Servers > Register > Server > Connection:
Host name/address: dpg-cnge0pq1hbls73fq15vg-a.frankfurt-postgres.render.com
Port: 5432
Username: manager
Password: 2Tes25NellX6Es9MM92Mg1a5g59Jz5J3

How to use Local Database in the API

Create a file in the src/data directory named database.js and add the following, replacing the "x" values while keeping the rest:
export const DB_CONFIG = {
    DATABASE: "x",
    USERNAME: "x",
    PASSWORD: "x",
    HOST: "localhost",
    PORT: "5432",
    DIALECT: "postgres",
    SSL_ENABLED: false,
};

The routes have the following structure:
localhost:8000/<table_name>/<list/get/create/update/delete>

If it is a GET, PUT, or DELETE request, it takes an additional parameter, like /1, for example.
List: POST
Get: GET
Create: POST
Update: PUT
Delete: DELETE


Web: https://web-6grl.onrender.com/
Backend: https://api-vwah.onrender.com/

! First start Api and then Web ! 

Mobile app available on the website /sobre

Admin: administrador Pass: 123
User: utilizador Pass: 123

=================================================================================================================================

Images: 

Website

![Main](https://github.com/user-attachments/assets/b374a9bb-52f1-493b-882c-469066b6b618)
![Backend](https://github.com/user-attachments/assets/1040c423-2dc5-4186-9cb4-9f55bafd1dba)

Mobile

![Mobile](https://github.com/user-attachments/assets/ea6063fe-f3cd-4cad-bf4a-49adde56b5a1)
