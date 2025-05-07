
# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell

git clone https://github.com/balaji-singh/gitops-promoter-hydrate-demo.git
# cd into the cloned directory
git checkout e0328c75351f86a739a9b3abf9bb7b94d229d172
kustomize build ./user-configuration/staging/integration
```