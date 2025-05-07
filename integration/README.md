
# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell

git clone https://github.com/balaji-singh/gitops-promoter-hydrate-demo.git
# cd into the cloned directory
git checkout 8a0d3b492d84578ac4554b434d3e082a90a11570
kustomize build ./user-configuration/staging/integration
```