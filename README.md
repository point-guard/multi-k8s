Need to run the following commands for the application to work

kubectl create secret generic pgpassword --from-literal PGPASSWORD=12345asdfg

Using this website, perform the following:
https://kubernetes.github.io/ingress-nginx/deploy/

kubectl apply -f https://raw.githubusercontent.com/kubernetes/ingress-nginx/nginx-0.28.0/deploy/static/mandatory.yaml
