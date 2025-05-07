
# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell

git clone https://github.com/balaji-singh/gitops-promoter-hydrate-demo.git
# cd into the cloned directory
git checkout e9ccf096dbfc9812906bda950d8298bb6b4f2dc6
kustomize build ./user-configuration/development
```