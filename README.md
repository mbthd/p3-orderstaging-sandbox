# p3-orderstaging-sandbox
practice workspace for project


Sandbox
p3-custorderstaging
Mkdir
	server
		node.js
		express
		pg
		knex
		bookshelf
		pug or ejs
	client

env setup
	client
	server

Postgresql db
	run:
	psql
	\connect dbname
	\l
	\dt
	\connect stagedorders
	created stagedorders

Server
express custorderstaging
  install dependencies:
     $ cd custorderstaging && npm install
   run the app:
     $ DEBUG=custorderstaging:* npm start


Git



echo "# p3-orderstaging-sandbox" >> README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin https://github.com/mbthd/p3-orderstaging-sandbox.git
git push -u origin master

push an existing repository from the command line

git remote add origin https://github.com/mbthd/p3-orderstaging-sandbox.git
git push -u origin master





