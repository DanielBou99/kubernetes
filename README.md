# kubernetes  
  
**kubectl run**  
Criar um pod  
  
**kubectl run nginx-pod --image=nginx:latest**  
  
**kubectl get pods**  
Listar pods  
  
**kubectl get pods --watch**  
Acompanhar pods  
  
**kubectl describe pod nginx-pod**  
Ver mais detalhes do pod  
  
**kubectl edit pod nginx-pod**  
Editar pod  
  
**kubectl apply -f .\primeiro-pod.yaml**  
Criar ou Atualizar um pod de maneira declarativa  
  
**kubectl delete pod nginx-pod**  
Deletar pod  
  
**kubectl delete -f .\primeiro-pod.yaml**  
Deletar pod  
  
**kubectl get svc**  
Listar serviços  
  