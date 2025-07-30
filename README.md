# Creating deployment using the manifest file

 kubectl apply -f deployment.yml

list the podes using the my-app namespace
# kubectl get pods -n my-app

Lists all Deployments in the my-app namespace.
# kubectl get deployment -n my-app

Scaling replicas for the "nginx-deploy" Deployment to handle increased traffic

 # kubectl scale deployment nginx-deploy -n my-app --replicas=5

 # kubectl scale deployment nginx-deploy -n my-app --replicas=2

# kubectl get pods -n my-app
