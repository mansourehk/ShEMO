# ShEMO
Sharif Emotional Speech Database

Inorder to collect data set fast, code makes user of process parallelism and to synchronize twitter key limitations across mutiple python processes, a lightweight flask application is used as keys management server.
Execute the following commands inside `code` folder,

    nohup python -m resource_server.app &> keys_server.out&

The above command will start the flask server in port 5000 by default.
