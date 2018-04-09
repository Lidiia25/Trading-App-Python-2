# data602_assignment2

Please use following command to run docker image:

docker run --name web -it --rm -p 5000:5000 lidiia25/data602_2 /bin/bash -c "cd /var/www; mongod --fork --syslog; mongoimport --db data602 --collection balance --file db.json; python3 server.py"

https://hub.docker.com/r/lidiia25/data602_2/


This is a test trading app, which was written on python language. You can buy and sell stocks, check history of transactions, and see unrealized and realized profits/losses, and also see basic statistic analisys. 
