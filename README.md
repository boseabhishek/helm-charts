# smelly-helm-charts

## Usage:

```shell

# add the helm repo and name it smellysearch (say)
helm repo add smellysearch https://boseabhishek.github.io/helm-charts/

# start an instance/release named smelly-cat using reponame(added above)/chartname(charts/<chart-name>)
helm upgrade -i smelly-cat smellysearch/smelly-ui

```