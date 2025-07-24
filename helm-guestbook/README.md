
# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell

git clone https://github.com/BenHesketh21/argocd-example-apps
# cd into the cloned directory
git checkout 71cc081aa58acd21157e16848e3513a189cf90dd
helm template . --name-template staging-helm-guestbook --include-crds
```