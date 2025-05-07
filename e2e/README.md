
# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell

git clone https://github.com/balaji-singh/gitops-promoter-hydrate-demo.git
# cd into the cloned directory
git checkout 899c659e796a4f7ec48eee4b5049a9d5a7e2a981
kustomize build ./user-configuration/staging/e2e
```