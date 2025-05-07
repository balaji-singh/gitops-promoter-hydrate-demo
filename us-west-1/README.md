
# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell

git clone https://github.com/balaji-singh/gitops-promoter-hydrate-demo.git
# cd into the cloned directory
git checkout c3627630e2e69d66c657a764be1fa894de5abd2a
kustomize build ./user-configuration/production/us-west-1
```