
# 🌒 Shadow Mode Deployment Example (YAML – Kubernetes)

```yaml
apiVersion: apps/v1
kind: Deployment
metadata:
  name: ai-shadow-model
spec:
  replicas: 1
  selector:
    matchLabels:
      app: shadow-model
  template:
    metadata:
      labels:
        app: shadow-model
    spec:
      containers:
      - name: shadow-model
        image: myregistry/ai-model:v2
        env:
        - name: MODE
          value: "shadow"
        ports:
        - containerPort: 8080
```

This example deploys a model in shadow mode, receiving real traffic but not impacting user experience.
