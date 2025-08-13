Install the minikube using below link:
  - https://minikube.sigs.k8s.io/docs/start/

Create deployment.yaml file.
Create service.yaml file. 

Apply deployment and service file 
  - kubectl apply -f deployment.yaml
  - kubectl apply -f service.yaml

Verify pods and service 
  - kubectl get pods -A
  - kubectl get svc 

Access the app
  - minikube service nginx-image
  - http://minikube-ip:30007

Describe resources 
  - kubectl describe pod <pod-name>

Check logs
  - kubectl logs <pod-name>

You can check the output of the service on kubernetes dashboard  
  - minikube dashboard

All the screenshort attached on minikube.pdf file
