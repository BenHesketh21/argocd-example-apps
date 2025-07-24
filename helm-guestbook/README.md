
# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell

git clone https://github.com/BenHesketh21/argocd-example-apps
# cd into the cloned directory
git checkout e0eb76636e23599c6f9abb61681ca8df51834873
helm template . --name-template development-helm-guestbook --include-crds
```