# argocd-test
    Repositorio creado durante el periodo de formación, para documentar avances en conocimiento, realizar testeos en servidor local (minikube), guardar un backup de los despliegues etc. 

## organización
``` 
├── README.md
├── apps
│   ├── application.yaml -- App of apps
│   └── goapp-test.yaml -- Segunda app - Servidor web Golang - "Hello World"
└── manifest
    └── goapp-test -- Segunda app (Primera desplegada "auto" con ArgoCD)
        ├── deployment.yaml
        ├── kustomization.yaml
        ├── service.yaml
        └── overlays -- Despliegue específico con Kustomization
            └── dev
                └── kustomization.yaml

```

### Recursos

Servidor Golang - [Link](https://github.com/miriamdomingo-next/goapp-test-argocd/blob/main/main.go)

Documentación completa - [Link en proceso](https://youtu.be/oHg5SJYRHA0?si=nupyUKfUsMMkasTR)