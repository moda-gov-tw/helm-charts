Before push do
```
helm package charts/*
mv *.tgz docs
helm repo index docs --url https://moda-gov-tw.github.io/helm-charts/
```