# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/jo8s/argocd-example-apps
# cd into the cloned directory
git checkout c9541a59c81dc41f1fb18df66e1d121a94494709
kustomize build ./guestbook-deploy/environments/prod
```
