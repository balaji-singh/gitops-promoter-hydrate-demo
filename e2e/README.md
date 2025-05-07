
# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell

git clone https://github.com/balaji-singh/gitops-promoter-hydrate-demo.git
# cd into the cloned directory
git checkout e11ddc8e0b9c2c074bcb0ab193bdf7b0792fdc88
kustomize build ./user-configuration/staging/e2e
```