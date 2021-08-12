# Email Sender App Simulator

##### Run the compose
<br> `docker-compose up -d --scale worker=3`

##### Access the app on your browser
<br>`localhost`

##### Checking emails sent on the database
<br> `docker-compose exec db psql -U postgres -d email_sender -c 'select * from emails'`