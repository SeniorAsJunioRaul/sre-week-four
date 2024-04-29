https://github.com/SeniorAsJunioRaul/sre-week-four/tree/main
@SeniorAsJunioRaul ➜ /workspaces/sre-week-four (main) $ history
    1  minikube
    2  minikube start
    3  kubectl create ns sre
    4  kubectl get all -n sre
    5  ls -ls
    6  ls -lsR
    7  helm install upcommerce ./upcommerce -n sre
    8  helm history upcoomerce -n sre
    9  helm history upcommerce -n sre
   10  kubectl get all -n sre
   12  clear
   13  cd templates
   14  pwd
   15  ls -la
   16  cd upcommerce/
   17  ls -lsa
   18  cd templates/
   19  touch canary-deployment.yml
   21  ls -ls
   22  touch canary-service.yml
   23  ls -ls
   24  cd ..
   25  pwd
   26  cd ..
   27  ls -ls
   28  helm history upcommerce -n sre
   29  helm upgrade upcommerce ./upcommerce -n sre
   30  helm history upcommerce -n sre
   31  kubectl get deployment -n sre -o wide

   35  kubectl get all -n sre
   36  clear
   38  helm list -a -n sre
   39  helm rollback upcommerce <release_number> -n sre
   40  helm rollback upcommerce 1 -n sre
   41  helm list -a -n sre
   42  helm history upcommerce -n sre
   43  kubectl get all -n sre
   60  helm show values ./upcommerce -n sre
   61  helm show readme ./upcommerce -n sre 
   62  helm lint ./upcommerce -n sre
   63  helm template upcommerce ./upcommerce -n sre

