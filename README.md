# ArgoCD
Repositorio creado durante el periodo de formación, con el objetivo de documentar avances en conocimiento, realizar testeos en servidor local (minikube), guardar un backup de los despliegues etc. 

## organización
``` 
├── README.md
├── apps
│   ├── application.yaml
│   ├── goapp-test-kustomize.yaml
│   └── goapp-test.yaml
└── manifest
    ├── goapp-test
    │   ├── base
    │   │   ├── deployment.yaml
    │   │   └── service.yaml
    │   └── overlays
    │       └── dev
    └── goapp-test-kustomize
        ├── base
        │   ├── deployment.yaml
        │   ├── kustomization.yaml
        │   └── service.yaml
        └── overlays
            └── dev
                └── kustomization.yaml


```

### Recursos

Servidor Golang - [Link](https://github.com/miriamdomingo-next/goapp-test-argocd/blob/main/main.go)

Documentación completa - [Link en proceso](https://youtu.be/oHg5SJYRHA0?si=nupyUKfUsMMkasTR)