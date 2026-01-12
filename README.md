# Purpose
A brief example of deploying Rabbit on Kubernetes

# Deployment
Apply the operator first with `kubectl apply -f operator/cluster-operator.yml`

Then, apply cluster configs with `kubectl apply -n <namespace> -f clusters/cluster1.yml`