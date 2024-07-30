# Budget_Tracker
IT Lab Project 6th semester
## 2. Install mongodb compass and shell
  
  [MongoDB Community Edition](https://www.mongodb.com/try/download/community)<br>
  Note: Install msi package for easy installation<br>
  !Important! Install mongo shell as well, it will be mentioned in the installer<br>
  The link: [Mongo Shell](https://www.mongodb.com/try/download/shell)<br>
  Make sure its installed in the same mongodb folder under program files<br>

## 2. Download the code from this git repository

## 3. Open the folder in vscode and type the folloing commands in the terminal inside that folder:
<pre>
  Npm i express
  Npm i hbs
  npm i mongoose
  npm install -g nodemon
</pre>

  Make sure package.json and nodemodules are present under the project
  If not, manually add using:
  <pre>
    npm init
  </pre>
  and run the above commands again

## 4. To run the code:
<pre>
  nodemon src/index.js
</pre>
  Every time you save the file it will refresh dont need to run this command again and again. Just ctrl+s the index.js<br>
  Database will automatically get created<br>

## 5. open browser and type: 
  <pre>localhost:3000</pre>  
   You should see a login page<br>
   Sign up details will be showin mongodb compass in the database created automatically<br>
