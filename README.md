# Blue-Green Deployment en Kubernetes

Este proyecto implementa una estrategia de **Blue-Green Deployment** en un clúster de Kubernetes local utilizando Minikube. El objetivo es demostrar cómo realizar actualizaciones sin interrupción del servicio y cómo revertir cambios (rollback) de manera controlada.

## 📋 Requisitos previos

- **Minikube** instalado y configurado
- **kubectl** instalado
- Driver de Docker o VirtualBox configurado en Minikube

## 📁 Estructura del proyecto
Blue-Green-deployment-en-K8s/

├── namespace.yaml

├── bluedeployment.yaml

├── greendeployment.yaml

├── service.yaml

└── README.md
