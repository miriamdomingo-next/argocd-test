# argocd-test
    - Repositorio creado durante el periodo de formación, para documentar avances en conocimiento, realizar testeos en servidor local (minikube), guardar un backup de los despliegues etc. 

## organización
``` 
├── apps
│   ├── application.yaml -- App of apps
│   └── goapp-test.yaml -- Primera app - Servidor web golang "Hello World"
│
├── manifest -- Contiene todos los ficheros requeridos para lanzamiento de apps en ArgoCD
│   └── goapp-test -- Primera app
│       ├── deployment.yaml
│       └── service.yaml
```