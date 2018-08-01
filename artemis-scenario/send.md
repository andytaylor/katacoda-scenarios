We can now send 100 messages to a queue called myTestQueue

``/var/lib/artemisBroker/bin/artemis producer --destination queue://myTestQueue --message-count 100``{{execute}}

If you click on the console tab and log in with the credentials you used to create the broker you will see the queue with 
the messages that you sent 

