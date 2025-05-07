
# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell

git clone https://github.com/balaji-singh/gitops-promoter-hydrate-demo.git
# cd into the cloned directory
git checkout 0affe41824159ff6e4932897143ad1c944cc317a
kustomize build ./user-configuration/staging/integration
```