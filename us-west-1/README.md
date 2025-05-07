
# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell

git clone https://github.com/balaji-singh/gitops-promoter-hydrate-demo.git
# cd into the cloned directory
git checkout eb7ad1242542a1693307a635a12002a71951d286
kustomize build ./user-configuration/production/us-west-1
```