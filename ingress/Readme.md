## Deploy Nginx controller & Nginx resource

- kubectl apply -f namespace.yml

- kubectl apply -f admission_controller_role.yaml 

- kubectl apply -f validate_webhook.yml

- kubectl apply -f job.yml

- kubectl apply -f ingress_role.yml

- kubectl apply -f configmap.yml

- kubectl apply -f services.yml

- kubectl apply -f deploy.yml

- kubectl apply -f app_1.yml

- kubectl apply -f ingress_class.yml

- kubectl apply -f ingress_route.yml
