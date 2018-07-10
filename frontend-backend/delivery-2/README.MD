## How to use

Based off the example in https://kubernetes.io/docs/tasks/access-application-cluster/connecting-frontend-backend/

Assuming you have a functional kubernetes cluster, deploy by using ```kubectl create -f backend.yaml -f frontend.yaml```.

To remove it, use the reverse: ```kubectl delete -f backend.yaml -f frontend.yaml```.

### Testing
With a browser or ```curl```, travel to the HTTP URL reported in the frontend deployment.