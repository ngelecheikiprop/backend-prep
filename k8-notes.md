#K8 short notes 
store insentive data in config map
store passwords and the rest in secrets 

`kubect describe pod` to debug 
`kubectl get pod --watch` to keep seeing in real time

make sure service is connected to pod by seeing the ip exposed 


deployment holds config of contairs(ports, image )

1:33 - going to mongo express

while deplyments pods can change but k8 service makes sure that you can still access the same 