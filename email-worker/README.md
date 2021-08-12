# Email Sender App Simulator


##### Run the compose
`docker-compose up -d --scale worker=3`
<br>
<br>

##### Access the app on your browser
`localhost`
<br>
<br>

##### Checking emails sent on the database
`docker-compose exec db psql -U postgres -d email_sender -c 'select * from emails'`
