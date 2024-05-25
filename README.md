Démarrer le server : `npm start`

Démarrer le front : `cd client` + `npm start`

configuration back:

* Mettez vos informations de cluster dans `/config/db.js`
* Créez le fichier `.env` dans `/config/` dans les données suivantes
   - PORT=5000
   - CLIENT_URL=http://localhost:3000
   - DB_USER_PASS= 
   - TOKEN_SECRET=990bf68e6adf1be5f1671bba3bec692056922454 `votre clé secrète aléatoire`

Configuration front end : 

* Créez un fichier `.env` dans l'URL du serveur :
   - REACT_APP_API_URL=http://localhost:5000/ `l'url de votre serveur`


  