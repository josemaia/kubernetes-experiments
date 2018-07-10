## How to use

Based off the example in https://kubernetes.io/docs/tasks/access-application-cluster/connecting-frontend-backend/

Assuming you have a functional kubernetes cluster, first navigate to either 'staging' or 'production', and then deploy by using ```kubectl create -f namespace.yaml -f backend/backend.yaml -f frontend/frontend.yaml --save-config```.

To remove it, delete the namespace: ```kubectl delete -f namespace.yaml```.

### Testing
With a browser or ```curl```, travel to the HTTP URL reported in the frontend deployment.