### Common helm config for create pv/pvc

Example run:
```sh
helm -n test install pvc --set namespace=test --set path=/opt/pv/ .
```
