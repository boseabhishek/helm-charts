# smelly-helm-charts

## Install a smelly frontend/UI :

```shell
helm upgrade -i smelly-ui smelly-helm-charts
```

## Install a smelly frontend/UI with a custom host domain:
- create a `myvalues.yaml` file and add below:
    ```
    ingress:
        hosts:
            - host: my.custom.domain
    ```
- install it
    ```shell
    helm upgrade -i --values myvalues.yaml  smelly-ui smelly-helm-charts 
    ```

## Uninstall the release:
```shell
helm uninstall smelly-ui
```
