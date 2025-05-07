
# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell

git clone https://github.com/balaji-singh/gitops-promoter-hydrate-demo.git
# cd into the cloned directory
git checkout 8288fdc68f7c7bde30f468e6291ac61ef3d27feb
kustomize build ./user-configuration/staging/e2e
```