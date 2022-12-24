# sheeps-helm
Tests
```
helm template -f sheeps/values_copy.yaml  sheeps ./sheeps
```

```
source variables
```

# Create new and modify files
```
helm create $APP_NAME
```

helm fetch sheeps/sheeps-helm --version 0.1.0

helm package sheeps
mv sheeps-0.1.0.tgz sheeps-helm/
helm repo index sheeps-helm/ --url https://ninesbr.github.io/sheeps-helm/