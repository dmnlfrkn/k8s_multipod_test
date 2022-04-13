# multipod_test
 !!! You must have any kubernetes platform. (Docker, minikube etc.)
 
 Run this code ``` kubectl apply -f podmulticontainer.yaml ```
 
 Yaml file should be same folder and in the yaml file you should change the ```https://raw.githubusercontent.com/dmnlfrkn/k8s_multipod_test/main/index.html``` part to your address
 
 Then make port mapping ``` kubectl port-forward pod/multicontainer 8080:80 ```
 
 When you change the index of index.html, you can see the changing at ``` http://127.0.0.1:8080 ```
 
 
