# Deployment

kubectl apply -f kubernetes/

Verify:

kubectl get pods -n nexoryx-kafka
kubectl get svc -n nexoryx-kafka
kubectl get ingress -n nexoryx-kafka
