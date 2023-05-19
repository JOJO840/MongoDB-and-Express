# MongoDB-and-Express

Apply the yaml files in  "k8s-commands.md" to you cluster, following the order of the files.
If completed successfully, there will be "mongodb" and "mongo-express"pods running in the cluster.

In case of port conflicts, it is possible to connect to mongodb and express using port-forwarding into the svc of express: kubectl port-forward svc/mongo-express-service 8082:8081.

Mongo-express can be accessed at localhost:8082.

<img width="921" alt="image" src="https://github.com/JOJO840/MongoDB-and-Express/assets/92030077/882d9b48-4459-4690-abac-ef57a5e1eb9e">                        
