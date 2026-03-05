# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/jo8s/argocd-example-apps
# cd into the cloned directory
git checkout 96e59ba228f0d1672db7b1cec34b7c4b32800368
kustomize build ./guestbook-deploy/environments/development
```
