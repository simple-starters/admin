# Generator Repository Naming Conventions

In the `simple-starters` org, the naming pattern for generators is

```
generator-<application-framework>-<deployment-platform>--<deployment-platform-option-1>-<deployment-platform-option-2>
```

Example:

A generator that targets Spring Boot applications for Kubernetes and uses the tools `kustomize` and `skaffold` to manage Kubernetes resource files would be in a a GitHub repository named `generator-boot-k8s-kustomize-skaffold`


